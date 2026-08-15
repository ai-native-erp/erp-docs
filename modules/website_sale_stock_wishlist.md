---
layout: page
title: "Product Availability Notifications (website_sale_stock_wishlist)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_sale_stock_wishlist/
nav_order: 0
---
# Product Availability Notifications — `website_sale_stock_wishlist`

**Source:** [`agents/modules/generated/website_sale_stock_wishlist.yaml`](../../agents/modules/generated/website_sale_stock_wishlist.yaml) · **Wiki:** [`knowledge/modules/website_sale_stock_wishlist/overview.md`](../../knowledge/modules/website_sale_stock_wishlist/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_sale_stock_wishlist</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Product Availability Notifications</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_sale_stock_wishlist</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_stock_wishlist"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Notify the user when a product is back in stock

## Direct dependencies

[`website_sale_stock`](website_sale_stock.md), [`website_sale_wishlist`](website_sale_wishlist.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>website_sale_stock_wishlist</code></div></div>
<div class="model"><div class="name"><code>product.wishlist</code></div><div class="role">extended by <code>website_sale_stock_wishlist</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.stock_account` | extends_model_from | `agents/modules/generated/stock_account.yaml` |
| `module.website_sale` | extends_model_from | `agents/modules/generated/website_sale.yaml` |
| `module.website_sale_stock` | depends_on | `agents/modules/generated/website_sale_stock.yaml` |
| `module.website_sale_wishlist` | depends_on, extends_model_from | `agents/modules/generated/website_sale_wishlist.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_sale_stock_wishlist`](../../../agents/modules/generated/website_sale_stock_wishlist.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_stock_wishlist)
- Direct dependencies: [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_sale_stock_wishlist`](../../impact-graph.json)

## Purpose

Notify the user when a product is back in stock

## Model relationships

- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `product.wishlist` — defined by [`website_sale_wishlist`](../website_sale_wishlist/overview.md)

## Related SME agents

- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from
- [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml) — depends_on
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
