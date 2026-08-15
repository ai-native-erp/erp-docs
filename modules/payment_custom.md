---
layout: page
title: "Payment Provider: Custom Payment Modes (payment_custom)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/payment_custom/
nav_order: 0
---
# Payment Provider: Custom Payment Modes — `payment_custom`

**Source:** [`agents/modules/generated/payment_custom.yaml`](../../agents/modules/generated/payment_custom.yaml) · **Wiki:** [`knowledge/modules/payment_custom/overview.md`](../../knowledge/modules/payment_custom/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>payment_custom</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Payment Provider: Custom Payment Modes</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/payment_custom</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/payment_custom"><code>126b5bd</code></a></div></div>
</div>
## Purpose

A payment provider for custom flows like wire transfers.

## Direct dependencies

[`payment`](payment.md)

## Reverse dependencies (modules that depend on this)

[`website_sale_picking`](website_sale_picking.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>payment.provider</code></div><div class="role">extended by <code>payment_custom</code></div></div>
<div class="model"><div class="name"><code>payment.transaction</code></div><div class="role">extended by <code>payment_custom</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.payment` | depends_on, extends_model_from | `agents/modules/generated/payment.yaml` |
| `module.website_sale_picking` | required_by | `agents/modules/generated/website_sale_picking.yaml` |

## Full wiki excerpt

- SME owner: [`module.payment_custom`](../../../agents/modules/generated/payment_custom.yaml)
- Domain: `accounting`
- Category: Accounting/Payment Providers
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/payment_custom)
- Direct dependencies: [`payment`](../payment/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_sale_picking`](../website_sale_picking/overview.md)
- Impact graph: [`module:payment_custom`](../../impact-graph.json)

## Purpose

A payment provider for custom flows like wire transfers.

## Model relationships

- Extends `payment.provider` — defined by [`payment`](../payment/overview.md)
- Extends `payment.transaction` — defined by [`payment`](../payment/overview.md)

## Related SME agents

- [`module.payment`](../../../agents/modules/generated/payment.yaml) — depends_on, extends_model_from
- [`module.website_sale_picking`](../../../agents/modules/generated/website_sale_picking.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`payment`](../payment/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
