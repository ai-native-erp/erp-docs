---
layout: page
title: "Payment - Account (account_payment)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_payment/
nav_order: 0
---
# Payment - Account — `account_payment`

**Source:** [`agents/modules/generated/account_payment.yaml`](../../agents/modules/generated/account_payment.yaml) · **Wiki:** [`knowledge/modules/account_payment/overview.md`](../../knowledge/modules/account_payment/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_payment</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Payment - Account</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_payment</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_payment"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Enable customers to pay invoices on the portal and post payments when transactions are processed.

## Direct dependencies

[`account`](account.md), [`payment`](payment.md)

## Reverse dependencies (modules that depend on this)

[`pos_online_payment`](pos_online_payment.md), [`sale`](sale.md), [`website_payment`](website_payment.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>payment.refund.wizard</code></div><div class="role">defined by <code>account_payment</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>account_payment</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>account_payment</code></div></div>
<div class="model"><div class="name"><code>account.payment</code></div><div class="role">extended by <code>account_payment</code></div></div>
<div class="model"><div class="name"><code>account.payment.method</code></div><div class="role">extended by <code>account_payment</code></div></div>
<div class="model"><div class="name"><code>account.payment.method.line</code></div><div class="role">extended by <code>account_payment</code></div></div>
<div class="model"><div class="name"><code>account.payment.register</code></div><div class="role">extended by <code>account_payment</code></div></div>
<div class="model"><div class="name"><code>onboarding.onboarding.step</code></div><div class="role">extended by <code>account_payment</code></div></div>
<div class="model"><div class="name"><code>payment.link.wizard</code></div><div class="role">extended by <code>account_payment</code></div></div>
<div class="model"><div class="name"><code>payment.provider</code></div><div class="role">extended by <code>account_payment</code></div></div>
<div class="model"><div class="name"><code>payment.transaction</code></div><div class="role">extended by <code>account_payment</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>account_payment</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.onboarding` | extends_model_from | `agents/modules/generated/onboarding.yaml` |
| `module.payment` | depends_on, extends_model_from | `agents/modules/generated/payment.yaml` |
| `module.pos_online_payment` | required_by | `agents/modules/generated/pos_online_payment.yaml` |
| `module.sale` | extends_model_from, required_by | `agents/modules/generated/sale.yaml` |
| `module.website_payment` | required_by | `agents/modules/generated/website_payment.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_payment`](../../../agents/modules/generated/account_payment.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_payment)
- Direct dependencies: [`account`](../account/overview.md), [`payment`](../payment/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`pos_online_payment`](../pos_online_payment/overview.md), [`sale`](../sale/overview.md), [`website_payment`](../website_payment/overview.md)
- Impact graph: [`module:account_payment`](../../impact-graph.json)

## Purpose

Enable customers to pay invoices on the portal and post payments when transactions are processed.

## Model relationships

- `payment.refund.wizard`
- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.payment` — defined by [`account`](../account/overview.md)
- Extends `account.payment.method` — defined by [`account`](../account/overview.md)
- Extends `account.payment.method.line` — defined by [`account`](../account/overview.md)
- Extends `account.payment.register` — defined by [`account`](../account/overview.md)
- Extends `onboarding.onboarding.step` — defined by [`onboarding`](../onboarding/overview.md)
- Extends `payment.link.wizard` — defined by [`payment`](../payment/overview.md)
- Extends `payment.provider` — defined by [`payment`](../payment/overview.md)
- Extends `payment.transaction` — defined by [`payment`](../payment/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.onboarding`](../../../agents/modules/generated/onboarding.yaml) — extends_model_from
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — depends_on, extends_model_from
- [`module.pos_online_payment`](../../../agents/modules/generated/pos_online_payment.yaml) — required_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from, required_by
- [`module.website_payment`](../../../agents/modules/generated/website_payment.yaml) — required_by

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`onboarding`](../onboarding/overview.md), [`payment`](../payment/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
