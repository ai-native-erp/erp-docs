---
layout: page
title: "Coupons, Promotions, Gift Card and Loyalty for eCommerce (website_sale_loyalty)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_sale_loyalty/
nav_order: 0
---
# Coupons, Promotions, Gift Card and Loyalty for eCommerce — `website_sale_loyalty`

**Source:** [`agents/modules/generated/website_sale_loyalty.yaml`](../../agents/modules/generated/website_sale_loyalty.yaml) · **Wiki:** [`knowledge/modules/website_sale_loyalty/overview.md`](../../knowledge/modules/website_sale_loyalty/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_sale_loyalty</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Coupons, Promotions, Gift Card and Loyalty for eCommerce</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_sale_loyalty</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_loyalty"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Use coupon, promotion, gift cards and loyalty programs in your eCommerce store

## Direct dependencies

[`sale_loyalty`](sale_loyalty.md), [`website_links`](website_links.md), [`website_sale`](website_sale.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>coupon.share</code></div><div class="role">defined by <code>website_sale_loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.program</code></div><div class="role">defined by <code>website_sale_loyalty</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>loyalty.card</code></div><div class="role">extended by <code>website_sale_loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.program</code></div><div class="role">extended by <code>website_sale_loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.rule</code></div><div class="role">extended by <code>website_sale_loyalty</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>website_sale_loyalty</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>website_sale_loyalty</code></div></div>
<div class="model"><div class="name"><code>website.multi.mixin</code></div><div class="role">extended by <code>website_sale_loyalty</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.loyalty` | extends_model_from | `agents/modules/generated/loyalty.yaml` |
| `module.pos_loyalty` | model_extended_by | `agents/modules/generated/pos_loyalty.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_loyalty` | depends_on, model_extended_by | `agents/modules/generated/sale_loyalty.yaml` |
| `module.sale_loyalty_delivery` | model_extended_by | `agents/modules/generated/sale_loyalty_delivery.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_links` | depends_on | `agents/modules/generated/website_links.yaml` |
| `module.website_sale` | depends_on | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_sale_loyalty`](../../../agents/modules/generated/website_sale_loyalty.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_loyalty)
- Direct dependencies: [`sale_loyalty`](../sale_loyalty/overview.md), [`website_links`](../website_links/overview.md), [`website_sale`](../website_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_sale_loyalty`](../../impact-graph.json)

## Purpose

Use coupon, promotion, gift cards and loyalty programs in your eCommerce store

## Model relationships

- `coupon.share`
- `loyalty.program` — extended by [`pos_loyalty`](../pos_loyalty/overview.md), [`sale_loyalty`](../sale_loyalty/overview.md), [`sale_loyalty_delivery`](../sale_loyalty_delivery/overview.md)
- Extends `loyalty.card` — defined by [`loyalty`](../loyalty/overview.md)
- Extends `loyalty.program` — defined by [`loyalty`](../loyalty/overview.md)
- Extends `loyalty.rule` — defined by [`loyalty`](../loyalty/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)
- Extends `website.multi.mixin` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — extends_model_from
- [`module.pos_loyalty`](../../../agents/modules/generated/pos_loyalty.yaml) — model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_loyalty`](../../../agents/modules/generated/sale_loyalty.yaml) — depends_on, model_extended_by
- [`module.sale_loyalty_delivery`](../../../agents/modules/generated/sale_loyalty_delivery.yaml) — model_extended_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_links`](../../../agents/modules/generated/website_links.yaml) — depends_on
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`pos_loyalty`](../pos_loyalty/overview.md), [`sale_loyalty`](../sale_loyalty/overview.md), [`sale_loyalty_delivery`](../sale_loyalty_delivery/overview.md).
- Review model owners used by this module: [`loyalty`](../loyalty/overview.md), [`sale`](../sale/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
