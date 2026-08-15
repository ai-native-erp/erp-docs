---
layout: page
title: "Delivery - Stock (stock_delivery)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/stock_delivery/
nav_order: 0
---
# Delivery - Stock — `stock_delivery`

**Source:** [`agents/modules/generated/stock_delivery.yaml`](../../agents/modules/generated/stock_delivery.yaml) · **Wiki:** [`knowledge/modules/stock_delivery/overview.md`](../../knowledge/modules/stock_delivery/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>stock_delivery</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Delivery - Stock</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/stock_delivery</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock_delivery"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`delivery`](delivery.md), [`sale_stock`](sale_stock.md)

## Reverse dependencies (modules that depend on this)

[`delivery_mondialrelay`](delivery_mondialrelay.md), [`delivery_stock_picking_batch`](delivery_stock_picking_batch.md), [`l10n_it_stock_ddt`](l10n_it_stock_ddt.md), [`l10n_ro_edi_stock`](l10n_ro_edi_stock.md), [`website_sale_stock`](website_sale_stock.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>choose.delivery.package</code></div><div class="role">defined by <code>stock_delivery</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>choose.delivery.carrier</code></div><div class="role">extended by <code>stock_delivery</code></div></div>
<div class="model"><div class="name"><code>delivery.carrier</code></div><div class="role">extended by <code>stock_delivery</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>stock_delivery</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>stock_delivery</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>stock_delivery</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>stock_delivery</code></div></div>
<div class="model"><div class="name"><code>stock.move.line</code></div><div class="role">extended by <code>stock_delivery</code></div></div>
<div class="model"><div class="name"><code>stock.package.type</code></div><div class="role">extended by <code>stock_delivery</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>stock_delivery</code></div></div>
<div class="model"><div class="name"><code>stock.quant.package</code></div><div class="role">extended by <code>stock_delivery</code></div></div>
<div class="model"><div class="name"><code>stock.return.picking</code></div><div class="role">extended by <code>stock_delivery</code></div></div>
<div class="model"><div class="name"><code>stock.route</code></div><div class="role">extended by <code>stock_delivery</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.delivery` | depends_on, extends_model_from | `agents/modules/generated/delivery.yaml` |
| `module.delivery_mondialrelay` | required_by | `agents/modules/generated/delivery_mondialrelay.yaml` |
| `module.delivery_stock_picking_batch` | required_by | `agents/modules/generated/delivery_stock_picking_batch.yaml` |
| `module.l10n_it_stock_ddt` | required_by | `agents/modules/generated/l10n_it_stock_ddt.yaml` |
| `module.l10n_ro_edi_stock` | required_by | `agents/modules/generated/l10n_ro_edi_stock.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml)
- Domain: `inventory_purchase`
- Category: Inventory/Delivery
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock_delivery)
- Direct dependencies: [`delivery`](../delivery/overview.md), [`sale_stock`](../sale_stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`delivery_stock_picking_batch`](../delivery_stock_picking_batch/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`l10n_ro_edi_stock`](../l10n_ro_edi_stock/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md)
- Impact graph: [`module:stock_delivery`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `choose.delivery.package`
- Extends `choose.delivery.carrier` — defined by [`delivery`](../delivery/overview.md)
- Extends `delivery.carrier` — defined by [`delivery`](../delivery/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move.line` — defined by [`stock`](../stock/overview.md)
- Extends `stock.package.type` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)
- Extends `stock.quant.package` — defined by [`stock`](../stock/overview.md)
- Extends `stock.return.picking` — defined by [`stock`](../stock/overview.md)
- Extends `stock.route` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — depends_on, extends_model_from
- [`module.delivery_mondialrelay`](../../../agents/modules/generated/delivery_mondialrelay.yaml) — required_by
- [`module.delivery_stock_picking_batch`](../../../agents/modules/generated/delivery_stock_picking_batch.yaml) — required_by
- [`module.l10n_it_stock_ddt`](../../../agents/modules/generated/l10n_it_stock_ddt.yaml) — required_by
- [`module.l10n_ro_edi_stock`](../../../agents/modules/generated/l10n_ro_edi_stock.yaml) — required_by
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — depends_on
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from
- [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml) — required_by

## Regression impact checklist

- Review 5 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`delivery`](../delivery/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
