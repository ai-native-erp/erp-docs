---
layout: page
title: "Product Availability (website_sale_stock)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_sale_stock/
nav_order: 0
---
# Product Availability — `website_sale_stock`

**Source:** [`agents/modules/generated/website_sale_stock.yaml`](../../agents/modules/generated/website_sale_stock.yaml) · **Wiki:** [`knowledge/modules/website_sale_stock/overview.md`](../../knowledge/modules/website_sale_stock/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_sale_stock</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Product Availability</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_sale_stock</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_stock"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage product inventory & availability

## Direct dependencies

[`sale_stock`](sale_stock.md), [`stock_delivery`](stock_delivery.md), [`website_sale`](website_sale.md)

## Reverse dependencies (modules that depend on this)

[`website_sale_mrp`](website_sale_mrp.md), [`website_sale_stock_wishlist`](website_sale_stock_wishlist.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>website_sale_stock</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>website_sale_stock</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website_sale_stock</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>website_sale_stock</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>website_sale_stock</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>website_sale_stock</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_sale_stock</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_stock` | depends_on | `agents/modules/generated/sale_stock.yaml` |
| `module.stock` | extends_model_from | `agents/modules/generated/stock.yaml` |
| `module.stock_account` | extends_model_from | `agents/modules/generated/stock_account.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_stock)
- Direct dependencies: [`sale_stock`](../sale_stock/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`website_sale`](../website_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_sale_mrp`](../website_sale_mrp/overview.md), [`website_sale_stock_wishlist`](../website_sale_stock_wishlist/overview.md)
- Impact graph: [`module:website_sale_stock`](../../impact-graph.json)

## Purpose

Manage product inventory & availability

## Model relationships

- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — depends_on
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — depends_on, extends_model_from
- [`module.website_sale_mrp`](../../../agents/modules/generated/website_sale_mrp.yaml) — required_by
- [`module.website_sale_stock_wishlist`](../../../agents/modules/generated/website_sale_stock_wishlist.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website`](../website/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
