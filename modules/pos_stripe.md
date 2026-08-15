---
layout: page
title: "POS Stripe (pos_stripe)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_stripe/
nav_order: 0
---
# POS Stripe — `pos_stripe`

**Source:** [`agents/modules/generated/pos_stripe.yaml`](../../agents/modules/generated/pos_stripe.yaml) · **Wiki:** [`knowledge/modules/pos_stripe/overview.md`](../../knowledge/modules/pos_stripe/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_stripe</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">POS Stripe</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_stripe</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_stripe"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Integrate your POS with a Stripe payment terminal

## Direct dependencies

[`payment_stripe`](payment_stripe.md), [`point_of_sale`](point_of_sale.md)

## Reverse dependencies (modules that depend on this)

[`pos_restaurant_stripe`](pos_restaurant_stripe.md), [`pos_self_order_stripe`](pos_self_order_stripe.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.payment.method</code></div><div class="role">extended by <code>pos_stripe</code></div></div>
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>pos_stripe</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.payment_stripe` | depends_on | `agents/modules/generated/payment_stripe.yaml` |
| `module.point_of_sale` | depends_on, extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.pos_restaurant_stripe` | required_by | `agents/modules/generated/pos_restaurant_stripe.yaml` |
| `module.pos_self_order_stripe` | required_by | `agents/modules/generated/pos_self_order_stripe.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_stripe`](../../../agents/modules/generated/pos_stripe.yaml)
- Domain: `point_of_sale`
- Category: Sales/Point of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_stripe)
- Direct dependencies: [`payment_stripe`](../payment_stripe/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`pos_restaurant_stripe`](../pos_restaurant_stripe/overview.md), [`pos_self_order_stripe`](../pos_self_order_stripe/overview.md)
- Impact graph: [`module:pos_stripe`](../../impact-graph.json)

## Purpose

Integrate your POS with a Stripe payment terminal

## Model relationships

- Extends `pos.payment.method` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)

## Related SME agents

- [`module.payment_stripe`](../../../agents/modules/generated/payment_stripe.yaml) — depends_on
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on, extends_model_from
- [`module.pos_restaurant_stripe`](../../../agents/modules/generated/pos_restaurant_stripe.yaml) — required_by
- [`module.pos_self_order_stripe`](../../../agents/modules/generated/pos_self_order_stripe.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`point_of_sale`](../point_of_sale/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
