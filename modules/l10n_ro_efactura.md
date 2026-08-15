---
layout: page
title: "Romania - Send E-Factura (l10n_ro_efactura)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_ro_efactura/
nav_order: 0
---
# Romania - Send E-Factura — `l10n_ro_efactura`

**Source:** [`agents/modules/generated/l10n_ro_efactura.yaml`](../../agents/modules/generated/l10n_ro_efactura.yaml) · **Wiki:** [`knowledge/modules/l10n_ro_efactura/overview.md`](../../knowledge/modules/l10n_ro_efactura/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_ro_efactura</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Romania - Send E-Factura</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_ro_efactura</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ro_efactura"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Bridge module for sending Romanian E-Factura to the SPV

## Direct dependencies

[`l10n_ro_edi`](l10n_ro_edi.md)

## Reverse dependencies (modules that depend on this)

[`l10n_ro_cpv_code`](l10n_ro_cpv_code.md), [`l10n_ro_edi_stock`](l10n_ro_edi_stock.md), [`l10n_ro_efactura_synchronize`](l10n_ro_efactura_synchronize.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>l10n_ro_edi.document</code></div><div class="role">defined by <code>l10n_ro_efactura</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_ro_efactura</code></div></div>
<div class="model"><div class="name"><code>account.move.send</code></div><div class="role">extended by <code>l10n_ro_efactura</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>l10n_ro_efactura</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>l10n_ro_efactura</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_ro_cpv_code` | required_by | `agents/modules/generated/l10n_ro_cpv_code.yaml` |
| `module.l10n_ro_edi` | depends_on | `agents/modules/generated/l10n_ro_edi.yaml` |
| `module.l10n_ro_edi_stock` | model_extended_by, required_by | `agents/modules/generated/l10n_ro_edi_stock.yaml` |
| `module.l10n_ro_edi_stock_batch` | model_extended_by | `agents/modules/generated/l10n_ro_edi_stock_batch.yaml` |
| `module.l10n_ro_efactura_synchronize` | model_extended_by, required_by | `agents/modules/generated/l10n_ro_efactura_synchronize.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_ro_efactura`](../../../agents/modules/generated/l10n_ro_efactura.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/EDI
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ro_efactura)
- Direct dependencies: [`l10n_ro_edi`](../l10n_ro_edi/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_ro_cpv_code`](../l10n_ro_cpv_code/overview.md), [`l10n_ro_edi_stock`](../l10n_ro_edi_stock/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md)
- Impact graph: [`module:l10n_ro_efactura`](../../impact-graph.json)

## Purpose

Bridge module for sending Romanian E-Factura to the SPV

## Model relationships

- `l10n_ro_edi.document` — extended by [`l10n_ro_edi_stock`](../l10n_ro_edi_stock/overview.md), [`l10n_ro_edi_stock_batch`](../l10n_ro_edi_stock_batch/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.send` — defined by [`account`](../account/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_ro_cpv_code`](../../../agents/modules/generated/l10n_ro_cpv_code.yaml) — required_by
- [`module.l10n_ro_edi`](../../../agents/modules/generated/l10n_ro_edi.yaml) — depends_on
- [`module.l10n_ro_edi_stock`](../../../agents/modules/generated/l10n_ro_edi_stock.yaml) — model_extended_by, required_by
- [`module.l10n_ro_edi_stock_batch`](../../../agents/modules/generated/l10n_ro_edi_stock_batch.yaml) — model_extended_by
- [`module.l10n_ro_efactura_synchronize`](../../../agents/modules/generated/l10n_ro_efactura_synchronize.yaml) — model_extended_by, required_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`l10n_ro_edi_stock`](../l10n_ro_edi_stock/overview.md), [`l10n_ro_edi_stock_batch`](../l10n_ro_edi_stock_batch/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
