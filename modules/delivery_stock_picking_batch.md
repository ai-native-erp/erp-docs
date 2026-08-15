---
layout: page
title: "Delivery Stock Picking Batch (delivery_stock_picking_batch)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/delivery_stock_picking_batch/
nav_order: 0
---
# Delivery Stock Picking Batch — `delivery_stock_picking_batch`

**Source:** [`agents/modules/generated/delivery_stock_picking_batch.yaml`](../../agents/modules/generated/delivery_stock_picking_batch.yaml) · **Wiki:** [`knowledge/modules/delivery_stock_picking_batch/overview.md`](../../knowledge/modules/delivery_stock_picking_batch/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>delivery_stock_picking_batch</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Delivery Stock Picking Batch</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/delivery_stock_picking_batch</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/delivery_stock_picking_batch"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Batch Transfer, Carrier

## Direct dependencies

[`stock_delivery`](stock_delivery.md), [`stock_picking_batch`](stock_picking_batch.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>delivery_stock_picking_batch</code></div></div>
<div class="model"><div class="name"><code>stock.picking.batch</code></div><div class="role">extended by <code>delivery_stock_picking_batch</code></div></div>
<div class="model"><div class="name"><code>stock.picking.type</code></div><div class="role">extended by <code>delivery_stock_picking_batch</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.stock` | extends_model_from | `agents/modules/generated/stock.yaml` |
| `module.stock_delivery` | depends_on | `agents/modules/generated/stock_delivery.yaml` |
| `module.stock_picking_batch` | depends_on, extends_model_from | `agents/modules/generated/stock_picking_batch.yaml` |

## Full wiki excerpt

- SME owner: [`module.delivery_stock_picking_batch`](../../../agents/modules/generated/delivery_stock_picking_batch.yaml)
- Domain: `inventory_purchase`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/delivery_stock_picking_batch)
- Direct dependencies: [`stock_delivery`](../stock_delivery/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:delivery_stock_picking_batch`](../../impact-graph.json)

## Purpose

Batch Transfer, Carrier

## Model relationships

- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)
- Extends `stock.picking.batch` — defined by [`stock_picking_batch`](../stock_picking_batch/overview.md)
- Extends `stock.picking.type` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — depends_on
- [`module.stock_picking_batch`](../../../agents/modules/generated/stock_picking_batch.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
