---
layout: page
title: "Website Payment (website_payment)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_payment/
nav_order: 0
---
# Website Payment — `website_payment`

**Source:** [`agents/modules/generated/website_payment.yaml`](../../agents/modules/generated/website_payment.yaml) · **Wiki:** [`knowledge/modules/website_payment/overview.md`](../../knowledge/modules/website_payment/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_payment</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Website Payment</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_payment</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_payment"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Payment integration with website

## Direct dependencies

[`account_payment`](account_payment.md), [`portal`](portal.md), [`website`](website.md)

## Reverse dependencies (modules that depend on this)

[`website_payment_authorize`](website_payment_authorize.md), [`website_sale`](website_sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.payment</code></div><div class="role">extended by <code>website_payment</code></div></div>
<div class="model"><div class="name"><code>payment.provider</code></div><div class="role">extended by <code>website_payment</code></div></div>
<div class="model"><div class="name"><code>payment.transaction</code></div><div class="role">extended by <code>website_payment</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website_payment</code></div></div>
<div class="model"><div class="name"><code>res.country</code></div><div class="role">extended by <code>website_payment</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_payment` | depends_on | `agents/modules/generated/account_payment.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.payment` | extends_model_from | `agents/modules/generated/payment.yaml` |
| `module.portal` | depends_on | `agents/modules/generated/portal.yaml` |
| `module.website` | depends_on | `agents/modules/generated/website.yaml` |
| `module.website_payment_authorize` | required_by | `agents/modules/generated/website_payment_authorize.yaml` |
| `module.website_sale` | required_by | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_payment`](../../../agents/modules/generated/website_payment.yaml)
- Domain: `website_ecommerce`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_payment)
- Direct dependencies: [`account_payment`](../account_payment/overview.md), [`portal`](../portal/overview.md), [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_payment_authorize`](../website_payment_authorize/overview.md), [`website_sale`](../website_sale/overview.md)
- Impact graph: [`module:website_payment`](../../impact-graph.json)

## Purpose

Payment integration with website

## Model relationships

- Extends `account.payment` — defined by [`account`](../account/overview.md)
- Extends `payment.provider` — defined by [`payment`](../payment/overview.md)
- Extends `payment.transaction` — defined by [`payment`](../payment/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.country` — defined by [`base`](../base/overview.md), [`l10n_cl`](../l10n_cl/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_payment`](../../../agents/modules/generated/account_payment.yaml) — depends_on
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — extends_model_from
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on
- [`module.website_payment_authorize`](../../../agents/modules/generated/website_payment_authorize.yaml) — required_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`payment`](../payment/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
