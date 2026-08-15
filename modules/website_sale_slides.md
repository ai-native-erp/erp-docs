---
layout: page
title: "Sell Courses (website_sale_slides)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_sale_slides/
nav_order: 0
---
# Sell Courses — `website_sale_slides`

**Source:** [`agents/modules/generated/website_sale_slides.yaml`](../../agents/modules/generated/website_sale_slides.yaml) · **Wiki:** [`knowledge/modules/website_sale_slides/overview.md`](../../knowledge/modules/website_sale_slides/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_sale_slides</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sell Courses</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_sale_slides</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_slides"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Sell your courses online

## Direct dependencies

[`website_sale`](website_sale.md), [`website_slides`](website_slides.md)

## Reverse dependencies (modules that depend on this)

[`spreadsheet_dashboard_website_sale_slides`](spreadsheet_dashboard_website_sale_slides.md), [`test_website_slides_full`](test_website_slides_full.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>website_sale_slides</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>website_sale_slides</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>website_sale_slides</code></div></div>
<div class="model"><div class="name"><code>slide.channel</code></div><div class="role">extended by <code>website_sale_slides</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_sale_slides</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.spreadsheet_dashboard_website_sale_slides` | required_by | `agents/modules/generated/spreadsheet_dashboard_website_sale_slides.yaml` |
| `module.stock_account` | extends_model_from | `agents/modules/generated/stock_account.yaml` |
| `module.test_website_slides_full` | required_by | `agents/modules/generated/test_website_slides_full.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_sale` | depends_on, extends_model_from | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_sale_slides`](../../../agents/modules/generated/website_sale_slides.yaml)
- Domain: `website_ecommerce`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_slides)
- Direct dependencies: [`website_sale`](../website_sale/overview.md), [`website_slides`](../website_slides/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`spreadsheet_dashboard_website_sale_slides`](../spreadsheet_dashboard_website_sale_slides/overview.md), [`test_website_slides_full`](../test_website_slides_full/overview.md)
- Impact graph: [`module:website_sale_slides`](../../impact-graph.json)

## Purpose

Sell your courses online

## Model relationships

- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `slide.channel` — defined by [`website_slides`](../website_slides/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.spreadsheet_dashboard_website_sale_slides`](../../../agents/modules/generated/spreadsheet_dashboard_website_sale_slides.yaml) — required_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.test_website_slides_full`](../../../agents/modules/generated/test_website_slides_full.yaml) — required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — depends_on, extends_model_from
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock_account`](../stock_account/overview.md), [`website`](../website/overview.md), [`website_sale`](../website_sale/overview.md), [`website_slides`](../website_slides/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
