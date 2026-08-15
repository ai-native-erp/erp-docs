---
layout: page
title: "Events Sales (event_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/event_sale/
nav_order: 0
---
# Events Sales — `event_sale`

**Source:** [`agents/modules/generated/event_sale.yaml`](../../agents/modules/generated/event_sale.yaml) · **Wiki:** [`knowledge/modules/event_sale/overview.md`](../../knowledge/modules/event_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>event_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Events Sales</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/event_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/event_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`event`](event.md), [`sale_management`](sale_management.md)

## Reverse dependencies (modules that depend on this)

[`event_booth_sale`](event_booth_sale.md), [`event_crm_sale`](event_crm_sale.md), [`spreadsheet_dashboard_event_sale`](spreadsheet_dashboard_event_sale.md), [`test_event_full`](test_event_full.md), [`test_sale_product_configurators`](test_sale_product_configurators.md), [`website_event_sale`](website_event_sale.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.event.configurator</code></div><div class="role">defined by <code>event_sale</code></div></div>
<div class="model"><div class="name"><code>event.sale.report</code></div><div class="role">defined by <code>event_sale</code></div></div>
<div class="model"><div class="name"><code>registration.editor</code></div><div class="role">defined by <code>event_sale</code></div></div>
<div class="model"><div class="name"><code>registration.editor.line</code></div><div class="role">defined by <code>event_sale</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.event</code></div><div class="role">extended by <code>event_sale</code></div></div>
<div class="model"><div class="name"><code>event.event.ticket</code></div><div class="role">extended by <code>event_sale</code></div></div>
<div class="model"><div class="name"><code>event.registration</code></div><div class="role">extended by <code>event_sale</code></div></div>
<div class="model"><div class="name"><code>event.type.ticket</code></div><div class="role">extended by <code>event_sale</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>event_sale</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>event_sale</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>event_sale</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>event_sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.event` | depends_on, extends_model_from | `agents/modules/generated/event.yaml` |
| `module.event_booth_sale` | required_by | `agents/modules/generated/event_booth_sale.yaml` |
| `module.event_crm` | extends_model_from | `agents/modules/generated/event_crm.yaml` |
| `module.event_crm_sale` | required_by | `agents/modules/generated/event_crm_sale.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_management` | depends_on | `agents/modules/generated/sale_management.yaml` |

## Full wiki excerpt

- SME owner: [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml)
- Domain: `marketing_events`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/event_sale)
- Direct dependencies: [`event`](../event/overview.md), [`sale_management`](../sale_management/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`event_booth_sale`](../event_booth_sale/overview.md), [`event_crm_sale`](../event_crm_sale/overview.md), [`spreadsheet_dashboard_event_sale`](../spreadsheet_dashboard_event_sale/overview.md), [`test_event_full`](../test_event_full/overview.md), [`test_sale_product_configurators`](../test_sale_product_configurators/overview.md), [`website_event_sale`](../website_event_sale/overview.md)
- Impact graph: [`module:event_sale`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `event.event.configurator`
- `event.sale.report` — extended by [`website_event_sale`](../website_event_sale/overview.md)
- `registration.editor`
- `registration.editor.line`
- Extends `event.event` — defined by [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`website_event`](../website_event/overview.md)
- Extends `event.event.ticket` — defined by [`event`](../event/overview.md)
- Extends `event.registration` — defined by [`event`](../event/overview.md), [`website_event`](../website_event/overview.md)
- Extends `event.type.ticket` — defined by [`event`](../event/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.event`](../../../agents/modules/generated/event.yaml) — depends_on, extends_model_from
- [`module.event_booth_sale`](../../../agents/modules/generated/event_booth_sale.yaml) — required_by
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — extends_model_from
- [`module.event_crm_sale`](../../../agents/modules/generated/event_crm_sale.yaml) — required_by
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — depends_on
- [`module.spreadsheet_dashboard_event_sale`](../../../agents/modules/generated/spreadsheet_dashboard_event_sale.yaml) — required_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.test_event_full`](../../../agents/modules/generated/test_event_full.yaml) — required_by
- [`module.test_sale_product_configurators`](../../../agents/modules/generated/test_sale_product_configurators.yaml) — required_by
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — extends_model_from
- [`module.website_event_sale`](../../../agents/modules/generated/website_event_sale.yaml) — model_extended_by, required_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 6 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`website_event_sale`](../website_event_sale/overview.md).
- Review model owners used by this module: [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock_account`](../stock_account/overview.md), [`website_event`](../website_event/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
