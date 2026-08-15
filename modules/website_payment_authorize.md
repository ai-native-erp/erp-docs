---
layout: page
title: "Website - Payment Authorize (website_payment_authorize)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_payment_authorize/
nav_order: 0
---
# Website - Payment Authorize — `website_payment_authorize`

**Source:** [`agents/modules/generated/website_payment_authorize.yaml`](../../agents/modules/generated/website_payment_authorize.yaml) · **Wiki:** [`knowledge/modules/website_payment_authorize/overview.md`](../../knowledge/modules/website_payment_authorize/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_payment_authorize</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Website - Payment Authorize</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_payment_authorize</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_payment_authorize"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Website - Payment Authorize

## Direct dependencies

[`payment_authorize`](payment_authorize.md), [`website_payment`](website_payment.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website_payment_authorize</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.payment_authorize` | depends_on | `agents/modules/generated/payment_authorize.yaml` |
| `module.website_payment` | depends_on | `agents/modules/generated/website_payment.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_payment_authorize`](../../../agents/modules/generated/website_payment_authorize.yaml)
- Domain: `website_ecommerce`
- Category: Accounting/Payment Providers
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_payment_authorize)
- Direct dependencies: [`payment_authorize`](../payment_authorize/overview.md), [`website_payment`](../website_payment/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_payment_authorize`](../../impact-graph.json)

## Purpose

Website - Payment Authorize

## Model relationships

- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.payment_authorize`](../../../agents/modules/generated/payment_authorize.yaml) — depends_on
- [`module.website_payment`](../../../agents/modules/generated/website_payment.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
