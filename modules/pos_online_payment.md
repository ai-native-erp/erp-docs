---
layout: page
title: "Point of Sale online payment (pos_online_payment)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_online_payment/
nav_order: 0
---
# Point of Sale online payment — `pos_online_payment`

**Source:** [`agents/modules/generated/pos_online_payment.yaml`](../../agents/modules/generated/pos_online_payment.yaml) · **Wiki:** [`knowledge/modules/pos_online_payment/overview.md`](../../knowledge/modules/pos_online_payment/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_online_payment</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Point of Sale online payment</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_online_payment</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_online_payment"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account_payment`](account_payment.md), [`point_of_sale`](point_of_sale.md)

## Reverse dependencies (modules that depend on this)

[`pos_online_payment_self_order`](pos_online_payment_self_order.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.payment</code></div><div class="role">extended by <code>pos_online_payment</code></div></div>
<div class="model"><div class="name"><code>payment.transaction</code></div><div class="role">extended by <code>pos_online_payment</code></div></div>
<div class="model"><div class="name"><code>pos.config</code></div><div class="role">extended by <code>pos_online_payment</code></div></div>
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">extended by <code>pos_online_payment</code></div></div>
<div class="model"><div class="name"><code>pos.payment</code></div><div class="role">extended by <code>pos_online_payment</code></div></div>
<div class="model"><div class="name"><code>pos.payment.method</code></div><div class="role">extended by <code>pos_online_payment</code></div></div>
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>pos_online_payment</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_payment` | depends_on | `agents/modules/generated/account_payment.yaml` |
| `module.l10n_ch_pos` | extends_model_from | `agents/modules/generated/l10n_ch_pos.yaml` |
| `module.payment` | extends_model_from | `agents/modules/generated/payment.yaml` |
| `module.point_of_sale` | depends_on, extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.pos_online_payment_self_order` | required_by | `agents/modules/generated/pos_online_payment_self_order.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_online_payment`](../../../agents/modules/generated/pos_online_payment.yaml)
- Domain: `point_of_sale`
- Category: Uncategorized
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_online_payment)
- Direct dependencies: [`account_payment`](../account_payment/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`pos_online_payment_self_order`](../pos_online_payment_self_order/overview.md)
- Impact graph: [`module:pos_online_payment`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.payment` — defined by [`account`](../account/overview.md)
- Extends `payment.transaction` — defined by [`payment`](../payment/overview.md)
- Extends `pos.config` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.order` — defined by [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.payment` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.payment.method` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_payment`](../../../agents/modules/generated/account_payment.yaml) — depends_on
- [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml) — extends_model_from
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on, extends_model_from
- [`module.pos_online_payment_self_order`](../../../agents/modules/generated/pos_online_payment_self_order.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`payment`](../payment/overview.md), [`point_of_sale`](../point_of_sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
