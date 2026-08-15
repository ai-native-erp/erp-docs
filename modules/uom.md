---
layout: page
title: "Units of measure (uom)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/uom/
nav_order: 0
---
# Units of measure — `uom`

**Source:** [`agents/modules/generated/uom.yaml`](../../agents/modules/generated/uom.yaml) · **Wiki:** [`knowledge/modules/uom/overview.md`](../../knowledge/modules/uom/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>uom</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Units of measure</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/uom</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/uom"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md)

## Reverse dependencies (modules that depend on this)

[`analytic`](analytic.md), [`barcodes_gs1_nomenclature`](barcodes_gs1_nomenclature.md), [`hr_timesheet`](hr_timesheet.md), [`l10n_cl`](l10n_cl.md), [`product`](product.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>uom.category</code></div><div class="role">defined by <code>uom</code></div></div>
<div class="model"><div class="name"><code>uom.uom</code></div><div class="role">defined by <code>uom</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | model_extended_by | `agents/modules/generated/account.yaml` |
| `module.analytic` | required_by | `agents/modules/generated/analytic.yaml` |
| `module.barcodes_gs1_nomenclature` | required_by | `agents/modules/generated/barcodes_gs1_nomenclature.yaml` |
| `module.base` | depends_on | `agents/modules/generated/base.yaml` |
| `module.hr_timesheet` | model_extended_by, required_by | `agents/modules/generated/hr_timesheet.yaml` |
| `module.l10n_ar` | model_extended_by | `agents/modules/generated/l10n_ar.yaml` |
| `module.l10n_cl` | model_extended_by, required_by | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_eg_edi_eta` | model_extended_by | `agents/modules/generated/l10n_eg_edi_eta.yaml` |
| `module.l10n_es_edi_facturae` | model_extended_by | `agents/modules/generated/l10n_es_edi_facturae.yaml` |
| `module.l10n_hu_edi` | model_extended_by | `agents/modules/generated/l10n_hu_edi.yaml` |

## Full wiki excerpt

- SME owner: [`module.uom`](../../../agents/modules/generated/uom.yaml)
- Domain: `platform_core`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/uom)
- Direct dependencies: [`base`](../base/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`analytic`](../analytic/overview.md), [`barcodes_gs1_nomenclature`](../barcodes_gs1_nomenclature/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`product`](../product/overview.md)
- Impact graph: [`module:uom`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `uom.category` — extended by [`point_of_sale`](../point_of_sale/overview.md)
- `uom.uom` — extended by [`account`](../account/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`product`](../product/overview.md), [`stock`](../stock/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — model_extended_by
- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — required_by
- [`module.barcodes_gs1_nomenclature`](../../../agents/modules/generated/barcodes_gs1_nomenclature.yaml) — required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on
- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — model_extended_by, required_by
- [`module.l10n_ar`](../../../agents/modules/generated/l10n_ar.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — model_extended_by, required_by
- [`module.l10n_eg_edi_eta`](../../../agents/modules/generated/l10n_eg_edi_eta.yaml) — model_extended_by
- [`module.l10n_es_edi_facturae`](../../../agents/modules/generated/l10n_es_edi_facturae.yaml) — model_extended_by
- [`module.l10n_hu_edi`](../../../agents/modules/generated/l10n_hu_edi.yaml) — model_extended_by
- [`module.l10n_id_efaktur_coretax`](../../../agents/modules/generated/l10n_id_efaktur_coretax.yaml) — model_extended_by
- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — model_extended_by
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — model_extended_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — model_extended_by, required_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — model_extended_by

## Regression impact checklist

- Review 5 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`product`](../product/overview.md), [`stock`](../stock/overview.md).
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
