---
layout: page
title: "POS Restaurant Adyen (pos_restaurant_adyen)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_restaurant_adyen/
nav_order: 0
---
# POS Restaurant Adyen — `pos_restaurant_adyen`

**Source:** [`agents/modules/generated/pos_restaurant_adyen.yaml`](../../agents/modules/generated/pos_restaurant_adyen.yaml) · **Wiki:** [`knowledge/modules/pos_restaurant_adyen/overview.md`](../../knowledge/modules/pos_restaurant_adyen/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_restaurant_adyen</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">POS Restaurant Adyen</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_restaurant_adyen</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_restaurant_adyen"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Adds American style tipping to Adyen

## Direct dependencies

[`payment_adyen`](payment_adyen.md), [`pos_adyen`](pos_adyen.md), [`pos_restaurant`](pos_restaurant.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">extended by <code>pos_restaurant_adyen</code></div></div>
<div class="model"><div class="name"><code>pos.payment</code></div><div class="role">extended by <code>pos_restaurant_adyen</code></div></div>
<div class="model"><div class="name"><code>pos.payment.method</code></div><div class="role">extended by <code>pos_restaurant_adyen</code></div></div>
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>pos_restaurant_adyen</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_ch_pos` | extends_model_from | `agents/modules/generated/l10n_ch_pos.yaml` |
| `module.payment_adyen` | depends_on | `agents/modules/generated/payment_adyen.yaml` |
| `module.point_of_sale` | extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.pos_adyen` | depends_on | `agents/modules/generated/pos_adyen.yaml` |
| `module.pos_restaurant` | depends_on | `agents/modules/generated/pos_restaurant.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_restaurant_adyen`](../../../agents/modules/generated/pos_restaurant_adyen.yaml)
- Domain: `point_of_sale`
- Category: Point of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_restaurant_adyen)
- Direct dependencies: [`payment_adyen`](../payment_adyen/overview.md), [`pos_adyen`](../pos_adyen/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:pos_restaurant_adyen`](../../impact-graph.json)

## Purpose

Adds American style tipping to Adyen

## Model relationships

- Extends `pos.order` — defined by [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.payment` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.payment.method` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)

## Related SME agents

- [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml) — extends_model_from
- [`module.payment_adyen`](../../../agents/modules/generated/payment_adyen.yaml) — depends_on
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — extends_model_from
- [`module.pos_adyen`](../../../agents/modules/generated/pos_adyen.yaml) — depends_on
- [`module.pos_restaurant`](../../../agents/modules/generated/pos_restaurant.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
