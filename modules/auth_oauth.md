---
layout: page
title: "OAuth2 Authentication (auth_oauth)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/auth_oauth/
nav_order: 0
---
# OAuth2 Authentication — `auth_oauth`

**Source:** [`agents/modules/generated/auth_oauth.yaml`](../../agents/modules/generated/auth_oauth.yaml) · **Wiki:** [`knowledge/modules/auth_oauth/overview.md`](../../knowledge/modules/auth_oauth/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>auth_oauth</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">OAuth2 Authentication</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/auth_oauth</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/auth_oauth"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`auth_signup`](auth_signup.md), [`base`](base.md), [`base_setup`](base_setup.md), [`web`](web.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>auth.oauth.provider</code></div><div class="role">defined by <code>auth_oauth</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.config_parameter</code></div><div class="role">extended by <code>auth_oauth</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>auth_oauth</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>auth_oauth</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.auth_signup` | depends_on | `agents/modules/generated/auth_signup.yaml` |
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_setup` | depends_on | `agents/modules/generated/base_setup.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |

## Full wiki excerpt

- SME owner: [`module.auth_oauth`](../../../agents/modules/generated/auth_oauth.yaml)
- Domain: `platform_core`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/auth_oauth)
- Direct dependencies: [`auth_signup`](../auth_signup/overview.md), [`base`](../base/overview.md), [`base_setup`](../base_setup/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:auth_oauth`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `auth.oauth.provider`
- Extends `ir.config_parameter` — defined by [`base`](../base/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — depends_on
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
