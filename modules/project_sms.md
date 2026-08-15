---
layout: page
title: "Project - SMS (project_sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/project_sms/
nav_order: 0
---
# Project - SMS — `project_sms`

**Source:** [`agents/modules/generated/project_sms.yaml`](../../agents/modules/generated/project_sms.yaml) · **Wiki:** [`knowledge/modules/project_sms/overview.md`](../../knowledge/modules/project_sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>project_sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Project - SMS</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">projects_services</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/project_sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Send text messages when project/task stage move

## Direct dependencies

[`project`](project.md), [`sms`](sms.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>project.project</code></div><div class="role">extended by <code>project_sms</code></div></div>
<div class="model"><div class="name"><code>project.project.stage</code></div><div class="role">extended by <code>project_sms</code></div></div>
<div class="model"><div class="name"><code>project.task</code></div><div class="role">extended by <code>project_sms</code></div></div>
<div class="model"><div class="name"><code>project.task.type</code></div><div class="role">extended by <code>project_sms</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr_timesheet` | extends_model_from | `agents/modules/generated/hr_timesheet.yaml` |
| `module.project` | depends_on, extends_model_from | `agents/modules/generated/project.yaml` |
| `module.sms` | depends_on | `agents/modules/generated/sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.project_sms`](../../../agents/modules/generated/project_sms.yaml)
- Domain: `projects_services`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_sms)
- Direct dependencies: [`project`](../project/overview.md), [`sms`](../sms/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:project_sms`](../../impact-graph.json)

## Purpose

Send text messages when project/task stage move

## Model relationships

- Extends `project.project` — defined by [`project`](../project/overview.md)
- Extends `project.project.stage` — defined by [`project`](../project/overview.md)
- Extends `project.task` — defined by [`hr_timesheet`](../hr_timesheet/overview.md), [`project`](../project/overview.md)
- Extends `project.task.type` — defined by [`project`](../project/overview.md)

## Related SME agents

- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — extends_model_from
- [`module.project`](../../../agents/modules/generated/project.yaml) — depends_on, extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`hr_timesheet`](../hr_timesheet/overview.md), [`project`](../project/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
