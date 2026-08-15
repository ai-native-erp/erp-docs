---
layout: page
title: "Point of Sale - Coupons & Loyalty (pos_loyalty)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_loyalty/
nav_order: 0
---
# Point of Sale - Coupons & Loyalty — `pos_loyalty`

**Source:** [`agents/modules/generated/pos_loyalty.yaml`](../../agents/modules/generated/pos_loyalty.yaml) · **Wiki:** [`knowledge/modules/pos_loyalty/overview.md`](../../knowledge/modules/pos_loyalty/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_loyalty</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Point of Sale - Coupons & Loyalty</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_loyalty</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_loyalty"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Use Coupons, Gift Cards and Loyalty programs in Point of Sale

## Direct dependencies

[`loyalty`](loyalty.md), [`point_of_sale`](point_of_sale.md)

## Reverse dependencies (modules that depend on this)

[`pos_restaurant_loyalty`](pos_restaurant_loyalty.md), [`pos_sale_loyalty`](pos_sale_loyalty.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>barcode.rule</code></div><div class="role">extended by <code>pos_loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.card</code></div><div class="role">extended by <code>pos_loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.mail</code></div><div class="role">extended by <code>pos_loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.program</code></div><div class="role">extended by <code>pos_loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.reward</code></div><div class="role">extended by <code>pos_loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.rule</code></div><div class="role">extended by <code>pos_loyalty</code></div></div>
<div class="model"><div class="name"><code>pos.config</code></div><div class="role">extended by <code>pos_loyalty</code></div></div>
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">extended by <code>pos_loyalty</code></div></div>
<div class="model"><div class="name"><code>pos.order.line</code></div><div class="role">extended by <code>pos_loyalty</code></div></div>
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>pos_loyalty</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>pos_loyalty</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.barcodes` | extends_model_from | `agents/modules/generated/barcodes.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_ch_pos` | extends_model_from | `agents/modules/generated/l10n_ch_pos.yaml` |
| `module.loyalty` | depends_on, extends_model_from | `agents/modules/generated/loyalty.yaml` |
| `module.point_of_sale` | depends_on, extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.pos_restaurant_loyalty` | required_by | `agents/modules/generated/pos_restaurant_loyalty.yaml` |
| `module.pos_sale_loyalty` | required_by | `agents/modules/generated/pos_sale_loyalty.yaml` |
| `module.website_sale_loyalty` | extends_model_from | `agents/modules/generated/website_sale_loyalty.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_loyalty`](../../../agents/modules/generated/pos_loyalty.yaml)
- Domain: `point_of_sale`
- Category: Sales/Point Of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_loyalty)
- Direct dependencies: [`loyalty`](../loyalty/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`pos_restaurant_loyalty`](../pos_restaurant_loyalty/overview.md), [`pos_sale_loyalty`](../pos_sale_loyalty/overview.md)
- Impact graph: [`module:pos_loyalty`](../../impact-graph.json)

## Purpose

Use Coupons, Gift Cards and Loyalty programs in Point of Sale

## Model relationships

- Extends `barcode.rule` — defined by [`barcodes`](../barcodes/overview.md)
- Extends `loyalty.card` — defined by [`loyalty`](../loyalty/overview.md)
- Extends `loyalty.mail` — defined by [`loyalty`](../loyalty/overview.md)
- Extends `loyalty.program` — defined by [`loyalty`](../loyalty/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md)
- Extends `loyalty.reward` — defined by [`loyalty`](../loyalty/overview.md)
- Extends `loyalty.rule` — defined by [`loyalty`](../loyalty/overview.md)
- Extends `pos.config` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.order` — defined by [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.order.line` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.barcodes`](../../../agents/modules/generated/barcodes.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml) — extends_model_from
- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — depends_on, extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on, extends_model_from
- [`module.pos_restaurant_loyalty`](../../../agents/modules/generated/pos_restaurant_loyalty.yaml) — required_by
- [`module.pos_sale_loyalty`](../../../agents/modules/generated/pos_sale_loyalty.yaml) — required_by
- [`module.website_sale_loyalty`](../../../agents/modules/generated/website_sale_loyalty.yaml) — extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`barcodes`](../barcodes/overview.md), [`base`](../base/overview.md), [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`loyalty`](../loyalty/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
