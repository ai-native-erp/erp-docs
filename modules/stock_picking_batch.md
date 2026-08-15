---
layout: page
title: "Warehouse Management: Batch Transfer (stock_picking_batch)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/stock_picking_batch/
nav_order: 0
---
# Warehouse Management: Batch Transfer — `stock_picking_batch`

**Source:** [`agents/modules/generated/stock_picking_batch.yaml`](../../agents/modules/generated/stock_picking_batch.yaml) · **Wiki:** [`knowledge/modules/stock_picking_batch/overview.md`](../../knowledge/modules/stock_picking_batch/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>stock_picking_batch</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Warehouse Management: Batch Transfer</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/stock_picking_batch</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock_picking_batch"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`stock`](stock.md)

## Reverse dependencies (modules that depend on this)

[`delivery_stock_picking_batch`](delivery_stock_picking_batch.md), [`l10n_ro_edi_stock_batch`](l10n_ro_edi_stock_batch.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>stock.add.to.wave</code></div><div class="role">defined by <code>stock_picking_batch</code></div></div>
<div class="model"><div class="name"><code>stock.picking.batch</code></div><div class="role">defined by <code>stock_picking_batch</code></div></div>
<div class="model"><div class="name"><code>stock.picking.to.batch</code></div><div class="role">defined by <code>stock_picking_batch</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>stock_picking_batch</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>stock_picking_batch</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>stock_picking_batch</code></div></div>
<div class="model"><div class="name"><code>stock.move.line</code></div><div class="role">extended by <code>stock_picking_batch</code></div></div>
<div class="model"><div class="name"><code>stock.package.destination</code></div><div class="role">extended by <code>stock_picking_batch</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>stock_picking_batch</code></div></div>
<div class="model"><div class="name"><code>stock.picking.type</code></div><div class="role">extended by <code>stock_picking_batch</code></div></div>
<div class="model"><div class="name"><code>stock.warehouse</code></div><div class="role">extended by <code>stock_picking_batch</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.delivery_stock_picking_batch` | model_extended_by, required_by | `agents/modules/generated/delivery_stock_picking_batch.yaml` |
| `module.l10n_ro_edi_stock_batch` | required_by | `agents/modules/generated/l10n_ro_edi_stock_batch.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.stock` | depends_on, extends_model_from | `agents/modules/generated/stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.stock_picking_batch`](../../../agents/modules/generated/stock_picking_batch.yaml)
- Domain: `inventory_purchase`
- Category: Inventory/Inventory
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock_picking_batch)
- Direct dependencies: [`stock`](../stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`delivery_stock_picking_batch`](../delivery_stock_picking_batch/overview.md), [`l10n_ro_edi_stock_batch`](../l10n_ro_edi_stock_batch/overview.md)
- Impact graph: [`module:stock_picking_batch`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `stock.add.to.wave`
- `stock.picking.batch` — extended by [`delivery_stock_picking_batch`](../delivery_stock_picking_batch/overview.md)
- `stock.picking.to.batch`
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move.line` — defined by [`stock`](../stock/overview.md)
- Extends `stock.package.destination` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)
- Extends `stock.picking.type` — defined by [`stock`](../stock/overview.md)
- Extends `stock.warehouse` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.delivery_stock_picking_batch`](../../../agents/modules/generated/delivery_stock_picking_batch.yaml) — model_extended_by, required_by
- [`module.l10n_ro_edi_stock_batch`](../../../agents/modules/generated/l10n_ro_edi_stock_batch.yaml) — required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`delivery_stock_picking_batch`](../delivery_stock_picking_batch/overview.md).
- Review model owners used by this module: [`mail`](../mail/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
