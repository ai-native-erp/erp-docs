---
layout: page
title: "Product Matrix (product_matrix)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/product_matrix/
nav_order: 0
---
# Product Matrix — `product_matrix`

**Source:** [`agents/modules/generated/product_matrix.yaml`](../../agents/modules/generated/product_matrix.yaml) · **Wiki:** [`knowledge/modules/product_matrix/overview.md`](../../knowledge/modules/product_matrix/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>product_matrix</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Product Matrix</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/product_matrix</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/product_matrix"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Technical module: Matrix Implementation

## Direct dependencies

[`account`](account.md)

## Reverse dependencies (modules that depend on this)

[`purchase_product_matrix`](purchase_product_matrix.md), [`sale_product_matrix`](sale_product_matrix.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>product_matrix</code></div></div>
<div class="model"><div class="name"><code>product.template.attribute.value</code></div><div class="role">extended by <code>product_matrix</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on | `agents/modules/generated/account.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_product_matrix` | required_by | `agents/modules/generated/purchase_product_matrix.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale_product_matrix` | required_by | `agents/modules/generated/sale_product_matrix.yaml` |
| `module.stock_account` | extends_model_from | `agents/modules/generated/stock_account.yaml` |
| `module.website_sale` | extends_model_from | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.product_matrix`](../../../agents/modules/generated/product_matrix.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/product_matrix)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`purchase_product_matrix`](../purchase_product_matrix/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md)
- Impact graph: [`module:product_matrix`](../../impact-graph.json)

## Purpose

Technical module: Matrix Implementation

## Model relationships

- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `product.template.attribute.value` — defined by [`product`](../product/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_product_matrix`](../../../agents/modules/generated/purchase_product_matrix.yaml) — required_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale_product_matrix`](../../../agents/modules/generated/sale_product_matrix.yaml) — required_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
