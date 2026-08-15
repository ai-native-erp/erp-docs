---
layout: page
title: "Sale Loyalty - Delivery (sale_loyalty_delivery)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_loyalty_delivery/
nav_order: 0
---
# Sale Loyalty - Delivery — `sale_loyalty_delivery`

**Source:** [`agents/modules/generated/sale_loyalty_delivery.yaml`](../../agents/modules/generated/sale_loyalty_delivery.yaml) · **Wiki:** [`knowledge/modules/sale_loyalty_delivery/overview.md`](../../knowledge/modules/sale_loyalty_delivery/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_loyalty_delivery</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sale Loyalty - Delivery</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_loyalty_delivery</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_loyalty_delivery"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Adds free shipping mechanism in sales orders

## Direct dependencies

[`delivery`](delivery.md), [`sale_loyalty`](sale_loyalty.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>loyalty.program</code></div><div class="role">extended by <code>sale_loyalty_delivery</code></div></div>
<div class="model"><div class="name"><code>loyalty.reward</code></div><div class="role">extended by <code>sale_loyalty_delivery</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_loyalty_delivery</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.delivery` | depends_on | `agents/modules/generated/delivery.yaml` |
| `module.loyalty` | extends_model_from | `agents/modules/generated/loyalty.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_loyalty` | depends_on | `agents/modules/generated/sale_loyalty.yaml` |
| `module.website_sale_loyalty` | extends_model_from | `agents/modules/generated/website_sale_loyalty.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_loyalty_delivery`](../../../agents/modules/generated/sale_loyalty_delivery.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_loyalty_delivery)
- Direct dependencies: [`delivery`](../delivery/overview.md), [`sale_loyalty`](../sale_loyalty/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:sale_loyalty_delivery`](../../impact-graph.json)

## Purpose

Adds free shipping mechanism in sales orders

## Model relationships

- Extends `loyalty.program` — defined by [`loyalty`](../loyalty/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md)
- Extends `loyalty.reward` — defined by [`loyalty`](../loyalty/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — depends_on
- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_loyalty`](../../../agents/modules/generated/sale_loyalty.yaml) — depends_on
- [`module.website_sale_loyalty`](../../../agents/modules/generated/website_sale_loyalty.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`loyalty`](../loyalty/overview.md), [`sale`](../sale/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
