---
layout: page
title: "Romania - E-Transport Batch Pickings (l10n_ro_edi_stock_batch)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_ro_edi_stock_batch/
nav_order: 0
---
# Romania - E-Transport Batch Pickings — `l10n_ro_edi_stock_batch`

**Source:** [`agents/modules/generated/l10n_ro_edi_stock_batch.yaml`](../../agents/modules/generated/l10n_ro_edi_stock_batch.yaml) · **Wiki:** [`knowledge/modules/l10n_ro_edi_stock_batch/overview.md`](../../knowledge/modules/l10n_ro_edi_stock_batch/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_ro_edi_stock_batch</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Romania - E-Transport Batch Pickings</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_ro_edi_stock_batch</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ro_edi_stock_batch"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_ro_edi_stock`](l10n_ro_edi_stock.md), [`stock_picking_batch`](stock_picking_batch.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>l10n_ro_edi.document</code></div><div class="role">extended by <code>l10n_ro_edi_stock_batch</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>l10n_ro_edi_stock_batch</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_ro_edi_stock` | depends_on | `agents/modules/generated/l10n_ro_edi_stock.yaml` |
| `module.l10n_ro_efactura` | extends_model_from | `agents/modules/generated/l10n_ro_efactura.yaml` |
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.stock` | extends_model_from | `agents/modules/generated/stock.yaml` |
| `module.stock_picking_batch` | depends_on | `agents/modules/generated/stock_picking_batch.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_ro_edi_stock_batch`](../../../agents/modules/generated/l10n_ro_edi_stock_batch.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/EDI
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ro_edi_stock_batch)
- Direct dependencies: [`l10n_ro_edi_stock`](../l10n_ro_edi_stock/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_ro_edi_stock_batch`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `l10n_ro_edi.document` — defined by [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)

## Related SME agents

- [`module.l10n_ro_edi_stock`](../../../agents/modules/generated/l10n_ro_edi_stock.yaml) — depends_on
- [`module.l10n_ro_efactura`](../../../agents/modules/generated/l10n_ro_efactura.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from
- [`module.stock_picking_batch`](../../../agents/modules/generated/stock_picking_batch.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
