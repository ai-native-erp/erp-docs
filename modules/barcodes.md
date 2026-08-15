---
layout: page
title: "Barcode (barcodes)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/barcodes/
nav_order: 0
---
# Barcode — `barcodes`

**Source:** [`agents/modules/generated/barcodes.yaml`](../../agents/modules/generated/barcodes.yaml) · **Wiki:** [`knowledge/modules/barcodes/overview.md`](../../knowledge/modules/barcodes/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>barcodes</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Barcode</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/barcodes</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/barcodes"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Scan and Parse Barcodes

## Direct dependencies

[`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`barcodes_gs1_nomenclature`](barcodes_gs1_nomenclature.md), [`event`](event.md), [`hr_attendance`](hr_attendance.md), [`point_of_sale`](point_of_sale.md), [`pos_mercury`](pos_mercury.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>barcode.nomenclature</code></div><div class="role">defined by <code>barcodes</code></div></div>
<div class="model"><div class="name"><code>barcode.rule</code></div><div class="role">defined by <code>barcodes</code></div></div>
<div class="model"><div class="name"><code>barcodes.barcode_events_mixin</code></div><div class="role">defined by <code>barcodes</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>barcodes</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>barcodes</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.barcodes_gs1_nomenclature` | model_extended_by, required_by | `agents/modules/generated/barcodes_gs1_nomenclature.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.event` | required_by | `agents/modules/generated/event.yaml` |
| `module.hr_attendance` | required_by | `agents/modules/generated/hr_attendance.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |
| `module.point_of_sale` | model_extended_by, required_by | `agents/modules/generated/point_of_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.barcodes`](../../../agents/modules/generated/barcodes.yaml)
- Domain: `inventory_purchase`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/barcodes)
- Direct dependencies: [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`barcodes_gs1_nomenclature`](../barcodes_gs1_nomenclature/overview.md), [`event`](../event/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_mercury`](../pos_mercury/overview.md)
- Impact graph: [`module:barcodes`](../../impact-graph.json)

## Purpose

Scan and Parse Barcodes

## Model relationships

- `barcode.nomenclature` — extended by [`barcodes_gs1_nomenclature`](../barcodes_gs1_nomenclature/overview.md)
- `barcode.rule` — extended by [`barcodes_gs1_nomenclature`](../barcodes_gs1_nomenclature/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_mercury`](../pos_mercury/overview.md), [`stock`](../stock/overview.md)
- `barcodes.barcode_events_mixin`
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.barcodes_gs1_nomenclature`](../../../agents/modules/generated/barcodes_gs1_nomenclature.yaml) — model_extended_by, required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.event`](../../../agents/modules/generated/event.yaml) — required_by
- [`module.hr_attendance`](../../../agents/modules/generated/hr_attendance.yaml) — required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by, required_by
- [`module.pos_loyalty`](../../../agents/modules/generated/pos_loyalty.yaml) — model_extended_by
- [`module.pos_mercury`](../../../agents/modules/generated/pos_mercury.yaml) — model_extended_by, required_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — model_extended_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 5 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`barcodes_gs1_nomenclature`](../barcodes_gs1_nomenclature/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_mercury`](../pos_mercury/overview.md), [`stock`](../stock/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
