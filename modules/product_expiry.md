---
layout: page
title: "Products Expiration Date (product_expiry)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/product_expiry/
nav_order: 0
---
# Products Expiration Date — `product_expiry`

**Source:** [`agents/modules/generated/product_expiry.yaml`](../../agents/modules/generated/product_expiry.yaml) · **Wiki:** [`knowledge/modules/product_expiry/overview.md`](../../knowledge/modules/product_expiry/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>product_expiry</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Products Expiration Date</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/product_expiry</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/product_expiry"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`stock`](stock.md)

## Reverse dependencies (modules that depend on this)

[`mrp_product_expiry`](mrp_product_expiry.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>expiry.picking.confirmation</code></div><div class="role">defined by <code>product_expiry</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>procurement.group</code></div><div class="role">extended by <code>product_expiry</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>product_expiry</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>product_expiry</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>product_expiry</code></div></div>
<div class="model"><div class="name"><code>stock.lot</code></div><div class="role">extended by <code>product_expiry</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>product_expiry</code></div></div>
<div class="model"><div class="name"><code>stock.move.line</code></div><div class="role">extended by <code>product_expiry</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>product_expiry</code></div></div>
<div class="model"><div class="name"><code>stock.quant</code></div><div class="role">extended by <code>product_expiry</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.mrp_product_expiry` | model_extended_by, required_by | `agents/modules/generated/mrp_product_expiry.yaml` |
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.stock` | depends_on, extends_model_from | `agents/modules/generated/stock.yaml` |
| `module.stock_account` | extends_model_from | `agents/modules/generated/stock_account.yaml` |
| `module.website_sale` | extends_model_from | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.product_expiry`](../../../agents/modules/generated/product_expiry.yaml)
- Domain: `sales_crm`
- Category: Inventory/Inventory
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/product_expiry)
- Direct dependencies: [`stock`](../stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`mrp_product_expiry`](../mrp_product_expiry/overview.md)
- Impact graph: [`module:product_expiry`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `expiry.picking.confirmation` — extended by [`mrp_product_expiry`](../mrp_product_expiry/overview.md)
- Extends `procurement.group` — defined by [`stock`](../stock/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `stock.lot` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move.line` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)
- Extends `stock.quant` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.mrp_product_expiry`](../../../agents/modules/generated/mrp_product_expiry.yaml) — model_extended_by, required_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — depends_on, extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`mrp_product_expiry`](../mrp_product_expiry/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
