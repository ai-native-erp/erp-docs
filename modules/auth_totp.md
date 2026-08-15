---
layout: page
title: "Two-Factor Authentication (TOTP) (auth_totp)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/auth_totp/
nav_order: 0
---
# Two-Factor Authentication (TOTP) — `auth_totp`

**Source:** [`agents/modules/generated/auth_totp.yaml`](../../agents/modules/generated/auth_totp.yaml) · **Wiki:** [`knowledge/modules/auth_totp/overview.md`](../../knowledge/modules/auth_totp/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>auth_totp</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Two-Factor Authentication (TOTP)</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/auth_totp</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/auth_totp"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`auth_totp_mail`](auth_totp_mail.md), [`auth_totp_mail_enforce`](auth_totp_mail_enforce.md), [`auth_totp_portal`](auth_totp_portal.md), [`test_apikeys`](test_apikeys.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>auth_totp.device</code></div><div class="role">defined by <code>auth_totp</code></div></div>
<div class="model"><div class="name"><code>auth_totp.wizard</code></div><div class="role">defined by <code>auth_totp</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>auth_totp</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>auth_totp</code></div></div>
<div class="model"><div class="name"><code>res.users.apikeys</code></div><div class="role">extended by <code>auth_totp</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.auth_totp_mail` | model_extended_by, required_by | `agents/modules/generated/auth_totp_mail.yaml` |
| `module.auth_totp_mail_enforce` | required_by | `agents/modules/generated/auth_totp_mail_enforce.yaml` |
| `module.auth_totp_portal` | required_by | `agents/modules/generated/auth_totp_portal.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.test_apikeys` | required_by | `agents/modules/generated/test_apikeys.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |

## Full wiki excerpt

- SME owner: [`module.auth_totp`](../../../agents/modules/generated/auth_totp.yaml)
- Domain: `platform_core`
- Category: Extra Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/auth_totp)
- Direct dependencies: [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`auth_totp_mail`](../auth_totp_mail/overview.md), [`auth_totp_mail_enforce`](../auth_totp_mail_enforce/overview.md), [`auth_totp_portal`](../auth_totp_portal/overview.md), [`test_apikeys`](../test_apikeys/overview.md)
- Impact graph: [`module:auth_totp`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `auth_totp.device` — extended by [`auth_totp_mail`](../auth_totp_mail/overview.md)
- `auth_totp.wizard`
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `res.users.apikeys` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.auth_totp_mail`](../../../agents/modules/generated/auth_totp_mail.yaml) — model_extended_by, required_by
- [`module.auth_totp_mail_enforce`](../../../agents/modules/generated/auth_totp_mail_enforce.yaml) — required_by
- [`module.auth_totp_portal`](../../../agents/modules/generated/auth_totp_portal.yaml) — required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.test_apikeys`](../../../agents/modules/generated/test_apikeys.yaml) — required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`auth_totp_mail`](../auth_totp_mail/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
