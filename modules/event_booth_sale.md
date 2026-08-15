---
layout: page
title: "Events Booths Sales (event_booth_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/event_booth_sale/
nav_order: 0
---
# Events Booths Sales — `event_booth_sale`

**Source:** [`agents/modules/generated/event_booth_sale.yaml`](../../agents/modules/generated/event_booth_sale.yaml) · **Wiki:** [`knowledge/modules/event_booth_sale/overview.md`](../../knowledge/modules/event_booth_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>event_booth_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Events Booths Sales</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/event_booth_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/event_booth_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage event booths sale

## Direct dependencies

[`event_booth`](event_booth.md), [`event_sale`](event_sale.md)

## Reverse dependencies (modules that depend on this)

[`website_event_booth_sale`](website_event_booth_sale.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.booth.configurator</code></div><div class="role">defined by <code>event_booth_sale</code></div></div>
<div class="model"><div class="name"><code>event.booth.registration</code></div><div class="role">defined by <code>event_booth_sale</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>event_booth_sale</code></div></div>
<div class="model"><div class="name"><code>event.booth</code></div><div class="role">extended by <code>event_booth_sale</code></div></div>
<div class="model"><div class="name"><code>event.booth.category</code></div><div class="role">extended by <code>event_booth_sale</code></div></div>
<div class="model"><div class="name"><code>event.type.booth</code></div><div class="role">extended by <code>event_booth_sale</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>event_booth_sale</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>event_booth_sale</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>event_booth_sale</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>event_booth_sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.event_booth` | depends_on, extends_model_from | `agents/modules/generated/event_booth.yaml` |
| `module.event_sale` | depends_on | `agents/modules/generated/event_sale.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.stock_account` | extends_model_from | `agents/modules/generated/stock_account.yaml` |

## Full wiki excerpt

- SME owner: [`module.event_booth_sale`](../../../agents/modules/generated/event_booth_sale.yaml)
- Domain: `marketing_events`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/event_booth_sale)
- Direct dependencies: [`event_booth`](../event_booth/overview.md), [`event_sale`](../event_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_event_booth_sale`](../website_event_booth_sale/overview.md)
- Impact graph: [`module:event_booth_sale`](../../impact-graph.json)

## Purpose

Manage event booths sale

## Model relationships

- `event.booth.configurator`
- `event.booth.registration` — extended by [`website_event_booth_sale_exhibitor`](../website_event_booth_sale_exhibitor/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `event.booth` — defined by [`event_booth`](../event_booth/overview.md)
- Extends `event.booth.category` — defined by [`event_booth`](../event_booth/overview.md)
- Extends `event.type.booth` — defined by [`event_booth`](../event_booth/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.event_booth`](../../../agents/modules/generated/event_booth.yaml) — depends_on, extends_model_from
- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — depends_on
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website_event_booth_sale`](../../../agents/modules/generated/website_event_booth_sale.yaml) — required_by
- [`module.website_event_booth_sale_exhibitor`](../../../agents/modules/generated/website_event_booth_sale_exhibitor.yaml) — model_extended_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`website_event_booth_sale_exhibitor`](../website_event_booth_sale_exhibitor/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`event_booth`](../event_booth/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
