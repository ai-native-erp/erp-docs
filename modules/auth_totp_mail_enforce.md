---
layout: page
title: "2FA by mail (auth_totp_mail_enforce)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/auth_totp_mail_enforce/
nav_order: 0
---
# 2FA by mail — `auth_totp_mail_enforce`

**Source:** [`agents/modules/generated/auth_totp_mail_enforce.yaml`](../../agents/modules/generated/auth_totp_mail_enforce.yaml) · **Wiki:** [`knowledge/modules/auth_totp_mail_enforce/overview.md`](../../knowledge/modules/auth_totp_mail_enforce/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>auth_totp_mail_enforce</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">2FA by mail</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/auth_totp_mail_enforce</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/auth_totp_mail_enforce"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`auth_totp`](auth_totp.md), [`mail`](mail.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>auth.totp.rate.limit.log</code></div><div class="role">defined by <code>auth_totp_mail_enforce</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>auth_totp_mail_enforce</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>auth_totp_mail_enforce</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.auth_totp` | depends_on | `agents/modules/generated/auth_totp.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.auth_totp_mail_enforce`](../../../agents/modules/generated/auth_totp_mail_enforce.yaml)
- Domain: `platform_core`
- Category: Extra Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/auth_totp_mail_enforce)
- Direct dependencies: [`auth_totp`](../auth_totp/overview.md), [`mail`](../mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:auth_totp_mail_enforce`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `auth.totp.rate.limit.log`
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.auth_totp`](../../../agents/modules/generated/auth_totp.yaml) — depends_on
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
