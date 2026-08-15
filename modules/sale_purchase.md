---
layout: page
title: "Sale Purchase (sale_purchase)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_purchase/
nav_order: 0
---
# Sale Purchase — `sale_purchase`

**Source:** [`agents/modules/generated/sale_purchase.yaml`](../../agents/modules/generated/sale_purchase.yaml) · **Wiki:** [`knowledge/modules/sale_purchase/overview.md`](../../knowledge/modules/sale_purchase/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_purchase</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sale Purchase</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_purchase</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_purchase"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Sale based on service outsourcing.

## Direct dependencies

[`purchase`](purchase.md), [`sale`](sale.md)

## Reverse dependencies (modules that depend on this)

[`purchase_requisition_sale`](purchase_requisition_sale.md), [`sale_purchase_stock`](sale_purchase_stock.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>sale_purchase</code></div></div>
<div class="model"><div class="name"><code>purchase.order</code></div><div class="role">extended by <code>sale_purchase</code></div></div>
<div class="model"><div class="name"><code>purchase.order.line</code></div><div class="role">extended by <code>sale_purchase</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_purchase</code></div></div>
<div class="model"><div class="name"><code>sale.order.cancel</code></div><div class="role">extended by <code>sale_purchase</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale_purchase</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | depends_on, extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_requisition_sale` | required_by | `agents/modules/generated/purchase_requisition_sale.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale` | depends_on, extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_purchase_stock` | required_by | `agents/modules/generated/sale_purchase_stock.yaml` |
| `module.stock_account` | extends_model_from | `agents/modules/generated/stock_account.yaml` |
| `module.website_sale` | extends_model_from | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_purchase`](../../../agents/modules/generated/sale_purchase.yaml)
- Domain: `sales_crm`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_purchase)
- Direct dependencies: [`purchase`](../purchase/overview.md), [`sale`](../sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`purchase_requisition_sale`](../purchase_requisition_sale/overview.md), [`sale_purchase_stock`](../sale_purchase_stock/overview.md)
- Impact graph: [`module:sale_purchase`](../../impact-graph.json)

## Purpose

Sale based on service outsourcing.

## Model relationships

- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `purchase.order` — defined by [`purchase`](../purchase/overview.md)
- Extends `purchase.order.line` — defined by [`purchase`](../purchase/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.cancel` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — depends_on, extends_model_from
- [`module.purchase_requisition_sale`](../../../agents/modules/generated/purchase_requisition_sale.yaml) — required_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — depends_on, extends_model_from
- [`module.sale_purchase_stock`](../../../agents/modules/generated/sale_purchase_stock.yaml) — required_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
