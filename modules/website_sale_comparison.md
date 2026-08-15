---
layout: page
title: "Product Comparison (website_sale_comparison)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_sale_comparison/
nav_order: 0
---
# Product Comparison — `website_sale_comparison`

**Source:** [`agents/modules/generated/website_sale_comparison.yaml`](../../agents/modules/generated/website_sale_comparison.yaml) · **Wiki:** [`knowledge/modules/website_sale_comparison/overview.md`](../../knowledge/modules/website_sale_comparison/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_sale_comparison</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Product Comparison</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_sale_comparison</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_comparison"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Allow shoppers to compare products based on their attributes

## Direct dependencies

[`website_sale`](website_sale.md)

## Reverse dependencies (modules that depend on this)

[`website_sale_comparison_wishlist`](website_sale_comparison_wishlist.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.attribute.category</code></div><div class="role">defined by <code>website_sale_comparison</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.attribute</code></div><div class="role">extended by <code>website_sale_comparison</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>website_sale_comparison</code></div></div>
<div class="model"><div class="name"><code>product.template.attribute.line</code></div><div class="role">extended by <code>website_sale_comparison</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.website_sale` | depends_on | `agents/modules/generated/website_sale.yaml` |
| `module.website_sale_comparison_wishlist` | required_by | `agents/modules/generated/website_sale_comparison_wishlist.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_sale_comparison`](../../../agents/modules/generated/website_sale_comparison.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_comparison)
- Direct dependencies: [`website_sale`](../website_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_sale_comparison_wishlist`](../website_sale_comparison_wishlist/overview.md)
- Impact graph: [`module:website_sale_comparison`](../../impact-graph.json)

## Purpose

Allow shoppers to compare products based on their attributes

## Model relationships

- `product.attribute.category`
- Extends `product.attribute` — defined by [`product`](../product/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template.attribute.line` — defined by [`product`](../product/overview.md)

## Related SME agents

- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — depends_on
- [`module.website_sale_comparison_wishlist`](../../../agents/modules/generated/website_sale_comparison_wishlist.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
