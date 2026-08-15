---
layout: page
title: "To-Do (project_todo)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/project_todo/
nav_order: 0
---
# To-Do — `project_todo`

**Source:** [`agents/modules/generated/project_todo.yaml`](../../agents/modules/generated/project_todo.yaml) · **Wiki:** [`knowledge/modules/project_todo/overview.md`](../../knowledge/modules/project_todo/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>project_todo</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">To-Do</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">projects_services</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/project_todo</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_todo"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Organize your work with memos and to-do lists

## Direct dependencies

[`project`](project.md)

## Reverse dependencies (modules that depend on this)

[`test_discuss_full`](test_discuss_full.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.activity.todo.create</code></div><div class="role">defined by <code>project_todo</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.activity.type</code></div><div class="role">extended by <code>project_todo</code></div></div>
<div class="model"><div class="name"><code>project.task</code></div><div class="role">extended by <code>project_todo</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr_timesheet` | extends_model_from | `agents/modules/generated/hr_timesheet.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.project` | depends_on, extends_model_from | `agents/modules/generated/project.yaml` |
| `module.test_discuss_full` | required_by | `agents/modules/generated/test_discuss_full.yaml` |

## Full wiki excerpt

- SME owner: [`module.project_todo`](../../../agents/modules/generated/project_todo.yaml)
- Domain: `projects_services`
- Category: Productivity/To-Do
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_todo)
- Direct dependencies: [`project`](../project/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_discuss_full`](../test_discuss_full/overview.md)
- Impact graph: [`module:project_todo`](../../impact-graph.json)

## Purpose

Organize your work with memos and to-do lists

## Model relationships

- `mail.activity.todo.create`
- Extends `mail.activity.type` — defined by [`mail`](../mail/overview.md)
- Extends `project.task` — defined by [`hr_timesheet`](../hr_timesheet/overview.md), [`project`](../project/overview.md)

## Related SME agents

- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.project`](../../../agents/modules/generated/project.yaml) — depends_on, extends_model_from
- [`module.test_discuss_full`](../../../agents/modules/generated/test_discuss_full.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`hr_timesheet`](../hr_timesheet/overview.md), [`mail`](../mail/overview.md), [`project`](../project/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
