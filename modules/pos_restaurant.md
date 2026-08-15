---
layout: page
title: "Restaurant (pos_restaurant)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_restaurant/
nav_order: 0
---
# Restaurant — `pos_restaurant`

**Source:** [`agents/modules/generated/pos_restaurant.yaml`](../../agents/modules/generated/pos_restaurant.yaml) · **Wiki:** [`knowledge/modules/pos_restaurant/overview.md`](../../knowledge/modules/pos_restaurant/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_restaurant</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Restaurant</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_restaurant</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_restaurant"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Restaurant extensions for the Point of Sale

## Direct dependencies

[`point_of_sale`](point_of_sale.md)

## Reverse dependencies (modules that depend on this)

[`pos_hr_restaurant`](pos_hr_restaurant.md), [`pos_restaurant_adyen`](pos_restaurant_adyen.md), [`pos_restaurant_loyalty`](pos_restaurant_loyalty.md), [`pos_restaurant_stripe`](pos_restaurant_stripe.md), [`pos_self_order`](pos_self_order.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>restaurant.floor</code></div><div class="role">defined by <code>pos_restaurant</code></div></div>
<div class="model"><div class="name"><code>restaurant.table</code></div><div class="role">defined by <code>pos_restaurant</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.config</code></div><div class="role">extended by <code>pos_restaurant</code></div></div>
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">extended by <code>pos_restaurant</code></div></div>
<div class="model"><div class="name"><code>pos.order.line</code></div><div class="role">extended by <code>pos_restaurant</code></div></div>
<div class="model"><div class="name"><code>pos.payment</code></div><div class="role">extended by <code>pos_restaurant</code></div></div>
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>pos_restaurant</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>pos_restaurant</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_ch_pos` | extends_model_from | `agents/modules/generated/l10n_ch_pos.yaml` |
| `module.point_of_sale` | depends_on, extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.pos_hr_restaurant` | required_by | `agents/modules/generated/pos_hr_restaurant.yaml` |
| `module.pos_restaurant_adyen` | required_by | `agents/modules/generated/pos_restaurant_adyen.yaml` |
| `module.pos_restaurant_loyalty` | required_by | `agents/modules/generated/pos_restaurant_loyalty.yaml` |
| `module.pos_restaurant_stripe` | required_by | `agents/modules/generated/pos_restaurant_stripe.yaml` |
| `module.pos_self_order` | model_extended_by, required_by | `agents/modules/generated/pos_self_order.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_restaurant`](../../../agents/modules/generated/pos_restaurant.yaml)
- Domain: `point_of_sale`
- Category: Sales/Point of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_restaurant)
- Direct dependencies: [`point_of_sale`](../point_of_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`pos_hr_restaurant`](../pos_hr_restaurant/overview.md), [`pos_restaurant_adyen`](../pos_restaurant_adyen/overview.md), [`pos_restaurant_loyalty`](../pos_restaurant_loyalty/overview.md), [`pos_restaurant_stripe`](../pos_restaurant_stripe/overview.md), [`pos_self_order`](../pos_self_order/overview.md)
- Impact graph: [`module:pos_restaurant`](../../impact-graph.json)

## Purpose

Restaurant extensions for the Point of Sale

## Model relationships

- `restaurant.floor`
- `restaurant.table` — extended by [`pos_self_order`](../pos_self_order/overview.md)
- Extends `pos.config` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.order` — defined by [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.order.line` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.payment` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on, extends_model_from
- [`module.pos_hr_restaurant`](../../../agents/modules/generated/pos_hr_restaurant.yaml) — required_by
- [`module.pos_restaurant_adyen`](../../../agents/modules/generated/pos_restaurant_adyen.yaml) — required_by
- [`module.pos_restaurant_loyalty`](../../../agents/modules/generated/pos_restaurant_loyalty.yaml) — required_by
- [`module.pos_restaurant_stripe`](../../../agents/modules/generated/pos_restaurant_stripe.yaml) — required_by
- [`module.pos_self_order`](../../../agents/modules/generated/pos_self_order.yaml) — model_extended_by, required_by

## Regression impact checklist

- Review 5 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`pos_self_order`](../pos_self_order/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
