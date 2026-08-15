---
layout: page
title: "POS - Sale Product Configurator (pos_sale_product_configurator)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_sale_product_configurator/
nav_order: 0
---
# POS - Sale Product Configurator — `pos_sale_product_configurator`

**Source:** [`agents/modules/generated/pos_sale_product_configurator.yaml`](../../agents/modules/generated/pos_sale_product_configurator.yaml) · **Wiki:** [`knowledge/modules/pos_sale_product_configurator/overview.md`](../../knowledge/modules/pos_sale_product_configurator/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_sale_product_configurator</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">POS - Sale Product Configurator</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_sale_product_configurator</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_sale_product_configurator"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Link module between point_of_sale and sale_product_configurator

## Direct dependencies

[`point_of_sale`](point_of_sale.md), [`sale_product_configurator`](sale_product_configurator.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>pos_sale_product_configurator</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>pos_sale_product_configurator</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.point_of_sale` | depends_on, extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale_product_configurator` | depends_on | `agents/modules/generated/sale_product_configurator.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_sale_product_configurator`](../../../agents/modules/generated/pos_sale_product_configurator.yaml)
- Domain: `point_of_sale`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_sale_product_configurator)
- Direct dependencies: [`point_of_sale`](../point_of_sale/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:pos_sale_product_configurator`](../../impact-graph.json)

## Purpose

Link module between point_of_sale and sale_product_configurator

## Model relationships

- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)

## Related SME agents

- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on, extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale_product_configurator`](../../../agents/modules/generated/sale_product_configurator.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp_account`](../mrp_account/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
