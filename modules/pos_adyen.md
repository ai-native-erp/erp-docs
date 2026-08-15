---
layout: page
title: "POS Adyen (pos_adyen)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_adyen/
nav_order: 0
---
# POS Adyen — `pos_adyen`

**Source:** [`agents/modules/generated/pos_adyen.yaml`](../../agents/modules/generated/pos_adyen.yaml) · **Wiki:** [`knowledge/modules/pos_adyen/overview.md`](../../knowledge/modules/pos_adyen/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_adyen</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">POS Adyen</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_adyen</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_adyen"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Integrate your POS with an Adyen payment terminal

## Direct dependencies

[`point_of_sale`](point_of_sale.md)

## Reverse dependencies (modules that depend on this)

[`pos_restaurant_adyen`](pos_restaurant_adyen.md), [`pos_self_order_adyen`](pos_self_order_adyen.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.config</code></div><div class="role">extended by <code>pos_adyen</code></div></div>
<div class="model"><div class="name"><code>pos.payment.method</code></div><div class="role">extended by <code>pos_adyen</code></div></div>
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>pos_adyen</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>pos_adyen</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.point_of_sale` | depends_on, extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.pos_restaurant_adyen` | required_by | `agents/modules/generated/pos_restaurant_adyen.yaml` |
| `module.pos_self_order_adyen` | required_by | `agents/modules/generated/pos_self_order_adyen.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_adyen`](../../../agents/modules/generated/pos_adyen.yaml)
- Domain: `point_of_sale`
- Category: Sales/Point of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_adyen)
- Direct dependencies: [`point_of_sale`](../point_of_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`pos_restaurant_adyen`](../pos_restaurant_adyen/overview.md), [`pos_self_order_adyen`](../pos_self_order_adyen/overview.md)
- Impact graph: [`module:pos_adyen`](../../impact-graph.json)

## Purpose

Integrate your POS with an Adyen payment terminal

## Model relationships

- Extends `pos.config` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.payment.method` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on, extends_model_from
- [`module.pos_restaurant_adyen`](../../../agents/modules/generated/pos_restaurant_adyen.yaml) — required_by
- [`module.pos_self_order_adyen`](../../../agents/modules/generated/pos_self_order_adyen.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`point_of_sale`](../point_of_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
