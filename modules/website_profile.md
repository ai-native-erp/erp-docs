---
layout: page
title: "Website profile (website_profile)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_profile/
nav_order: 0
---
# Website profile — `website_profile`

**Source:** [`agents/modules/generated/website_profile.yaml`](../../agents/modules/generated/website_profile.yaml) · **Wiki:** [`knowledge/modules/website_profile/overview.md`](../../knowledge/modules/website_profile/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_profile</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Website profile</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_profile</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_profile"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Access the website profile of the users

## Direct dependencies

[`gamification`](gamification.md), [`website_partner`](website_partner.md)

## Reverse dependencies (modules that depend on this)

[`website_event_track_quiz`](website_event_track_quiz.md), [`website_forum`](website_forum.md), [`website_slides`](website_slides.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>gamification.badge</code></div><div class="role">defined by <code>website_profile</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>gamification.badge</code></div><div class="role">extended by <code>website_profile</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>website_profile</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_profile</code></div></div>
<div class="model"><div class="name"><code>website.published.mixin</code></div><div class="role">extended by <code>website_profile</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.gamification` | depends_on, extends_model_from | `agents/modules/generated/gamification.yaml` |
| `module.hr_gamification` | model_extended_by | `agents/modules/generated/hr_gamification.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.survey` | model_extended_by | `agents/modules/generated/survey.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_event_track_quiz` | required_by | `agents/modules/generated/website_event_track_quiz.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_profile`](../../../agents/modules/generated/website_profile.yaml)
- Domain: `website_ecommerce`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_profile)
- Direct dependencies: [`gamification`](../gamification/overview.md), [`website_partner`](../website_partner/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_event_track_quiz`](../website_event_track_quiz/overview.md), [`website_forum`](../website_forum/overview.md), [`website_slides`](../website_slides/overview.md)
- Impact graph: [`module:website_profile`](../../impact-graph.json)

## Purpose

Access the website profile of the users

## Model relationships

- `gamification.badge` — extended by [`hr_gamification`](../hr_gamification/overview.md), [`survey`](../survey/overview.md)
- Extends `gamification.badge` — defined by [`gamification`](../gamification/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)
- Extends `website.published.mixin` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.gamification`](../../../agents/modules/generated/gamification.yaml) — depends_on, extends_model_from
- [`module.hr_gamification`](../../../agents/modules/generated/hr_gamification.yaml) — model_extended_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.survey`](../../../agents/modules/generated/survey.yaml) — model_extended_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_event_track_quiz`](../../../agents/modules/generated/website_event_track_quiz.yaml) — required_by
- [`module.website_forum`](../../../agents/modules/generated/website_forum.yaml) — required_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — depends_on
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — required_by

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr_gamification`](../hr_gamification/overview.md), [`survey`](../survey/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`gamification`](../gamification/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
