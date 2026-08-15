---
layout: page
title: "Sale Loyalty (sale_loyalty)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_loyalty/
nav_order: 0
---
# Sale Loyalty — `sale_loyalty`

**Source:** [`agents/modules/generated/sale_loyalty.yaml`](../../agents/modules/generated/sale_loyalty.yaml) · **Wiki:** [`knowledge/modules/sale_loyalty/overview.md`](../../knowledge/modules/sale_loyalty/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_loyalty</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sale Loyalty</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_loyalty</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_loyalty"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Use discounts and loyalty programs in sales orders

## Direct dependencies

[`loyalty`](loyalty.md), [`sale`](sale.md)

## Reverse dependencies (modules that depend on this)

[`sale_loyalty_delivery`](sale_loyalty_delivery.md), [`website_sale_loyalty`](website_sale_loyalty.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>sale.loyalty.coupon.wizard</code></div><div class="role">defined by <code>sale_loyalty</code></div></div>
<div class="model"><div class="name"><code>sale.loyalty.reward.wizard</code></div><div class="role">defined by <code>sale_loyalty</code></div></div>
<div class="model"><div class="name"><code>sale.order.coupon.points</code></div><div class="role">defined by <code>sale_loyalty</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>loyalty.card</code></div><div class="role">extended by <code>sale_loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.program</code></div><div class="role">extended by <code>sale_loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.reward</code></div><div class="role">extended by <code>sale_loyalty</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_loyalty</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale_loyalty</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.loyalty` | depends_on, extends_model_from | `agents/modules/generated/loyalty.yaml` |
| `module.sale` | depends_on, extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_loyalty_delivery` | required_by | `agents/modules/generated/sale_loyalty_delivery.yaml` |
| `module.website_sale_loyalty` | extends_model_from, required_by | `agents/modules/generated/website_sale_loyalty.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_loyalty`](../../../agents/modules/generated/sale_loyalty.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_loyalty)
- Direct dependencies: [`loyalty`](../loyalty/overview.md), [`sale`](../sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`sale_loyalty_delivery`](../sale_loyalty_delivery/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md)
- Impact graph: [`module:sale_loyalty`](../../impact-graph.json)

## Purpose

Use discounts and loyalty programs in sales orders

## Model relationships

- `sale.loyalty.coupon.wizard`
- `sale.loyalty.reward.wizard`
- `sale.order.coupon.points`
- Extends `loyalty.card` — defined by [`loyalty`](../loyalty/overview.md)
- Extends `loyalty.program` — defined by [`loyalty`](../loyalty/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md)
- Extends `loyalty.reward` — defined by [`loyalty`](../loyalty/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — depends_on, extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — depends_on, extends_model_from
- [`module.sale_loyalty_delivery`](../../../agents/modules/generated/sale_loyalty_delivery.yaml) — required_by
- [`module.website_sale_loyalty`](../../../agents/modules/generated/website_sale_loyalty.yaml) — extends_model_from, required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`loyalty`](../loyalty/overview.md), [`sale`](../sale/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
