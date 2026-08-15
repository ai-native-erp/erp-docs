---
layout: page
title: "Resource (resource)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/resource/
nav_order: 0
---
# Resource — `resource`

**Source:** [`agents/modules/generated/resource.yaml`](../../agents/modules/generated/resource.yaml) · **Wiki:** [`knowledge/modules/resource/overview.md`](../../knowledge/modules/resource/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>resource</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Resource</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/resource</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/resource"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md), [`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`base_automation`](base_automation.md), [`crm`](crm.md), [`digest`](digest.md), [`hr`](hr.md), [`hr_holidays`](hr_holidays.md), [`mrp`](mrp.md), [`project`](project.md), [`test_resource`](test_resource.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>resource.calendar</code></div><div class="role">defined by <code>resource</code></div></div>
<div class="model"><div class="name"><code>resource.calendar.attendance</code></div><div class="role">defined by <code>resource</code></div></div>
<div class="model"><div class="name"><code>resource.calendar.leaves</code></div><div class="role">defined by <code>resource</code></div></div>
<div class="model"><div class="name"><code>resource.mixin</code></div><div class="role">defined by <code>resource</code></div></div>
<div class="model"><div class="name"><code>resource.resource</code></div><div class="role">defined by <code>resource</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>resource</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>resource</code></div></div>
<div class="model"><div class="name"><code>resource.calendar</code></div><div class="role">extended by <code>resource</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_automation` | required_by | `agents/modules/generated/base_automation.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | required_by | `agents/modules/generated/crm.yaml` |
| `module.digest` | required_by | `agents/modules/generated/digest.yaml` |
| `module.hr` | model_extended_by, required_by | `agents/modules/generated/hr.yaml` |
| `module.hr_attendance` | model_extended_by | `agents/modules/generated/hr_attendance.yaml` |
| `module.hr_contract` | model_extended_by | `agents/modules/generated/hr_contract.yaml` |
| `module.hr_holidays` | model_extended_by, required_by | `agents/modules/generated/hr_holidays.yaml` |

## Full wiki excerpt

- SME owner: [`module.resource`](../../../agents/modules/generated/resource.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/resource)
- Direct dependencies: [`base`](../base/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`base_automation`](../base_automation/overview.md), [`crm`](../crm/overview.md), [`digest`](../digest/overview.md), [`hr`](../hr/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`mrp`](../mrp/overview.md), [`project`](../project/overview.md), [`test_resource`](../test_resource/overview.md)
- Impact graph: [`module:resource`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `resource.calendar` — extended by [`hr_contract`](../hr_contract/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_work_entry_contract`](../hr_work_entry_contract/overview.md), [`l10n_fr_hr_holidays`](../l10n_fr_hr_holidays/overview.md)
- `resource.calendar.attendance` — extended by [`hr_work_entry`](../hr_work_entry/overview.md)
- `resource.calendar.leaves` — extended by [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_work_entry`](../hr_work_entry/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md)
- `resource.mixin` — extended by [`hr`](../hr/overview.md), [`mrp`](../mrp/overview.md), [`test_resource`](../test_resource/overview.md)
- `resource.resource` — extended by [`hr`](../hr/overview.md), [`hr_contract`](../hr_contract/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `resource.calendar` — framework/dynamic owner

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.base_automation`](../../../agents/modules/generated/base_automation.yaml) — required_by
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — required_by
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — required_by
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — model_extended_by, required_by
- [`module.hr_attendance`](../../../agents/modules/generated/hr_attendance.yaml) — model_extended_by
- [`module.hr_contract`](../../../agents/modules/generated/hr_contract.yaml) — model_extended_by
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — model_extended_by, required_by
- [`module.hr_work_entry`](../../../agents/modules/generated/hr_work_entry.yaml) — model_extended_by
- [`module.hr_work_entry_contract`](../../../agents/modules/generated/hr_work_entry_contract.yaml) — model_extended_by
- [`module.l10n_fr_hr_holidays`](../../../agents/modules/generated/l10n_fr_hr_holidays.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — model_extended_by, required_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.project`](../../../agents/modules/generated/project.yaml) — required_by
- [`module.project_timesheet_holidays`](../../../agents/modules/generated/project_timesheet_holidays.yaml) — model_extended_by
- [`module.test_resource`](../../../agents/modules/generated/test_resource.yaml) — model_extended_by, required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 8 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_work_entry`](../hr_work_entry/overview.md), [`hr_work_entry_contract`](../hr_work_entry_contract/overview.md), [`l10n_fr_hr_holidays`](../l10n_fr_hr_holidays/overview.md), [`mrp`](../mrp/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`test_resource`](../test_resource/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
