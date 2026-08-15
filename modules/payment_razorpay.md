---
layout: page
title: "Payment Provider: Razorpay (payment_razorpay)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/payment_razorpay/
nav_order: 0
---
# Payment Provider: Razorpay — `payment_razorpay`

**Source:** [`agents/modules/generated/payment_razorpay.yaml`](../../agents/modules/generated/payment_razorpay.yaml) · **Wiki:** [`knowledge/modules/payment_razorpay/overview.md`](../../knowledge/modules/payment_razorpay/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>payment_razorpay</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Payment Provider: Razorpay</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/payment_razorpay</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/payment_razorpay"><code>126b5bd</code></a></div></div>
</div>
## Purpose

A payment provider covering India.

## Direct dependencies

[`payment`](payment.md)

## Reverse dependencies (modules that depend on this)

[`payment_razorpay_oauth`](payment_razorpay_oauth.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>payment.provider</code></div><div class="role">extended by <code>payment_razorpay</code></div></div>
<div class="model"><div class="name"><code>payment.transaction</code></div><div class="role">extended by <code>payment_razorpay</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.payment` | depends_on, extends_model_from | `agents/modules/generated/payment.yaml` |
| `module.payment_razorpay_oauth` | required_by | `agents/modules/generated/payment_razorpay_oauth.yaml` |

## Full wiki excerpt

- SME owner: [`module.payment_razorpay`](../../../agents/modules/generated/payment_razorpay.yaml)
- Domain: `accounting`
- Category: Accounting/Payment Providers
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/payment_razorpay)
- Direct dependencies: [`payment`](../payment/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`payment_razorpay_oauth`](../payment_razorpay_oauth/overview.md)
- Impact graph: [`module:payment_razorpay`](../../impact-graph.json)

## Purpose

A payment provider covering India.

## Model relationships

- Extends `payment.provider` — defined by [`payment`](../payment/overview.md)
- Extends `payment.transaction` — defined by [`payment`](../payment/overview.md)

## Related SME agents

- [`module.payment`](../../../agents/modules/generated/payment.yaml) — depends_on, extends_model_from
- [`module.payment_razorpay_oauth`](../../../agents/modules/generated/payment_razorpay_oauth.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`payment`](../payment/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
