---
layout: page
title: "Recruitment (hr_recruitment)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_recruitment/
nav_order: 0
---
# Recruitment — `hr_recruitment`

**Source:** [`agents/modules/generated/hr_recruitment.yaml`](../../agents/modules/generated/hr_recruitment.yaml) · **Wiki:** [`knowledge/modules/hr_recruitment/overview.md`](../../knowledge/modules/hr_recruitment/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_recruitment</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Recruitment</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_recruitment</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_recruitment"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Track your recruitment pipeline

## Direct dependencies

[`attachment_indexation`](attachment_indexation.md), [`calendar`](calendar.md), [`digest`](digest.md), [`hr`](hr.md), [`utm`](utm.md), [`web_tour`](web_tour.md)

## Reverse dependencies (modules that depend on this)

[`hr_recruitment_skills`](hr_recruitment_skills.md), [`hr_recruitment_sms`](hr_recruitment_sms.md), [`hr_recruitment_survey`](hr_recruitment_survey.md), [`website_hr_recruitment`](website_hr_recruitment.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>applicant.get.refuse.reason</code></div><div class="role">defined by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>applicant.send.mail</code></div><div class="role">defined by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.applicant</code></div><div class="role">defined by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.applicant.category</code></div><div class="role">defined by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.applicant.refuse.reason</code></div><div class="role">defined by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.job</code></div><div class="role">defined by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.recruitment.degree</code></div><div class="role">defined by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.recruitment.source</code></div><div class="role">defined by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.recruitment.stage</code></div><div class="role">defined by <code>hr_recruitment</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>calendar.event</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>digest.digest</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.department</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.job</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>ir.ui.menu</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>mail.alias.mixin</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>mail.composer.mixin</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>mail.thread.blacklist</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>mail.thread.cc</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>mail.thread.main.attachment</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>mail.thread.phone</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>utm.campaign</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>utm.mixin</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>utm.source</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>utm.source.mixin</code></div><div class="role">extended by <code>hr_recruitment</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.attachment_indexation` | depends_on | `agents/modules/generated/attachment_indexation.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.calendar` | depends_on, extends_model_from | `agents/modules/generated/calendar.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.digest` | depends_on, extends_model_from | `agents/modules/generated/digest.yaml` |
| `module.google_calendar` | extends_model_from | `agents/modules/generated/google_calendar.yaml` |
| `module.hr` | depends_on, extends_model_from, model_extended_by | `agents/modules/generated/hr.yaml` |
| `module.hr_recruitment_skills` | model_extended_by, required_by | `agents/modules/generated/hr_recruitment_skills.yaml` |
| `module.hr_recruitment_sms` | required_by | `agents/modules/generated/hr_recruitment_sms.yaml` |
| `module.hr_recruitment_survey` | model_extended_by, required_by | `agents/modules/generated/hr_recruitment_survey.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml)
- Domain: `human_resources`
- Category: Human Resources/Recruitment
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_recruitment)
- Direct dependencies: [`attachment_indexation`](../attachment_indexation/overview.md), [`calendar`](../calendar/overview.md), [`digest`](../digest/overview.md), [`hr`](../hr/overview.md), [`utm`](../utm/overview.md), [`web_tour`](../web_tour/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_recruitment_skills`](../hr_recruitment_skills/overview.md), [`hr_recruitment_sms`](../hr_recruitment_sms/overview.md), [`hr_recruitment_survey`](../hr_recruitment_survey/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md)
- Impact graph: [`module:hr_recruitment`](../../impact-graph.json)

## Purpose

Track your recruitment pipeline

## Model relationships

- `applicant.get.refuse.reason`
- `applicant.send.mail`
- `hr.applicant` — extended by [`hr_recruitment_skills`](../hr_recruitment_skills/overview.md), [`hr_recruitment_survey`](../hr_recruitment_survey/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md)
- `hr.applicant.category`
- `hr.applicant.refuse.reason`
- `hr.job` — extended by [`hr`](../hr/overview.md), [`hr_recruitment_survey`](../hr_recruitment_survey/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md)
- `hr.recruitment.degree`
- `hr.recruitment.source` — extended by [`website_hr_recruitment`](../website_hr_recruitment/overview.md)
- `hr.recruitment.stage`
- Extends `calendar.event` — defined by [`calendar`](../calendar/overview.md), [`google_calendar`](../google_calendar/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md)
- Extends `digest.digest` — defined by [`digest`](../digest/overview.md)
- Extends `hr.department` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `hr.job` — defined by [`hr`](../hr/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md)
- Extends `ir.ui.menu` — defined by [`base`](../base/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.alias.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.composer.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.blacklist` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.cc` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.main.attachment` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.phone` — defined by [`phone_validation`](../phone_validation/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `utm.campaign` — defined by [`utm`](../utm/overview.md)
- Extends `utm.mixin` — defined by [`utm`](../utm/overview.md)
- Extends `utm.source` — defined by [`utm`](../utm/overview.md)
- Extends `utm.source.mixin` — defined by [`utm`](../utm/overview.md)

## Related SME agents

- [`module.attachment_indexation`](../../../agents/modules/generated/attachment_indexation.yaml) — depends_on
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — depends_on, extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — depends_on, extends_model_from
- [`module.google_calendar`](../../../agents/modules/generated/google_calendar.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.hr_recruitment_skills`](../../../agents/modules/generated/hr_recruitment_skills.yaml) — model_extended_by, required_by
- [`module.hr_recruitment_sms`](../../../agents/modules/generated/hr_recruitment_sms.yaml) — required_by
- [`module.hr_recruitment_survey`](../../../agents/modules/generated/hr_recruitment_survey.yaml) — model_extended_by, required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.microsoft_calendar`](../../../agents/modules/generated/microsoft_calendar.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — depends_on, extends_model_from
- [`module.web_tour`](../../../agents/modules/generated/web_tour.yaml) — depends_on
- [`module.website_hr_recruitment`](../../../agents/modules/generated/website_hr_recruitment.yaml) — extends_model_from, model_extended_by, required_by

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr`](../hr/overview.md), [`hr_recruitment_skills`](../hr_recruitment_skills/overview.md), [`hr_recruitment_survey`](../hr_recruitment_survey/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`calendar`](../calendar/overview.md), [`contacts`](../contacts/overview.md), [`digest`](../digest/overview.md), [`google_calendar`](../google_calendar/overview.md), [`hr`](../hr/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md), [`phone_validation`](../phone_validation/overview.md), [`utm`](../utm/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
