---
layout: page
title: "Indian - E-waybill (l10n_in_edi_ewaybill)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_in_edi_ewaybill/
nav_order: 0
---
# Indian - E-waybill — `l10n_in_edi_ewaybill`

**Source:** [`agents/modules/generated/l10n_in_edi_ewaybill.yaml`](../../agents/modules/generated/l10n_in_edi_ewaybill.yaml) · **Wiki:** [`knowledge/modules/l10n_in_edi_ewaybill/overview.md`](../../knowledge/modules/l10n_in_edi_ewaybill/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_in_edi_ewaybill</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Indian - E-waybill</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_in_edi_ewaybill</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_in_edi_ewaybill"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_in_edi`](l10n_in_edi.md)

## Reverse dependencies (modules that depend on this)

[`l10n_in_ewaybill_port`](l10n_in_ewaybill_port.md), [`l10n_in_ewaybill_stock`](l10n_in_ewaybill_stock.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>l10n.in.ewaybill.type</code></div><div class="role">defined by <code>l10n_in_edi_ewaybill</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>l10n_in_edi_ewaybill</code></div></div>
<div class="model"><div class="name"><code>account.edi.format</code></div><div class="role">extended by <code>l10n_in_edi_ewaybill</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_in_edi_ewaybill</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>l10n_in_edi_ewaybill</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>l10n_in_edi_ewaybill</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_edi` | extends_model_from | `agents/modules/generated/account_edi.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_in_edi` | depends_on | `agents/modules/generated/l10n_in_edi.yaml` |
| `module.l10n_in_ewaybill_port` | required_by | `agents/modules/generated/l10n_in_ewaybill_port.yaml` |
| `module.l10n_in_ewaybill_stock` | required_by | `agents/modules/generated/l10n_in_ewaybill_stock.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_in_edi_ewaybill`](../../../agents/modules/generated/l10n_in_edi_ewaybill.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/EDI
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_in_edi_ewaybill)
- Direct dependencies: [`l10n_in_edi`](../l10n_in_edi/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_in_ewaybill_port`](../l10n_in_ewaybill_port/overview.md), [`l10n_in_ewaybill_stock`](../l10n_in_ewaybill_stock/overview.md)
- Impact graph: [`module:l10n_in_edi_ewaybill`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `l10n.in.ewaybill.type`
- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.edi.format` — defined by [`account_edi`](../account_edi/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_edi`](../../../agents/modules/generated/account_edi.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_in_edi`](../../../agents/modules/generated/l10n_in_edi.yaml) — depends_on
- [`module.l10n_in_ewaybill_port`](../../../agents/modules/generated/l10n_in_ewaybill_port.yaml) — required_by
- [`module.l10n_in_ewaybill_stock`](../../../agents/modules/generated/l10n_in_ewaybill_stock.yaml) — required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`account_edi`](../account_edi/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
