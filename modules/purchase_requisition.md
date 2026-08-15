---
layout: page
title: "Purchase Agreements (purchase_requisition)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/purchase_requisition/
nav_order: 0
---
# Purchase Agreements — `purchase_requisition`

**Source:** [`agents/modules/generated/purchase_requisition.yaml`](../../agents/modules/generated/purchase_requisition.yaml) · **Wiki:** [`knowledge/modules/purchase_requisition/overview.md`](../../knowledge/modules/purchase_requisition/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>purchase_requisition</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Purchase Agreements</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/purchase_requisition</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/purchase_requisition"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`purchase`](purchase.md)

## Reverse dependencies (modules that depend on this)

[`purchase_requisition_sale`](purchase_requisition_sale.md), [`purchase_requisition_stock`](purchase_requisition_stock.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>purchase.order.group</code></div><div class="role">defined by <code>purchase_requisition</code></div></div>
<div class="model"><div class="name"><code>purchase.requisition</code></div><div class="role">defined by <code>purchase_requisition</code></div></div>
<div class="model"><div class="name"><code>purchase.requisition.alternative.warning</code></div><div class="role">defined by <code>purchase_requisition</code></div></div>
<div class="model"><div class="name"><code>purchase.requisition.create.alternative</code></div><div class="role">defined by <code>purchase_requisition</code></div></div>
<div class="model"><div class="name"><code>purchase.requisition.line</code></div><div class="role">defined by <code>purchase_requisition</code></div></div>
<div class="model"><div class="name"><code>purchase.requisition.type</code></div><div class="role">defined by <code>purchase_requisition</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>analytic.mixin</code></div><div class="role">extended by <code>purchase_requisition</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>purchase_requisition</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>purchase_requisition</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>purchase_requisition</code></div></div>
<div class="model"><div class="name"><code>product.supplierinfo</code></div><div class="role">extended by <code>purchase_requisition</code></div></div>
<div class="model"><div class="name"><code>purchase.order</code></div><div class="role">extended by <code>purchase_requisition</code></div></div>
<div class="model"><div class="name"><code>purchase.order.line</code></div><div class="role">extended by <code>purchase_requisition</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.analytic` | extends_model_from | `agents/modules/generated/analytic.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | depends_on, extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_requisition_sale` | model_extended_by, required_by | `agents/modules/generated/purchase_requisition_sale.yaml` |
| `module.purchase_requisition_stock` | model_extended_by, required_by | `agents/modules/generated/purchase_requisition_stock.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.purchase_requisition`](../../../agents/modules/generated/purchase_requisition.yaml)
- Domain: `inventory_purchase`
- Category: Inventory/Purchase
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/purchase_requisition)
- Direct dependencies: [`purchase`](../purchase/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`purchase_requisition_sale`](../purchase_requisition_sale/overview.md), [`purchase_requisition_stock`](../purchase_requisition_stock/overview.md)
- Impact graph: [`module:purchase_requisition`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `purchase.order.group`
- `purchase.requisition` — extended by [`purchase_requisition_stock`](../purchase_requisition_stock/overview.md)
- `purchase.requisition.alternative.warning`
- `purchase.requisition.create.alternative` — extended by [`purchase_requisition_sale`](../purchase_requisition_sale/overview.md), [`purchase_requisition_stock`](../purchase_requisition_stock/overview.md)
- `purchase.requisition.line` — extended by [`purchase_requisition_stock`](../purchase_requisition_stock/overview.md)
- `purchase.requisition.type`
- Extends `analytic.mixin` — defined by [`analytic`](../analytic/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.supplierinfo` — defined by [`product`](../product/overview.md)
- Extends `purchase.order` — defined by [`purchase`](../purchase/overview.md)
- Extends `purchase.order.line` — defined by [`purchase`](../purchase/overview.md)

## Related SME agents

- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — depends_on, extends_model_from
- [`module.purchase_requisition_sale`](../../../agents/modules/generated/purchase_requisition_sale.yaml) — model_extended_by, required_by
- [`module.purchase_requisition_stock`](../../../agents/modules/generated/purchase_requisition_stock.yaml) — model_extended_by, required_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`purchase_requisition_sale`](../purchase_requisition_sale/overview.md), [`purchase_requisition_stock`](../purchase_requisition_stock/overview.md).
- Review model owners used by this module: [`analytic`](../analytic/overview.md), [`mail`](../mail/overview.md), [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
