---
layout: page
title: "Lunch (lunch)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/lunch/
nav_order: 0
---
# Lunch — `lunch`

**Source:** [`agents/modules/generated/lunch.yaml`](../../agents/modules/generated/lunch.yaml) · **Wiki:** [`knowledge/modules/lunch/overview.md`](../../knowledge/modules/lunch/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>lunch</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Lunch</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/lunch</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/lunch"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Handle lunch orders of your employees

## Direct dependencies

[`mail`](mail.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>lunch.alert</code></div><div class="role">defined by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.cashmove</code></div><div class="role">defined by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.cashmove.report</code></div><div class="role">defined by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.location</code></div><div class="role">defined by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.order</code></div><div class="role">defined by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.product</code></div><div class="role">defined by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.product.category</code></div><div class="role">defined by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.supplier</code></div><div class="role">defined by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.topping</code></div><div class="role">defined by <code>lunch</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>image.mixin</code></div><div class="role">extended by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.alert</code></div><div class="role">extended by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.location</code></div><div class="role">extended by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.order</code></div><div class="role">extended by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.product</code></div><div class="role">extended by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.product.category</code></div><div class="role">extended by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>lunch.supplier</code></div><div class="role">extended by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>lunch</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>lunch</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |

## Full wiki excerpt

- SME owner: [`module.lunch`](../../../agents/modules/generated/lunch.yaml)
- Domain: `human_resources`
- Category: Human Resources/Lunch
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/lunch)
- Direct dependencies: [`mail`](../mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:lunch`](../../impact-graph.json)

## Purpose

Handle lunch orders of your employees

## Model relationships

- `lunch.alert`
- `lunch.cashmove`
- `lunch.cashmove.report`
- `lunch.location`
- `lunch.order`
- `lunch.product`
- `lunch.product.category`
- `lunch.supplier`
- `lunch.topping`
- Extends `image.mixin` — defined by [`base`](../base/overview.md)
- Extends `lunch.alert` — framework/dynamic owner
- Extends `lunch.location` — framework/dynamic owner
- Extends `lunch.order` — framework/dynamic owner
- Extends `lunch.product` — framework/dynamic owner
- Extends `lunch.product.category` — framework/dynamic owner
- Extends `lunch.supplier` — framework/dynamic owner
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
