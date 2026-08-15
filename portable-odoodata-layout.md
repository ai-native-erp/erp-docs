# Portable OdooData layout

The complete local Odoo 17 development instance is kept on the external APFS
volume mounted at `/Volumes/OdooData`:

| Path | Purpose |
| --- | --- |
| `/Volumes/OdooData/ODOO-ERP` | Git workspace, Compose file, custom addons, tools, and documentation |
| `/Volumes/OdooData/colima-runtime/.colima` | Colima VM, Docker images, containers, networks, and named volumes |
| `/Volumes/OdooData/ODOO-ERP/enterprise-addons` | Local, Git-ignored licensed Odoo 17 Enterprise dependency; do not redistribute |
| `/Volumes/OdooData/ODOO-ERP/vendor-addons` | Local, Git-ignored third-party addon dependencies |
| `/Volumes/OdooData/odoo-backups` | Source database dumps and filestore backups |
| `/Volumes/OdooData/odoo-instance-kit` | Machine-readable inventory and project image archive |

The compatibility paths on this Mac are symbolic links:

```text
/Users/srste/Documents/ODOO-ERP -> /Volumes/OdooData/ODOO-ERP
/Users/srste/.colima -> /Volumes/OdooData/colima-runtime/.colima
```

## Start on this Mac

1. Attach the SSD and confirm that it is mounted as `/Volumes/OdooData`.
2. Run `colima start`.
3. Run `docker-compose up -d` from `/Volumes/OdooData/ODOO-ERP`.
4. Run `tools/verify_odoodata_layout.sh`.

Stop Colima before ejecting the SSD. Detaching it while the VM or PostgreSQL is
running can corrupt the Docker data disk.

## Reuse on this Mac

Install Colima and the Docker CLI, attach the SSD at `/Volumes/OdooData`, and
restore the compatibility links if required:

```sh
ln -s /Volumes/OdooData/ODOO-ERP "$HOME/Documents/ODOO-ERP"
ln -s /Volumes/OdooData/colima-runtime/.colima "$HOME/.colima"
colima start
docker-compose -f /Volumes/OdooData/ODOO-ERP/compose.yaml up -d
```

The relocated Colima VM is the fastest replica on this Mac because it
contains the current Docker volume state, including the restored HO and Store
databases and filestores. The image archive in `odoo-instance-kit` is a secondary
recovery input; standard base images can also be pulled and project images rebuilt
from the Compose file.

## Replicate on another Mac

Colima VM metadata contains host-specific absolute paths, so do not assume that
copying the VM directory alone is portable to a different username or Colima
version. On another Apple Silicon Mac, create a clean Colima instance, load the
project image archive with `docker load`, start the Compose stack from the SSD,
and restore the database and filestore backups using the documented CMR restore
workflow. If reusing the captured VM directly, first review the mounts in
`colima-runtime/.colima/default/colima.yaml` and replace host-specific paths.

The `.env` file is intentionally outside Git but travels with the SSD workspace.
Review its absolute addon paths if the external volume is mounted under a
different name. Never copy or publish the Enterprise addon tree unless the target
machine and users are covered by the applicable Odoo Enterprise agreement.

The CTL Fashion Odoo backup is stored at
`/Volumes/OdooData/odoo-backups/CMR_CTL_FASHION`. A compatibility symlink at
`/Volumes/OdooData/CMR_CTL_FASHION` preserves the supplied path. Its database and
filestore restore into the isolated `cmr_ctl_fashion` Compose service; the source
backup remains immutable recovery input.
