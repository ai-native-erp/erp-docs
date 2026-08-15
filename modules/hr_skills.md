---
layout: page
title: "Skills Management (hr_skills)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_skills/
nav_order: 0
---
# Skills Management — `hr_skills`

**Source:** [`agents/modules/generated/hr_skills.yaml`](../../agents/modules/generated/hr_skills.yaml) · **Wiki:** [`knowledge/modules/hr_skills/overview.md`](../../knowledge/modules/hr_skills/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_skills</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Skills Management</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_skills</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_skills"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage skills, knowledge and resume of your employees

## Direct dependencies

[`hr`](hr.md)

## Reverse dependencies (modules that depend on this)

[`hr_recruitment_skills`](hr_recruitment_skills.md), [`hr_skills_slides`](hr_skills_slides.md), [`hr_skills_survey`](hr_skills_survey.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.employee.cv.wizard</code></div><div class="role">defined by <code>hr_skills</code></div></div>
<div class="model"><div class="name"><code>hr.employee.skill</code></div><div class="role">defined by <code>hr_skills</code></div></div>
<div class="model"><div class="name"><code>hr.employee.skill.log</code></div><div class="role">defined by <code>hr_skills</code></div></div>
<div class="model"><div class="name"><code>hr.employee.skill.report</code></div><div class="role">defined by <code>hr_skills</code></div></div>
<div class="model"><div class="name"><code>hr.resume.line</code></div><div class="role">defined by <code>hr_skills</code></div></div>
<div class="model"><div class="name"><code>hr.resume.line.type</code></div><div class="role">defined by <code>hr_skills</code></div></div>
<div class="model"><div class="name"><code>hr.skill</code></div><div class="role">defined by <code>hr_skills</code></div></div>
<div class="model"><div class="name"><code>hr.skill.level</code></div><div class="role">defined by <code>hr_skills</code></div></div>
<div class="model"><div class="name"><code>hr.skill.type</code></div><div class="role">defined by <code>hr_skills</code></div></div>
<div class="model"><div class="name"><code>report.hr_skills.report_employee_cv</code></div><div class="role">defined by <code>hr_skills</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr_skills</code></div></div>
<div class="model"><div class="name"><code>hr.employee.public</code></div><div class="role">extended by <code>hr_skills</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>hr_skills</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.hr_recruitment_skills` | required_by | `agents/modules/generated/hr_recruitment_skills.yaml` |
| `module.hr_skills_slides` | model_extended_by, required_by | `agents/modules/generated/hr_skills_slides.yaml` |
| `module.hr_skills_survey` | model_extended_by, required_by | `agents/modules/generated/hr_skills_survey.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_skills`](../../../agents/modules/generated/hr_skills.yaml)
- Domain: `human_resources`
- Category: Human Resources/Employees
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_skills)
- Direct dependencies: [`hr`](../hr/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_recruitment_skills`](../hr_recruitment_skills/overview.md), [`hr_skills_slides`](../hr_skills_slides/overview.md), [`hr_skills_survey`](../hr_skills_survey/overview.md)
- Impact graph: [`module:hr_skills`](../../impact-graph.json)

## Purpose

Manage skills, knowledge and resume of your employees

## Model relationships

- `hr.employee.cv.wizard`
- `hr.employee.skill`
- `hr.employee.skill.log`
- `hr.employee.skill.report`
- `hr.resume.line` — extended by [`hr_skills_slides`](../hr_skills_slides/overview.md), [`hr_skills_survey`](../hr_skills_survey/overview.md)
- `hr.resume.line.type`
- `hr.skill`
- `hr.skill.level`
- `hr.skill.type`
- `report.hr_skills.report_employee_cv`
- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee.public` — defined by [`hr`](../hr/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.hr_recruitment_skills`](../../../agents/modules/generated/hr_recruitment_skills.yaml) — required_by
- [`module.hr_skills_slides`](../../../agents/modules/generated/hr_skills_slides.yaml) — model_extended_by, required_by
- [`module.hr_skills_survey`](../../../agents/modules/generated/hr_skills_survey.yaml) — model_extended_by, required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr_skills_slides`](../hr_skills_slides/overview.md), [`hr_skills_survey`](../hr_skills_survey/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`hr`](../hr/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
