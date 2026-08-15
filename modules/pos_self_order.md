---
layout: page
title: "POS Self Order (pos_self_order)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_self_order/
nav_order: 0
---
# POS Self Order — `pos_self_order`

**Source:** [`agents/modules/generated/pos_self_order.yaml`](../../agents/modules/generated/pos_self_order.yaml) · **Wiki:** [`knowledge/modules/pos_self_order/overview.md`](../../knowledge/modules/pos_self_order/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_self_order</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">POS Self Order</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_self_order</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_self_order"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Addon for the POS App that allows customers to view the menu on their smartphone.

## Direct dependencies

[`http_routing`](http_routing.md), [`pos_restaurant`](pos_restaurant.md)

## Reverse dependencies (modules that depend on this)

[`pos_online_payment_self_order`](pos_online_payment_self_order.md), [`pos_self_order_adyen`](pos_self_order_adyen.md), [`pos_self_order_epson_printer`](pos_self_order_epson_printer.md), [`pos_self_order_sale`](pos_self_order_sale.md), [`pos_self_order_stripe`](pos_self_order_stripe.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos_self_order.custom_link</code></div><div class="role">defined by <code>pos_self_order</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>pos_self_order</code></div></div>
<div class="model"><div class="name"><code>pos.config</code></div><div class="role">extended by <code>pos_self_order</code></div></div>
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">extended by <code>pos_self_order</code></div></div>
<div class="model"><div class="name"><code>pos.order.line</code></div><div class="role">extended by <code>pos_self_order</code></div></div>
<div class="model"><div class="name"><code>pos.payment.method</code></div><div class="role">extended by <code>pos_self_order</code></div></div>
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>pos_self_order</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>pos_self_order</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>pos_self_order</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>pos_self_order</code></div></div>
<div class="model"><div class="name"><code>restaurant.table</code></div><div class="role">extended by <code>pos_self_order</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.http_routing` | depends_on | `agents/modules/generated/http_routing.yaml` |
| `module.l10n_ch_pos` | extends_model_from | `agents/modules/generated/l10n_ch_pos.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.point_of_sale` | extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.pos_online_payment_self_order` | required_by | `agents/modules/generated/pos_online_payment_self_order.yaml` |
| `module.pos_restaurant` | depends_on, extends_model_from | `agents/modules/generated/pos_restaurant.yaml` |
| `module.pos_self_order_adyen` | required_by | `agents/modules/generated/pos_self_order_adyen.yaml` |
| `module.pos_self_order_epson_printer` | required_by | `agents/modules/generated/pos_self_order_epson_printer.yaml` |
| `module.pos_self_order_sale` | required_by | `agents/modules/generated/pos_self_order_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_self_order`](../../../agents/modules/generated/pos_self_order.yaml)
- Domain: `point_of_sale`
- Category: Sales/Point Of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_self_order)
- Direct dependencies: [`http_routing`](../http_routing/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`pos_online_payment_self_order`](../pos_online_payment_self_order/overview.md), [`pos_self_order_adyen`](../pos_self_order_adyen/overview.md), [`pos_self_order_epson_printer`](../pos_self_order_epson_printer/overview.md), [`pos_self_order_sale`](../pos_self_order_sale/overview.md), [`pos_self_order_stripe`](../pos_self_order_stripe/overview.md)
- Impact graph: [`module:pos_self_order`](../../impact-graph.json)

## Purpose

Addon for the POS App that allows customers to view the menu on their smartphone.

## Model relationships

- `pos_self_order.custom_link`
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `pos.config` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.order` — defined by [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.order.line` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.payment.method` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `restaurant.table` — defined by [`pos_restaurant`](../pos_restaurant/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.http_routing`](../../../agents/modules/generated/http_routing.yaml) — depends_on
- [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — extends_model_from
- [`module.pos_online_payment_self_order`](../../../agents/modules/generated/pos_online_payment_self_order.yaml) — required_by
- [`module.pos_restaurant`](../../../agents/modules/generated/pos_restaurant.yaml) — depends_on, extends_model_from
- [`module.pos_self_order_adyen`](../../../agents/modules/generated/pos_self_order_adyen.yaml) — required_by
- [`module.pos_self_order_epson_printer`](../../../agents/modules/generated/pos_self_order_epson_printer.yaml) — required_by
- [`module.pos_self_order_sale`](../../../agents/modules/generated/pos_self_order_sale.yaml) — required_by
- [`module.pos_self_order_stripe`](../../../agents/modules/generated/pos_self_order_stripe.yaml) — required_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 5 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`mrp_account`](../mrp_account/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
