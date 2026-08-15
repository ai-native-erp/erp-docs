---
layout: page
title: "Timesheets/attendances reporting (hr_timesheet_attendance)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_timesheet_attendance/
nav_order: 0
---
# Timesheets/attendances reporting — `hr_timesheet_attendance`

**Source:** [`agents/modules/generated/hr_timesheet_attendance.yaml`](../../agents/modules/generated/hr_timesheet_attendance.yaml) · **Wiki:** [`knowledge/modules/hr_timesheet_attendance/overview.md`](../../knowledge/modules/hr_timesheet_attendance/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_timesheet_attendance</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Timesheets/attendances reporting</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_timesheet_attendance</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_timesheet_attendance"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`hr_attendance`](hr_attendance.md), [`hr_timesheet`](hr_timesheet.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.timesheet.attendance.report</code></div><div class="role">defined by <code>hr_timesheet_attendance</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.ui.menu</code></div><div class="role">extended by <code>hr_timesheet_attendance</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.hr_attendance` | depends_on | `agents/modules/generated/hr_attendance.yaml` |
| `module.hr_timesheet` | depends_on | `agents/modules/generated/hr_timesheet.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_timesheet_attendance`](../../../agents/modules/generated/hr_timesheet_attendance.yaml)
- Domain: `human_resources`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_timesheet_attendance)
- Direct dependencies: [`hr_attendance`](../hr_attendance/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:hr_timesheet_attendance`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `hr.timesheet.attendance.report`
- Extends `ir.ui.menu` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.hr_attendance`](../../../agents/modules/generated/hr_attendance.yaml) — depends_on
- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
