---
layout: page
title: "Gamification (gamification)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/gamification/
nav_order: 0
---
# Gamification — `gamification`

**Source:** [`agents/modules/generated/gamification.yaml`](../../agents/modules/generated/gamification.yaml) · **Wiki:** [`knowledge/modules/gamification/overview.md`](../../knowledge/modules/gamification/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>gamification</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Gamification</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/gamification</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/gamification"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`mail`](mail.md)

## Reverse dependencies (modules that depend on this)

[`gamification_sale_crm`](gamification_sale_crm.md), [`hr_gamification`](hr_gamification.md), [`survey`](survey.md), [`website_profile`](website_profile.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>gamification.badge</code></div><div class="role">defined by <code>gamification</code></div></div>
<div class="model"><div class="name"><code>gamification.badge.user</code></div><div class="role">defined by <code>gamification</code></div></div>
<div class="model"><div class="name"><code>gamification.badge.user.wizard</code></div><div class="role">defined by <code>gamification</code></div></div>
<div class="model"><div class="name"><code>gamification.challenge</code></div><div class="role">defined by <code>gamification</code></div></div>
<div class="model"><div class="name"><code>gamification.challenge.line</code></div><div class="role">defined by <code>gamification</code></div></div>
<div class="model"><div class="name"><code>gamification.goal</code></div><div class="role">defined by <code>gamification</code></div></div>
<div class="model"><div class="name"><code>gamification.goal.definition</code></div><div class="role">defined by <code>gamification</code></div></div>
<div class="model"><div class="name"><code>gamification.goal.wizard</code></div><div class="role">defined by <code>gamification</code></div></div>
<div class="model"><div class="name"><code>gamification.karma.rank</code></div><div class="role">defined by <code>gamification</code></div></div>
<div class="model"><div class="name"><code>gamification.karma.tracking</code></div><div class="role">defined by <code>gamification</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>image.mixin</code></div><div class="role">extended by <code>gamification</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>gamification</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>gamification</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.gamification_sale_crm` | required_by | `agents/modules/generated/gamification_sale_crm.yaml` |
| `module.hr_gamification` | model_extended_by, required_by | `agents/modules/generated/hr_gamification.yaml` |
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.survey` | model_extended_by, required_by | `agents/modules/generated/survey.yaml` |
| `module.website_forum` | model_extended_by | `agents/modules/generated/website_forum.yaml` |
| `module.website_profile` | model_extended_by, required_by | `agents/modules/generated/website_profile.yaml` |

## Full wiki excerpt

- SME owner: [`module.gamification`](../../../agents/modules/generated/gamification.yaml)
- Domain: `platform_core`
- Category: Human Resources
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/gamification)
- Direct dependencies: [`mail`](../mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`gamification_sale_crm`](../gamification_sale_crm/overview.md), [`hr_gamification`](../hr_gamification/overview.md), [`survey`](../survey/overview.md), [`website_profile`](../website_profile/overview.md)
- Impact graph: [`module:gamification`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `gamification.badge` — extended by [`hr_gamification`](../hr_gamification/overview.md), [`survey`](../survey/overview.md), [`website_profile`](../website_profile/overview.md)
- `gamification.badge.user` — extended by [`hr_gamification`](../hr_gamification/overview.md)
- `gamification.badge.user.wizard` — extended by [`hr_gamification`](../hr_gamification/overview.md)
- `gamification.challenge` — extended by [`survey`](../survey/overview.md), [`website_forum`](../website_forum/overview.md), [`website_slides`](../website_slides/overview.md)
- `gamification.challenge.line`
- `gamification.goal`
- `gamification.goal.definition`
- `gamification.goal.wizard`
- `gamification.karma.rank`
- `gamification.karma.tracking` — extended by [`website_forum`](../website_forum/overview.md), [`website_slides`](../website_slides/overview.md)
- Extends `image.mixin` — defined by [`base`](../base/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.gamification_sale_crm`](../../../agents/modules/generated/gamification_sale_crm.yaml) — required_by
- [`module.hr_gamification`](../../../agents/modules/generated/hr_gamification.yaml) — model_extended_by, required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.survey`](../../../agents/modules/generated/survey.yaml) — model_extended_by, required_by
- [`module.website_forum`](../../../agents/modules/generated/website_forum.yaml) — model_extended_by
- [`module.website_profile`](../../../agents/modules/generated/website_profile.yaml) — model_extended_by, required_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — model_extended_by

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr_gamification`](../hr_gamification/overview.md), [`survey`](../survey/overview.md), [`website_forum`](../website_forum/overview.md), [`website_profile`](../website_profile/overview.md), [`website_slides`](../website_slides/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
