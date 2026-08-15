---
layout: page
title: "On site Payment & Picking (website_sale_picking)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_sale_picking/
nav_order: 0
---
# On site Payment & Picking — `website_sale_picking`

**Source:** [`agents/modules/generated/website_sale_picking.yaml`](../../agents/modules/generated/website_sale_picking.yaml) · **Wiki:** [`knowledge/modules/website_sale_picking/overview.md`](../../knowledge/modules/website_sale_picking/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_sale_picking</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">On site Payment & Picking</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_sale_picking</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_picking"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`payment_custom`](payment_custom.md), [`stock`](stock.md), [`website_sale`](website_sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>delivery.carrier</code></div><div class="role">extended by <code>website_sale_picking</code></div></div>
<div class="model"><div class="name"><code>payment.provider</code></div><div class="role">extended by <code>website_sale_picking</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website_sale_picking</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>website_sale_picking</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_sale_picking</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.delivery` | extends_model_from | `agents/modules/generated/delivery.yaml` |
| `module.payment` | extends_model_from | `agents/modules/generated/payment.yaml` |
| `module.payment_custom` | depends_on | `agents/modules/generated/payment_custom.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.stock` | depends_on | `agents/modules/generated/stock.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_sale` | depends_on, extends_model_from | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_sale_picking`](../../../agents/modules/generated/website_sale_picking.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_picking)
- Direct dependencies: [`payment_custom`](../payment_custom/overview.md), [`stock`](../stock/overview.md), [`website_sale`](../website_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_sale_picking`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `delivery.carrier` — defined by [`delivery`](../delivery/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `payment.provider` — defined by [`payment`](../payment/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — extends_model_from
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — extends_model_from
- [`module.payment_custom`](../../../agents/modules/generated/payment_custom.yaml) — depends_on
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`delivery`](../delivery/overview.md), [`payment`](../payment/overview.md), [`sale`](../sale/overview.md), [`website`](../website/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
