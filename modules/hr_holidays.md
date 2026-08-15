---
layout: page
title: "Time Off (hr_holidays)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_holidays/
nav_order: 0
---
# Time Off — `hr_holidays`

**Source:** [`agents/modules/generated/hr_holidays.yaml`](../../agents/modules/generated/hr_holidays.yaml) · **Wiki:** [`knowledge/modules/hr_holidays/overview.md`](../../knowledge/modules/hr_holidays/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_holidays</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Time Off</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_holidays</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_holidays"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Allocate PTOs and follow leaves requests

## Direct dependencies

[`calendar`](calendar.md), [`hr`](hr.md), [`resource`](resource.md)

## Reverse dependencies (modules that depend on this)

[`hr_holidays_attendance`](hr_holidays_attendance.md), [`hr_presence`](hr_presence.md), [`hr_work_entry_holidays`](hr_work_entry_holidays.md), [`l10n_fr_hr_holidays`](l10n_fr_hr_holidays.md), [`project_timesheet_holidays`](project_timesheet_holidays.md), [`test_discuss_full`](test_discuss_full.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.holidays.cancel.leave</code></div><div class="role">defined by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.holidays.summary.employee</code></div><div class="role">defined by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave</code></div><div class="role">defined by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave.accrual.level</code></div><div class="role">defined by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave.accrual.plan</code></div><div class="role">defined by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave.allocation</code></div><div class="role">defined by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave.employee.type.report</code></div><div class="role">defined by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave.mandatory.day</code></div><div class="role">defined by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave.report</code></div><div class="role">defined by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave.report.calendar</code></div><div class="role">defined by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave.type</code></div><div class="role">defined by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>report.hr_holidays.report_holidayssummary</code></div><div class="role">defined by <code>hr_holidays</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.department</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.departure.wizard</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.employee.base</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave.allocation</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave.type</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>mail.activity.type</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>mail.message.subtype</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>mail.thread.main.attachment</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>resource.calendar</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
<div class="model"><div class="name"><code>resource.calendar.leaves</code></div><div class="role">extended by <code>hr_holidays</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.calendar` | depends_on | `agents/modules/generated/calendar.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.hr_holidays_attendance` | model_extended_by, required_by | `agents/modules/generated/hr_holidays_attendance.yaml` |
| `module.hr_presence` | required_by | `agents/modules/generated/hr_presence.yaml` |
| `module.hr_work_entry_holidays` | model_extended_by, required_by | `agents/modules/generated/hr_work_entry_holidays.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml)
- Domain: `human_resources`
- Category: Human Resources/Time Off
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_holidays)
- Direct dependencies: [`calendar`](../calendar/overview.md), [`hr`](../hr/overview.md), [`resource`](../resource/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_presence`](../hr_presence/overview.md), [`hr_work_entry_holidays`](../hr_work_entry_holidays/overview.md), [`l10n_fr_hr_holidays`](../l10n_fr_hr_holidays/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`test_discuss_full`](../test_discuss_full/overview.md)
- Impact graph: [`module:hr_holidays`](../../impact-graph.json)

## Purpose

Allocate PTOs and follow leaves requests

## Model relationships

- `hr.holidays.cancel.leave`
- `hr.holidays.summary.employee`
- `hr.leave` — extended by [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_work_entry_holidays`](../hr_work_entry_holidays/overview.md), [`l10n_fr_hr_holidays`](../l10n_fr_hr_holidays/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md)
- `hr.leave.accrual.level` — extended by [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md)
- `hr.leave.accrual.plan`
- `hr.leave.allocation` — extended by [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md)
- `hr.leave.employee.type.report`
- `hr.leave.mandatory.day`
- `hr.leave.report`
- `hr.leave.report.calendar`
- `hr.leave.type` — extended by [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_work_entry_holidays`](../hr_work_entry_holidays/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md)
- `report.hr_holidays.report_holidayssummary`
- Extends `hr.department` — defined by [`hr`](../hr/overview.md)
- Extends `hr.departure.wizard` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee.base` — defined by [`hr`](../hr/overview.md)
- Extends `hr.leave` — framework/dynamic owner
- Extends `hr.leave.allocation` — framework/dynamic owner
- Extends `hr.leave.type` — framework/dynamic owner
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.activity.type` — defined by [`mail`](../mail/overview.md)
- Extends `mail.message.subtype` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.main.attachment` — defined by [`mail`](../mail/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `resource.calendar` — defined by [`resource`](../resource/overview.md)
- Extends `resource.calendar.leaves` — defined by [`resource`](../resource/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — depends_on
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.hr_holidays_attendance`](../../../agents/modules/generated/hr_holidays_attendance.yaml) — model_extended_by, required_by
- [`module.hr_presence`](../../../agents/modules/generated/hr_presence.yaml) — required_by
- [`module.hr_work_entry_holidays`](../../../agents/modules/generated/hr_work_entry_holidays.yaml) — model_extended_by, required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_fr_hr_holidays`](../../../agents/modules/generated/l10n_fr_hr_holidays.yaml) — model_extended_by, required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.project_timesheet_holidays`](../../../agents/modules/generated/project_timesheet_holidays.yaml) — model_extended_by, required_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — depends_on, extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.test_discuss_full`](../../../agents/modules/generated/test_discuss_full.yaml) — required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 6 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_work_entry_holidays`](../hr_work_entry_holidays/overview.md), [`l10n_fr_hr_holidays`](../l10n_fr_hr_holidays/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`hr`](../hr/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`resource`](../resource/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
