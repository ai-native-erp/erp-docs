---
layout: page
title: "Task Logs (hr_timesheet)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_timesheet/
nav_order: 0
---
# Task Logs — `hr_timesheet`

**Source:** [`agents/modules/generated/hr_timesheet.yaml`](../../agents/modules/generated/hr_timesheet.yaml) · **Wiki:** [`knowledge/modules/hr_timesheet/overview.md`](../../knowledge/modules/hr_timesheet/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_timesheet</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Task Logs</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_timesheet</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_timesheet"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Track employee time on tasks

## Direct dependencies

[`analytic`](analytic.md), [`hr`](hr.md), [`hr_hourly_cost`](hr_hourly_cost.md), [`project`](project.md), [`uom`](uom.md)

## Reverse dependencies (modules that depend on this)

[`hr_timesheet_attendance`](hr_timesheet_attendance.md), [`project_timesheet_holidays`](project_timesheet_holidays.md), [`sale_timesheet`](sale_timesheet.md), [`spreadsheet_dashboard_hr_timesheet`](spreadsheet_dashboard_hr_timesheet.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.employee.delete.wizard</code></div><div class="role">defined by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>project.task</code></div><div class="role">defined by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>timesheets.analysis.report</code></div><div class="role">defined by <code>hr_timesheet</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.analytic.line</code></div><div class="role">extended by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>ir.ui.menu</code></div><div class="role">extended by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>project.collaborator</code></div><div class="role">extended by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>project.project</code></div><div class="role">extended by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>project.task</code></div><div class="role">extended by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>project.update</code></div><div class="role">extended by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>report.project.task.user</code></div><div class="role">extended by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>hr_timesheet</code></div></div>
<div class="model"><div class="name"><code>uom.uom</code></div><div class="role">extended by <code>hr_timesheet</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.analytic` | depends_on, extends_model_from | `agents/modules/generated/analytic.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.hr_hourly_cost` | depends_on | `agents/modules/generated/hr_hourly_cost.yaml` |
| `module.hr_timesheet_attendance` | required_by | `agents/modules/generated/hr_timesheet_attendance.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml)
- Domain: `human_resources`
- Category: Services/Timesheets
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_timesheet)
- Direct dependencies: [`analytic`](../analytic/overview.md), [`hr`](../hr/overview.md), [`hr_hourly_cost`](../hr_hourly_cost/overview.md), [`project`](../project/overview.md), [`uom`](../uom/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_timesheet_attendance`](../hr_timesheet_attendance/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`spreadsheet_dashboard_hr_timesheet`](../spreadsheet_dashboard_hr_timesheet/overview.md)
- Impact graph: [`module:hr_timesheet`](../../impact-graph.json)

## Purpose

Track employee time on tasks

## Model relationships

- `hr.employee.delete.wizard`
- `project.task` — extended by [`project`](../project/overview.md), [`project_sms`](../project_sms/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`project_todo`](../project_todo/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md)
- `timesheets.analysis.report` — extended by [`sale_timesheet`](../sale_timesheet/overview.md)
- Extends `account.analytic.line` — defined by [`analytic`](../analytic/overview.md)
- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `ir.ui.menu` — defined by [`base`](../base/overview.md)
- Extends `project.collaborator` — defined by [`project`](../project/overview.md)
- Extends `project.project` — defined by [`project`](../project/overview.md)
- Extends `project.task` — defined by [`project`](../project/overview.md)
- Extends `project.update` — defined by [`project`](../project/overview.md)
- Extends `report.project.task.user` — defined by [`project`](../project/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `uom.uom` — defined by [`uom`](../uom/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.hr_hourly_cost`](../../../agents/modules/generated/hr_hourly_cost.yaml) — depends_on
- [`module.hr_timesheet_attendance`](../../../agents/modules/generated/hr_timesheet_attendance.yaml) — required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.project`](../../../agents/modules/generated/project.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.project_sms`](../../../agents/modules/generated/project_sms.yaml) — model_extended_by
- [`module.project_timesheet_holidays`](../../../agents/modules/generated/project_timesheet_holidays.yaml) — model_extended_by, required_by
- [`module.project_todo`](../../../agents/modules/generated/project_todo.yaml) — model_extended_by
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — model_extended_by
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — model_extended_by, required_by
- [`module.spreadsheet_dashboard_hr_timesheet`](../../../agents/modules/generated/spreadsheet_dashboard_hr_timesheet.yaml) — required_by
- [`module.uom`](../../../agents/modules/generated/uom.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`project`](../project/overview.md), [`project_sms`](../project_sms/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`project_todo`](../project_todo/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`analytic`](../analytic/overview.md), [`base`](../base/overview.md), [`hr`](../hr/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`project`](../project/overview.md), [`uom`](../uom/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
