---
layout: page
title: "Razorpay OAuth Integration (payment_razorpay_oauth)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/payment_razorpay_oauth/
nav_order: 0
---
# Razorpay OAuth Integration — `payment_razorpay_oauth`

**Source:** [`agents/modules/generated/payment_razorpay_oauth.yaml`](../../agents/modules/generated/payment_razorpay_oauth.yaml) · **Wiki:** [`knowledge/modules/payment_razorpay_oauth/overview.md`](../../knowledge/modules/payment_razorpay_oauth/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>payment_razorpay_oauth</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Razorpay OAuth Integration</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/payment_razorpay_oauth</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/payment_razorpay_oauth"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Easy Razorpay Onboarding With Oauth.

## Direct dependencies

[`payment_razorpay`](payment_razorpay.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>payment.provider</code></div><div class="role">extended by <code>payment_razorpay_oauth</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.payment` | extends_model_from | `agents/modules/generated/payment.yaml` |
| `module.payment_razorpay` | depends_on | `agents/modules/generated/payment_razorpay.yaml` |

## Full wiki excerpt

- SME owner: [`module.payment_razorpay_oauth`](../../../agents/modules/generated/payment_razorpay_oauth.yaml)
- Domain: `accounting`
- Category: Accounting/Payment Providers
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/payment_razorpay_oauth)
- Direct dependencies: [`payment_razorpay`](../payment_razorpay/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:payment_razorpay_oauth`](../../impact-graph.json)

## Purpose

Easy Razorpay Onboarding With Oauth.

## Model relationships

- Extends `payment.provider` — defined by [`payment`](../payment/overview.md)

## Related SME agents

- [`module.payment`](../../../agents/modules/generated/payment.yaml) — extends_model_from
- [`module.payment_razorpay`](../../../agents/modules/generated/payment_razorpay.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`payment`](../payment/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
