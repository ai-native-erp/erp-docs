---
layout: page
title: "Purchase Requisition Stock (purchase_requisition_stock)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/purchase_requisition_stock/
nav_order: 0
---
# Purchase Requisition Stock — `purchase_requisition_stock`

**Source:** [`agents/modules/generated/purchase_requisition_stock.yaml`](../../agents/modules/generated/purchase_requisition_stock.yaml) · **Wiki:** [`knowledge/modules/purchase_requisition_stock/overview.md`](../../knowledge/modules/purchase_requisition_stock/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>purchase_requisition_stock</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Purchase Requisition Stock</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/purchase_requisition_stock</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/purchase_requisition_stock"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`purchase_requisition`](purchase_requisition.md), [`purchase_stock`](purchase_stock.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>purchase.order</code></div><div class="role">extended by <code>purchase_requisition_stock</code></div></div>
<div class="model"><div class="name"><code>purchase.order.line</code></div><div class="role">extended by <code>purchase_requisition_stock</code></div></div>
<div class="model"><div class="name"><code>purchase.requisition</code></div><div class="role">extended by <code>purchase_requisition_stock</code></div></div>
<div class="model"><div class="name"><code>purchase.requisition.create.alternative</code></div><div class="role">extended by <code>purchase_requisition_stock</code></div></div>
<div class="model"><div class="name"><code>purchase.requisition.line</code></div><div class="role">extended by <code>purchase_requisition_stock</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>purchase_requisition_stock</code></div></div>
<div class="model"><div class="name"><code>stock.rule</code></div><div class="role">extended by <code>purchase_requisition_stock</code></div></div>
<div class="model"><div class="name"><code>stock.warehouse.orderpoint</code></div><div class="role">extended by <code>purchase_requisition_stock</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_requisition` | depends_on, extends_model_from | `agents/modules/generated/purchase_requisition.yaml` |
| `module.purchase_stock` | depends_on | `agents/modules/generated/purchase_stock.yaml` |
| `module.stock` | extends_model_from | `agents/modules/generated/stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.purchase_requisition_stock`](../../../agents/modules/generated/purchase_requisition_stock.yaml)
- Domain: `inventory_purchase`
- Category: Inventory/Purchase
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/purchase_requisition_stock)
- Direct dependencies: [`purchase_requisition`](../purchase_requisition/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:purchase_requisition_stock`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `purchase.order` — defined by [`purchase`](../purchase/overview.md)
- Extends `purchase.order.line` — defined by [`purchase`](../purchase/overview.md)
- Extends `purchase.requisition` — defined by [`purchase_requisition`](../purchase_requisition/overview.md)
- Extends `purchase.requisition.create.alternative` — defined by [`purchase_requisition`](../purchase_requisition/overview.md)
- Extends `purchase.requisition.line` — defined by [`purchase_requisition`](../purchase_requisition/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.rule` — defined by [`stock`](../stock/overview.md)
- Extends `stock.warehouse.orderpoint` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_requisition`](../../../agents/modules/generated/purchase_requisition.yaml) — depends_on, extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — depends_on
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`purchase`](../purchase/overview.md), [`purchase_requisition`](../purchase_requisition/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
