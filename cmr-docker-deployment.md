# CMR Odoo 17 Docker deployment

The customer application runs as isolated Odoo 17 services while sharing the
existing PostgreSQL 16 server:

| Profile | Service | Database | Default URL | Addons | Filestore volume |
| --- | --- | --- | --- | --- | --- |
| Head Office | `odoo-cmr-ho` | `cmr_ho_test` | `http://localhost:8074` | `RetailEnterprise/HeadOffice`, Enterprise 17, project addons | `cmr-ho-web-data` |
| Store | `odoo-cmr-store` | `cmr_store_test` | `http://localhost:8075` | `RetailEnterprise/Store`, project addons | `cmr-store-web-data` |
| CTL Fashion | `odoo-cmr-ctl-fashion` | `cmr_ctl_fashion` | `http://localhost:8081` | `RetailEnterprise/Store`, Enterprise 17, project addons | `cmr-ctl-fashion-web-data` |

Database inspection endpoints are isolated too:

| Database | Viewer | Read-only MCP |
| --- | --- | --- |
| Head Office | `http://localhost:8076` | `http://localhost:8078` |
| Store | `http://localhost:8077` | `http://localhost:8079` |
| CTL Fashion | `http://localhost:8082` | `http://localhost:8083` |

The development instance remains at `http://localhost:8069`. Override the customer
ports with `CMR_HO_PORT` and `CMR_STORE_PORT` when necessary.

## Required local inputs

- Keep the supplied customer source under `RetailEnterprise/`; it is intentionally
  ignored by Git. Override `CMR_HO_ADDONS_PATH` and `CMR_STORE_ADDONS_PATH` when
  using another local source root.
- Place the licensed Odoo 17 Enterprise addons under `enterprise-addons/`, or set
  `ODOO_ENTERPRISE_ADDONS_PATH` to the entitled checkout. The current SSD layout
  uses `/Volumes/OdooData/ODOO-ERP/enterprise-addons`. Colima must mount both the user's
  home directory and `/Volumes/OdooData`; the SSD mount is read-only inside the VM.
- Set `ODOO_AUTO_BACKUP_ADDON_PATH` when `auto_database_backup` is supplied outside
  the Enterprise tree. The current path is
  `/Volumes/OdooData/ODOO-ERP/vendor-addons/auto_database_backup`.
- A Community/LGPL license file is not an Enterprise subscription credential and
  cannot be used to download or reconstruct Enterprise source. Obtain the Odoo 17
  Enterprise repository checkout from an account authorized by the customer's
  subscription, or obtain the exact source bundle from the customer.
- Obtain the matching database dump and filestore for each database. Never pair a
  dump with a filestore from a different backup time.
- Confirm OPL/proprietary module entitlements before running or distributing them.

The SSD Enterprise tree supplies the required `account_accountant`, `account_asset`,
`approvals`, `approvals_purchase`, `hr_referral`, `l10n_in_hr_payroll`, `planning`,
and `sale_purchase_inter_company_rules` modules. Its OEEL-1 source must remain
separate from custom addons and must not be published or redistributed.

## Build

```bash
docker-compose --profile customer build odoo-cmr-ho odoo-cmr-store
docker-compose --profile customer config --quiet
```

The customer image adds only packages imported by supplied addons. It deliberately
does not downgrade Odoo's Werkzeug, lxml, or MarkupSafe libraries. The HO backup
addon and installed Indian QR localization additionally require `boto3`, `dropbox`,
`pyncclient`, `nextcloud-api-wrapper`, and `PyJWT`.

## Restored metadata compatibility

After the Enterprise source was attached, 1,337 previously quarantined views,
338 menus, three asset directives, and 723 approval activities were restored.
Eleven views remain inactive because their stored XML is incompatible with the
mounted code/schema: one custom `pi.po.grc` report, one modified Approvals product
line view, one online synchronization view, and eight payroll form extensions.
Keep these disabled until their owning source/schema is aligned and each view
passes ORM validation.

## Restore

The restore helper refuses to overwrite an existing target database:

```bash
tools/cmr_restore.sh ho /absolute/path/ho.dump /absolute/path/ho-filestore
tools/cmr_restore.sh store /absolute/path/store.dump /absolute/path/store-filestore
tools/cmr_restore.sh ctl-fashion /absolute/path/dump.sql /absolute/path/filestore
```

It accepts PostgreSQL custom-format dumps, plain SQL dumps, and gzip-compressed
SQL dumps. For an Odoo ZIP
backup, extract `dump.sql` and the `filestore/` directory first.

## Start and inspect

```bash
docker-compose --profile customer up -d odoo-cmr-ho odoo-cmr-store
docker-compose --profile customer up -d odoo-cmr-ctl-fashion
docker-compose --profile customer up -d db-workbench-cmr-ho db-workbench-cmr-store
docker-compose --profile customer up -d db-workbench-mcp-cmr-ho db-workbench-mcp-cmr-store
docker-compose ps
docker-compose logs --tail=200 odoo-cmr-ho
docker-compose logs --tail=200 odoo-cmr-store
docker-compose logs --tail=200 odoo-cmr-ctl-fashion
```

Both configurations have `max_cron_threads = 0`, database listing disabled, and an
exact database filter. Before enabling cron, neutralize outgoing email, payment,
e-invoicing, e-waybill, Tally/SAP, backup, and HO/Store synchronization settings.
Rotate all restored API keys and credentials.

Inside Docker, Store should address Head Office as `odoo-cmr-ho:8069`; do not use
`localhost` or an old machine IP. Keep production-like synchronization disabled
until a bounded test confirms authentication, idempotency, retry behavior, company
mapping, product identity, taxes, lots, journals, and POS session mapping.

On first startup, `cmr-start` creates only a minimal Odoo database when the fixed
database name does not exist. It never replaces an existing database. Restore the
customer dump before first startup when customer data is available.

## Module updates

Do not begin with `-u all`. First verify registry startup against the restored
database. Then update only the intended customer modules in dependency order:

```bash
docker-compose --profile customer run --rm odoo-cmr-store \
  --entrypoint /entrypoint.sh odoo -d cmr_store_test \
  -u nhcl_customizations --stop-after-init --max-cron-threads=0
```

For a clean Store database, the tested initial application set is
`nhcl_customizations,nhcl_store_to_ho_transactions,nhcl_pos_sale`. The customer
image includes the spreadsheet dependencies used by those modules, including
`pandas`, `odfpy`, `openpyxl`, `xlrd`, and `xlsxwriter`, plus
`httpagentparser` and `paramiko` used by terminal-access detection and SSH lookup.

Take a new database and filestore snapshot before every update attempt.

## Missing Store filestore

A database-only restore leaves attachment metadata in `ir_attachment` but not the
files referenced by `store_fname`. Standard spreadsheet dashboard snapshots can
be regenerated from their module JSON files through the
`spreadsheet_binary_data` ORM field. Customer uploads, product images, documents,
and other attachment-backed data cannot be reconstructed from PostgreSQL; restore
the matching Store filestore to recover them. Do not pair the HO filestore with
the Store database.
