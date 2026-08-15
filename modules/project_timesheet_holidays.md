---
layout: page
title: "Timesheet when on Time Off (project_timesheet_holidays)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/project_timesheet_holidays/
nav_order: 0
---
# Timesheet when on Time Off — `project_timesheet_holidays`

**Source:** [`agents/modules/generated/project_timesheet_holidays.yaml`](../../agents/modules/generated/project_timesheet_holidays.yaml) · **Wiki:** [`knowledge/modules/project_timesheet_holidays/overview.md`](../../knowledge/modules/project_timesheet_holidays/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>project_timesheet_holidays</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Timesheet when on Time Off</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">projects_services</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/project_timesheet_holidays</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_timesheet_holidays"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Schedule timesheet when on time off

## Direct dependencies

[`hr_holidays`](hr_holidays.md), [`hr_timesheet`](hr_timesheet.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.analytic.line</code></div><div class="role">extended by <code>project_timesheet_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>project_timesheet_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave</code></div><div class="role">extended by <code>project_timesheet_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave.type</code></div><div class="role">extended by <code>project_timesheet_holidays</code></div></div>
<div class="model"><div class="name"><code>project.task</code></div><div class="role">extended by <code>project_timesheet_holidays</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>project_timesheet_holidays</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>project_timesheet_holidays</code></div></div>
<div class="model"><div class="name"><code>resource.calendar.leaves</code></div><div class="role">extended by <code>project_timesheet_holidays</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.analytic` | extends_model_from | `agents/modules/generated/analytic.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.hr` | extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.hr_holidays` | depends_on, extends_model_from | `agents/modules/generated/hr_holidays.yaml` |
| `module.hr_timesheet` | depends_on, extends_model_from | `agents/modules/generated/hr_timesheet.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |

## Full wiki excerpt

- SME owner: [`module.project_timesheet_holidays`](../../../agents/modules/generated/project_timesheet_holidays.yaml)
- Domain: `projects_services`
- Category: Human Resources
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_timesheet_holidays)
- Direct dependencies: [`hr_holidays`](../hr_holidays/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:project_timesheet_holidays`](../../impact-graph.json)

## Purpose

Schedule timesheet when on time off

## Model relationships

- Extends `account.analytic.line` — defined by [`analytic`](../analytic/overview.md)
- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `hr.leave` — defined by [`hr_holidays`](../hr_holidays/overview.md)
- Extends `hr.leave.type` — defined by [`hr_holidays`](../hr_holidays/overview.md)
- Extends `project.task` — defined by [`hr_timesheet`](../hr_timesheet/overview.md), [`project`](../project/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `resource.calendar.leaves` — defined by [`resource`](../resource/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — extends_model_from
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — depends_on, extends_model_from
- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — depends_on, extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.project`](../../../agents/modules/generated/project.yaml) — extends_model_from
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`analytic`](../analytic/overview.md), [`base`](../base/overview.md), [`hr`](../hr/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`project`](../project/overview.md), [`resource`](../resource/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
