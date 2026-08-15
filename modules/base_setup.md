---
layout: page
title: "Initial Setup Tools (base_setup)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/base_setup/
nav_order: 0
---
# Initial Setup Tools — `base_setup`

**Source:** [`agents/modules/generated/base_setup.yaml`](../../agents/modules/generated/base_setup.yaml) · **Wiki:** [`knowledge/modules/base_setup/overview.md`](../../knowledge/modules/base_setup/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base_setup</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Initial Setup Tools</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/base_setup</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base_setup"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md), [`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`account`](account.md), [`auth_ldap`](auth_ldap.md), [`auth_oauth`](auth_oauth.md), [`auth_password_policy`](auth_password_policy.md), [`auth_signup`](auth_signup.md), [`base_geolocalize`](base_geolocalize.md), [`crm`](crm.md), [`event`](event.md), [`google_account`](google_account.md), [`google_recaptcha`](google_recaptcha.md), [`hr`](hr.md), [`iap`](iap.md), [`mail`](mail.md), [`microsoft_account`](microsoft_account.md), [`project`](project.md), [`web_unsplash`](web_unsplash.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>kpi.provider</code></div><div class="role">defined by <code>base_setup</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>base_setup</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>base_setup</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>base_setup</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | model_extended_by, required_by | `agents/modules/generated/account.yaml` |
| `module.auth_ldap` | required_by | `agents/modules/generated/auth_ldap.yaml` |
| `module.auth_oauth` | required_by | `agents/modules/generated/auth_oauth.yaml` |
| `module.auth_password_policy` | required_by | `agents/modules/generated/auth_password_policy.yaml` |
| `module.auth_signup` | required_by | `agents/modules/generated/auth_signup.yaml` |
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_geolocalize` | required_by | `agents/modules/generated/base_geolocalize.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | required_by | `agents/modules/generated/crm.yaml` |
| `module.event` | required_by | `agents/modules/generated/event.yaml` |

## Full wiki excerpt

- SME owner: [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base_setup)
- Direct dependencies: [`base`](../base/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`account`](../account/overview.md), [`auth_ldap`](../auth_ldap/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`auth_password_policy`](../auth_password_policy/overview.md), [`auth_signup`](../auth_signup/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`crm`](../crm/overview.md), [`event`](../event/overview.md), [`google_account`](../google_account/overview.md), [`google_recaptcha`](../google_recaptcha/overview.md), [`hr`](../hr/overview.md), [`iap`](../iap/overview.md), [`mail`](../mail/overview.md), [`microsoft_account`](../microsoft_account/overview.md), [`project`](../project/overview.md), [`web_unsplash`](../web_unsplash/overview.md)
- Impact graph: [`module:base_setup`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `kpi.provider` — extended by [`account`](../account/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — model_extended_by, required_by
- [`module.auth_ldap`](../../../agents/modules/generated/auth_ldap.yaml) — required_by
- [`module.auth_oauth`](../../../agents/modules/generated/auth_oauth.yaml) — required_by
- [`module.auth_password_policy`](../../../agents/modules/generated/auth_password_policy.yaml) — required_by
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.base_geolocalize`](../../../agents/modules/generated/base_geolocalize.yaml) — required_by
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — required_by
- [`module.event`](../../../agents/modules/generated/event.yaml) — required_by
- [`module.google_account`](../../../agents/modules/generated/google_account.yaml) — required_by
- [`module.google_recaptcha`](../../../agents/modules/generated/google_recaptcha.yaml) — required_by
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — required_by
- [`module.iap`](../../../agents/modules/generated/iap.yaml) — required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from, required_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.microsoft_account`](../../../agents/modules/generated/microsoft_account.yaml) — required_by
- [`module.project`](../../../agents/modules/generated/project.yaml) — required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on
- [`module.web_unsplash`](../../../agents/modules/generated/web_unsplash.yaml) — required_by

## Regression impact checklist

- Review 16 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
