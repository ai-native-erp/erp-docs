---
layout: page
title: "Sale Matrix (sale_product_matrix)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_product_matrix/
nav_order: 0
---
# Sale Matrix — `sale_product_matrix`

**Source:** [`agents/modules/generated/sale_product_matrix.yaml`](../../agents/modules/generated/sale_product_matrix.yaml) · **Wiki:** [`knowledge/modules/sale_product_matrix/overview.md`](../../knowledge/modules/sale_product_matrix/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_product_matrix</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sale Matrix</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_product_matrix</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_product_matrix"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Add variants to Sales Order through a grid entry.

## Direct dependencies

[`product_matrix`](product_matrix.md), [`sale`](sale.md), [`sale_product_configurator`](sale_product_configurator.md)

## Reverse dependencies (modules that depend on this)

[`test_sale_product_configurators`](test_sale_product_configurators.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>sale_product_matrix</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_product_matrix</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale_product_matrix</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.product_matrix` | depends_on | `agents/modules/generated/product_matrix.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale` | depends_on, extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_product_configurator` | depends_on | `agents/modules/generated/sale_product_configurator.yaml` |
| `module.stock_account` | extends_model_from | `agents/modules/generated/stock_account.yaml` |
| `module.test_sale_product_configurators` | required_by | `agents/modules/generated/test_sale_product_configurators.yaml` |
| `module.website_sale` | extends_model_from | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_product_matrix`](../../../agents/modules/generated/sale_product_matrix.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_product_matrix)
- Direct dependencies: [`product_matrix`](../product_matrix/overview.md), [`sale`](../sale/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_sale_product_configurators`](../test_sale_product_configurators/overview.md)
- Impact graph: [`module:sale_product_matrix`](../../impact-graph.json)

## Purpose

Add variants to Sales Order through a grid entry.

## Model relationships

- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.product_matrix`](../../../agents/modules/generated/product_matrix.yaml) — depends_on
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — depends_on, extends_model_from
- [`module.sale_product_configurator`](../../../agents/modules/generated/sale_product_configurator.yaml) — depends_on
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.test_sale_product_configurators`](../../../agents/modules/generated/test_sale_product_configurators.yaml) — required_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
