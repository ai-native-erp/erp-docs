---
layout: page
title: "Project - Sale - Expense (project_sale_expense)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/project_sale_expense/
nav_order: 0
---
# Project - Sale - Expense — `project_sale_expense`

**Source:** [`agents/modules/generated/project_sale_expense.yaml`](../../agents/modules/generated/project_sale_expense.yaml) · **Wiki:** [`knowledge/modules/project_sale_expense/overview.md`](../../knowledge/modules/project_sale_expense/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>project_sale_expense</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Project - Sale - Expense</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">projects_services</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/project_sale_expense</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_sale_expense"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`project_hr_expense`](project_hr_expense.md), [`sale_expense`](sale_expense.md), [`sale_project`](sale_project.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>project.project</code></div><div class="role">extended by <code>project_sale_expense</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.project` | extends_model_from | `agents/modules/generated/project.yaml` |
| `module.project_hr_expense` | depends_on | `agents/modules/generated/project_hr_expense.yaml` |
| `module.sale_expense` | depends_on | `agents/modules/generated/sale_expense.yaml` |
| `module.sale_project` | depends_on | `agents/modules/generated/sale_project.yaml` |

## Full wiki excerpt

- SME owner: [`module.project_sale_expense`](../../../agents/modules/generated/project_sale_expense.yaml)
- Domain: `projects_services`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_sale_expense)
- Direct dependencies: [`project_hr_expense`](../project_hr_expense/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_project`](../sale_project/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:project_sale_expense`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `project.project` — defined by [`project`](../project/overview.md)

## Related SME agents

- [`module.project`](../../../agents/modules/generated/project.yaml) — extends_model_from
- [`module.project_hr_expense`](../../../agents/modules/generated/project_hr_expense.yaml) — depends_on
- [`module.sale_expense`](../../../agents/modules/generated/sale_expense.yaml) — depends_on
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`project`](../project/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
