---
layout: page
title: "Online Event Booth Sale (website_event_booth_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_event_booth_sale/
nav_order: 0
---
# Online Event Booth Sale — `website_event_booth_sale`

**Source:** [`agents/modules/generated/website_event_booth_sale.yaml`](../../agents/modules/generated/website_event_booth_sale.yaml) · **Wiki:** [`knowledge/modules/website_event_booth_sale/overview.md`](../../knowledge/modules/website_event_booth_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_event_booth_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Online Event Booth Sale</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_event_booth_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_booth_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Events, sell your booths online

## Direct dependencies

[`event_booth_sale`](event_booth_sale.md), [`website_event_booth`](website_event_booth.md), [`website_sale`](website_sale.md)

## Reverse dependencies (modules that depend on this)

[`website_event_booth_sale_exhibitor`](website_event_booth_sale_exhibitor.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>website_event_booth_sale</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>website_event_booth_sale</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>website_event_booth_sale</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_event_booth_sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.event_booth_sale` | depends_on | `agents/modules/generated/event_booth_sale.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.stock_account` | extends_model_from | `agents/modules/generated/stock_account.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_event_booth` | depends_on | `agents/modules/generated/website_event_booth.yaml` |
| `module.website_event_booth_sale_exhibitor` | required_by | `agents/modules/generated/website_event_booth_sale_exhibitor.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_event_booth_sale`](../../../agents/modules/generated/website_event_booth_sale.yaml)
- Domain: `website_ecommerce`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_booth_sale)
- Direct dependencies: [`event_booth_sale`](../event_booth_sale/overview.md), [`website_event_booth`](../website_event_booth/overview.md), [`website_sale`](../website_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_event_booth_sale_exhibitor`](../website_event_booth_sale_exhibitor/overview.md)
- Impact graph: [`module:website_event_booth_sale`](../../impact-graph.json)

## Purpose

Events, sell your booths online

## Model relationships

- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.event_booth_sale`](../../../agents/modules/generated/event_booth_sale.yaml) — depends_on
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_event_booth`](../../../agents/modules/generated/website_event_booth.yaml) — depends_on
- [`module.website_event_booth_sale_exhibitor`](../../../agents/modules/generated/website_event_booth_sale_exhibitor.yaml) — required_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock_account`](../stock_account/overview.md), [`website`](../website/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
