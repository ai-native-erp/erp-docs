---
layout: page
title: "Employees (hr)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr/
nav_order: 0
---
# Employees — `hr`

**Source:** [`agents/modules/generated/hr.yaml`](../../agents/modules/generated/hr.yaml) · **Wiki:** [`knowledge/modules/hr/overview.md`](../../knowledge/modules/hr/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Employees</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Centralize employee information

## Direct dependencies

[`base_setup`](base_setup.md), [`mail`](mail.md), [`phone_validation`](phone_validation.md), [`resource`](resource.md), [`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`hr_attendance`](hr_attendance.md), [`hr_contract`](hr_contract.md), [`hr_expense`](hr_expense.md), [`hr_fleet`](hr_fleet.md), [`hr_gamification`](hr_gamification.md), [`hr_holidays`](hr_holidays.md), [`hr_homeworking`](hr_homeworking.md), [`hr_hourly_cost`](hr_hourly_cost.md), [`hr_livechat`](hr_livechat.md), [`hr_maintenance`](hr_maintenance.md), [`hr_org_chart`](hr_org_chart.md), [`hr_presence`](hr_presence.md), [`hr_recruitment`](hr_recruitment.md), [`hr_skills`](hr_skills.md), [`hr_timesheet`](hr_timesheet.md), [`hr_work_entry`](hr_work_entry.md), [`l10n_mx_hr`](l10n_mx_hr.md), [`mail_bot_hr`](mail_bot_hr.md), [`pos_hr`](pos_hr.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.contract.type</code></div><div class="role">defined by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.department</code></div><div class="role">defined by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.departure.reason</code></div><div class="role">defined by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.departure.wizard</code></div><div class="role">defined by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">defined by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.employee.base</code></div><div class="role">defined by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.employee.category</code></div><div class="role">defined by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.employee.public</code></div><div class="role">defined by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.job</code></div><div class="role">defined by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.work.location</code></div><div class="role">defined by <code>hr</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>avatar.mixin</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>base</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>discuss.channel</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.department</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.employee.base</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.employee.category</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.job</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>hr.work.location</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>ir.ui.menu</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>mail.activity.plan</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>mail.activity.plan.template</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>mail.activity.schedule</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>mail.alias</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>mail.thread.main.attachment</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>res.partner.bank</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>resource.mixin</code></div><div class="role">extended by <code>hr</code></div></div>
<div class="model"><div class="name"><code>resource.resource</code></div><div class="role">extended by <code>hr</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_setup` | depends_on | `agents/modules/generated/base_setup.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.hr_attendance` | model_extended_by, required_by | `agents/modules/generated/hr_attendance.yaml` |
| `module.hr_contract` | model_extended_by, required_by | `agents/modules/generated/hr_contract.yaml` |
| `module.hr_expense` | model_extended_by, required_by | `agents/modules/generated/hr_expense.yaml` |
| `module.hr_fleet` | model_extended_by, required_by | `agents/modules/generated/hr_fleet.yaml` |
| `module.hr_gamification` | model_extended_by, required_by | `agents/modules/generated/hr_gamification.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr`](../../../agents/modules/generated/hr.yaml)
- Domain: `human_resources`
- Category: Human Resources/Employees
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr)
- Direct dependencies: [`base_setup`](../base_setup/overview.md), [`mail`](../mail/overview.md), [`phone_validation`](../phone_validation/overview.md), [`resource`](../resource/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_gamification`](../hr_gamification/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_hourly_cost`](../hr_hourly_cost/overview.md), [`hr_livechat`](../hr_livechat/overview.md), [`hr_maintenance`](../hr_maintenance/overview.md), [`hr_org_chart`](../hr_org_chart/overview.md), [`hr_presence`](../hr_presence/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_skills`](../hr_skills/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`hr_work_entry`](../hr_work_entry/overview.md), [`l10n_mx_hr`](../l10n_mx_hr/overview.md), [`mail_bot_hr`](../mail_bot_hr/overview.md), [`pos_hr`](../pos_hr/overview.md)
- Impact graph: [`module:hr`](../../impact-graph.json)

## Purpose

Centralize employee information

## Model relationships

- `hr.contract.type`
- `hr.department` — extended by [`hr_expense`](../hr_expense/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md)
- `hr.departure.reason`
- `hr.departure.wizard` — extended by [`hr_contract`](../hr_contract/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_holidays`](../hr_holidays/overview.md)
- `hr.employee` — extended by [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_hourly_cost`](../hr_hourly_cost/overview.md), [`hr_maintenance`](../hr_maintenance/overview.md), [`hr_org_chart`](../hr_org_chart/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_skills`](../hr_skills/overview.md), [`hr_skills_slides`](../hr_skills_slides/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`hr_work_entry`](../hr_work_entry/overview.md), [`hr_work_entry_contract`](../hr_work_entry_contract/overview.md), [`l10n_mx_hr`](../l10n_mx_hr/overview.md), [`pos_hr`](../pos_hr/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md)
- `hr.employee.base` — extended by [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_gamification`](../hr_gamification/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_org_chart`](../hr_org_chart/overview.md), [`hr_presence`](../hr_presence/overview.md), [`hr_work_entry_holidays`](../hr_work_entry_holidays/overview.md)
- `hr.employee.category`
- `hr.employee.public` — extended by [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_org_chart`](../hr_org_chart/overview.md), [`hr_skills`](../hr_skills/overview.md)
- `hr.job` — extended by [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_recruitment_survey`](../hr_recruitment_survey/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md)
- `hr.work.location` — extended by [`hr_homeworking`](../hr_homeworking/overview.md)
- Extends `avatar.mixin` — defined by [`base`](../base/overview.md)
- Extends `base` — defined by [`base`](../base/overview.md)
- Extends `discuss.channel` — defined by [`im_livechat`](../im_livechat/overview.md), [`mail`](../mail/overview.md)
- Extends `hr.department` — framework/dynamic owner
- Extends `hr.employee` — framework/dynamic owner
- Extends `hr.employee.base` — framework/dynamic owner
- Extends `hr.employee.category` — framework/dynamic owner
- Extends `hr.job` — defined by [`hr_recruitment`](../hr_recruitment/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md)
- Extends `hr.work.location` — framework/dynamic owner
- Extends `ir.ui.menu` — defined by [`base`](../base/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.activity.plan` — defined by [`mail`](../mail/overview.md)
- Extends `mail.activity.plan.template` — defined by [`mail`](../mail/overview.md)
- Extends `mail.activity.schedule` — defined by [`mail`](../mail/overview.md)
- Extends `mail.alias` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.main.attachment` — defined by [`mail`](../mail/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.partner.bank` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `resource.mixin` — defined by [`resource`](../resource/overview.md)
- Extends `resource.resource` — defined by [`resource`](../resource/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.hr_attendance`](../../../agents/modules/generated/hr_attendance.yaml) — model_extended_by, required_by
- [`module.hr_contract`](../../../agents/modules/generated/hr_contract.yaml) — model_extended_by, required_by
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — model_extended_by, required_by
- [`module.hr_fleet`](../../../agents/modules/generated/hr_fleet.yaml) — model_extended_by, required_by
- [`module.hr_gamification`](../../../agents/modules/generated/hr_gamification.yaml) — model_extended_by, required_by
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — model_extended_by, required_by
- [`module.hr_homeworking`](../../../agents/modules/generated/hr_homeworking.yaml) — model_extended_by, required_by
- [`module.hr_hourly_cost`](../../../agents/modules/generated/hr_hourly_cost.yaml) — model_extended_by, required_by
- [`module.hr_livechat`](../../../agents/modules/generated/hr_livechat.yaml) — required_by
- [`module.hr_maintenance`](../../../agents/modules/generated/hr_maintenance.yaml) — model_extended_by, required_by
- [`module.hr_org_chart`](../../../agents/modules/generated/hr_org_chart.yaml) — model_extended_by, required_by
- [`module.hr_presence`](../../../agents/modules/generated/hr_presence.yaml) — model_extended_by, required_by
- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — extends_model_from, model_extended_by, required_by
- [`module.hr_recruitment_survey`](../../../agents/modules/generated/hr_recruitment_survey.yaml) — model_extended_by
- [`module.hr_skills`](../../../agents/modules/generated/hr_skills.yaml) — model_extended_by, required_by
- [`module.hr_skills_slides`](../../../agents/modules/generated/hr_skills_slides.yaml) — model_extended_by
- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — model_extended_by, required_by
- [`module.hr_work_entry`](../../../agents/modules/generated/hr_work_entry.yaml) — model_extended_by, required_by
- [`module.hr_work_entry_contract`](../../../agents/modules/generated/hr_work_entry_contract.yaml) — model_extended_by
- [`module.hr_work_entry_holidays`](../../../agents/modules/generated/hr_work_entry_holidays.yaml) — model_extended_by
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — extends_model_from
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_mx_hr`](../../../agents/modules/generated/l10n_mx_hr.yaml) — model_extended_by, required_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mail_bot_hr`](../../../agents/modules/generated/mail_bot_hr.yaml) — required_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — depends_on, extends_model_from
- [`module.pos_hr`](../../../agents/modules/generated/pos_hr.yaml) — model_extended_by, required_by
- [`module.project_timesheet_holidays`](../../../agents/modules/generated/project_timesheet_holidays.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — depends_on, extends_model_from
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_hr_recruitment`](../../../agents/modules/generated/website_hr_recruitment.yaml) — extends_model_from, model_extended_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 19 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_gamification`](../hr_gamification/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_hourly_cost`](../hr_hourly_cost/overview.md), [`hr_maintenance`](../hr_maintenance/overview.md), [`hr_org_chart`](../hr_org_chart/overview.md), [`hr_presence`](../hr_presence/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_recruitment_survey`](../hr_recruitment_survey/overview.md), [`hr_skills`](../hr_skills/overview.md), [`hr_skills_slides`](../hr_skills_slides/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`hr_work_entry`](../hr_work_entry/overview.md), [`hr_work_entry_contract`](../hr_work_entry_contract/overview.md), [`hr_work_entry_holidays`](../hr_work_entry_holidays/overview.md), [`l10n_mx_hr`](../l10n_mx_hr/overview.md), [`pos_hr`](../pos_hr/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`resource`](../resource/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
