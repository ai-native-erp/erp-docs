---
layout: page
title: "Mail Tests (Full) (test_mail_full)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_mail_full/
nav_order: 0
---
# Mail Tests (Full) — `test_mail_full`

**Source:** [`agents/modules/generated/test_mail_full.yaml`](../../agents/modules/generated/test_mail_full.yaml) · **Wiki:** [`knowledge/modules/test_mail_full/overview.md`](../../knowledge/modules/test_mail_full/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_mail_full</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Mail Tests (Full)</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_mail_full</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_mail_full"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Mail Tests: performances and tests specific to mail with all sub-modules

## Direct dependencies

[`mail`](mail.md), [`mail_bot`](mail_bot.md), [`mass_mailing`](mass_mailing.md), [`mass_mailing_sms`](mass_mailing_sms.md), [`phone_validation`](phone_validation.md), [`portal`](portal.md), [`rating`](rating.md), [`sms`](sms.md), [`test_mail`](test_mail.md), [`test_mail_sms`](test_mail_sms.md), [`test_mass_mailing`](test_mass_mailing.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.test.portal</code></div><div class="role">defined by <code>test_mail_full</code></div></div>
<div class="model"><div class="name"><code>mail.test.portal.no.partner</code></div><div class="role">defined by <code>test_mail_full</code></div></div>
<div class="model"><div class="name"><code>mail.test.portal.public.access.action</code></div><div class="role">defined by <code>test_mail_full</code></div></div>
<div class="model"><div class="name"><code>mail.test.rating</code></div><div class="role">defined by <code>test_mail_full</code></div></div>
<div class="model"><div class="name"><code>mail.test.rating.thread</code></div><div class="role">defined by <code>test_mail_full</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>test_mail_full</code></div></div>
<div class="model"><div class="name"><code>mail.test.portal</code></div><div class="role">extended by <code>test_mail_full</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>test_mail_full</code></div></div>
<div class="model"><div class="name"><code>portal.mixin</code></div><div class="role">extended by <code>test_mail_full</code></div></div>
<div class="model"><div class="name"><code>rating.mixin</code></div><div class="role">extended by <code>test_mail_full</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mail_bot` | depends_on | `agents/modules/generated/mail_bot.yaml` |
| `module.mass_mailing` | depends_on | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | depends_on | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.phone_validation` | depends_on | `agents/modules/generated/phone_validation.yaml` |
| `module.portal` | depends_on, extends_model_from | `agents/modules/generated/portal.yaml` |
| `module.rating` | depends_on, extends_model_from | `agents/modules/generated/rating.yaml` |
| `module.sms` | depends_on | `agents/modules/generated/sms.yaml` |
| `module.test_mail` | depends_on | `agents/modules/generated/test_mail.yaml` |
| `module.test_mail_sms` | depends_on | `agents/modules/generated/test_mail_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_mail_full`](../../../agents/modules/generated/test_mail_full.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_mail_full)
- Direct dependencies: [`mail`](../mail/overview.md), [`mail_bot`](../mail_bot/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`phone_validation`](../phone_validation/overview.md), [`portal`](../portal/overview.md), [`rating`](../rating/overview.md), [`sms`](../sms/overview.md), [`test_mail`](../test_mail/overview.md), [`test_mail_sms`](../test_mail_sms/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_mail_full`](../../impact-graph.json)

## Purpose

Mail Tests: performances and tests specific to mail with all sub-modules

## Model relationships

- `mail.test.portal`
- `mail.test.portal.no.partner`
- `mail.test.portal.public.access.action`
- `mail.test.rating`
- `mail.test.rating.thread`
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.test.portal` — framework/dynamic owner
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `portal.mixin` — defined by [`portal`](../portal/overview.md)
- Extends `rating.mixin` — defined by [`rating`](../rating/overview.md)

## Related SME agents

- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mail_bot`](../../../agents/modules/generated/mail_bot.yaml) — depends_on
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — depends_on
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — depends_on
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — depends_on
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on, extends_model_from
- [`module.rating`](../../../agents/modules/generated/rating.yaml) — depends_on, extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on
- [`module.test_mail`](../../../agents/modules/generated/test_mail.yaml) — depends_on
- [`module.test_mail_sms`](../../../agents/modules/generated/test_mail_sms.yaml) — depends_on
- [`module.test_mass_mailing`](../../../agents/modules/generated/test_mass_mailing.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mail`](../mail/overview.md), [`portal`](../portal/overview.md), [`rating`](../rating/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
