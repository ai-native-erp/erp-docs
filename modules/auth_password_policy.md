---
layout: page
title: "Password Policy (auth_password_policy)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/auth_password_policy/
nav_order: 0
---
# Password Policy — `auth_password_policy`

**Source:** [`agents/modules/generated/auth_password_policy.yaml`](../../agents/modules/generated/auth_password_policy.yaml) · **Wiki:** [`knowledge/modules/auth_password_policy/overview.md`](../../knowledge/modules/auth_password_policy/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>auth_password_policy</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Password Policy</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/auth_password_policy</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/auth_password_policy"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Implement basic password policy configuration & check

## Direct dependencies

[`base_setup`](base_setup.md), [`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`auth_password_policy_portal`](auth_password_policy_portal.md), [`auth_password_policy_signup`](auth_password_policy_signup.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>auth_password_policy</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>auth_password_policy</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.auth_password_policy_portal` | required_by | `agents/modules/generated/auth_password_policy_portal.yaml` |
| `module.auth_password_policy_signup` | required_by | `agents/modules/generated/auth_password_policy_signup.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_setup` | depends_on | `agents/modules/generated/base_setup.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |

## Full wiki excerpt

- SME owner: [`module.auth_password_policy`](../../../agents/modules/generated/auth_password_policy.yaml)
- Domain: `platform_core`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/auth_password_policy)
- Direct dependencies: [`base_setup`](../base_setup/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`auth_password_policy_portal`](../auth_password_policy_portal/overview.md), [`auth_password_policy_signup`](../auth_password_policy_signup/overview.md)
- Impact graph: [`module:auth_password_policy`](../../impact-graph.json)

## Purpose

Implement basic password policy configuration & check

## Model relationships

- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.auth_password_policy_portal`](../../../agents/modules/generated/auth_password_policy_portal.yaml) — required_by
- [`module.auth_password_policy_signup`](../../../agents/modules/generated/auth_password_policy_signup.yaml) — required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
