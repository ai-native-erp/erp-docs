---
layout: page
title: "HR Gamification (hr_gamification)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_gamification/
nav_order: 0
---
# HR Gamification — `hr_gamification`

**Source:** [`agents/modules/generated/hr_gamification.yaml`](../../agents/modules/generated/hr_gamification.yaml) · **Wiki:** [`knowledge/modules/hr_gamification/overview.md`](../../knowledge/modules/hr_gamification/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_gamification</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">HR Gamification</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_gamification</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_gamification"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`gamification`](gamification.md), [`hr`](hr.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>gamification.badge</code></div><div class="role">extended by <code>hr_gamification</code></div></div>
<div class="model"><div class="name"><code>gamification.badge.user</code></div><div class="role">extended by <code>hr_gamification</code></div></div>
<div class="model"><div class="name"><code>gamification.badge.user.wizard</code></div><div class="role">extended by <code>hr_gamification</code></div></div>
<div class="model"><div class="name"><code>hr.employee.base</code></div><div class="role">extended by <code>hr_gamification</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>hr_gamification</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.gamification` | depends_on, extends_model_from | `agents/modules/generated/gamification.yaml` |
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.website_profile` | extends_model_from | `agents/modules/generated/website_profile.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_gamification`](../../../agents/modules/generated/hr_gamification.yaml)
- Domain: `human_resources`
- Category: Human Resources
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_gamification)
- Direct dependencies: [`gamification`](../gamification/overview.md), [`hr`](../hr/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:hr_gamification`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `gamification.badge` — defined by [`gamification`](../gamification/overview.md), [`website_profile`](../website_profile/overview.md)
- Extends `gamification.badge.user` — defined by [`gamification`](../gamification/overview.md)
- Extends `gamification.badge.user.wizard` — defined by [`gamification`](../gamification/overview.md)
- Extends `hr.employee.base` — defined by [`hr`](../hr/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.gamification`](../../../agents/modules/generated/gamification.yaml) — depends_on, extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.website_profile`](../../../agents/modules/generated/website_profile.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`gamification`](../gamification/overview.md), [`hr`](../hr/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`website_profile`](../website_profile/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
