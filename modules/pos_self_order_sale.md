---
layout: page
title: "POS Self Order Sale (pos_self_order_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_self_order_sale/
nav_order: 0
---
# POS Self Order Sale — `pos_self_order_sale`

**Source:** [`agents/modules/generated/pos_self_order_sale.yaml`](../../agents/modules/generated/pos_self_order_sale.yaml) · **Wiki:** [`knowledge/modules/pos_self_order_sale/overview.md`](../../knowledge/modules/pos_self_order_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_self_order_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">POS Self Order Sale</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_self_order_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_self_order_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`pos_sale`](pos_sale.md), [`pos_self_order`](pos_self_order.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>pos_self_order_sale</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>pos_self_order_sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.pos_sale` | depends_on | `agents/modules/generated/pos_sale.yaml` |
| `module.pos_self_order` | depends_on | `agents/modules/generated/pos_self_order.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_self_order_sale`](../../../agents/modules/generated/pos_self_order_sale.yaml)
- Domain: `point_of_sale`
- Category: Sales/Point Of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_self_order_sale)
- Direct dependencies: [`pos_sale`](../pos_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:pos_self_order_sale`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml) — depends_on
- [`module.pos_self_order`](../../../agents/modules/generated/pos_self_order.yaml) — depends_on
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
