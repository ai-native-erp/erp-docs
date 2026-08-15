---
layout: page
title: "Project - Account (project_account)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/project_account/
nav_order: 0
---
# Project - Account — `project_account`

**Source:** [`agents/modules/generated/project_account.yaml`](../../agents/modules/generated/project_account.yaml) · **Wiki:** [`knowledge/modules/project_account/overview.md`](../../knowledge/modules/project_account/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>project_account</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Project - Account</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">projects_services</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/project_account</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_account"><code>126b5bd</code></a></div></div>
</div>
## Purpose

project profitability items computation

## Direct dependencies

[`account`](account.md), [`project`](project.md)

## Reverse dependencies (modules that depend on this)

[`project_hr_expense`](project_hr_expense.md), [`project_purchase`](project_purchase.md), [`sale_project`](sale_project.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>project.project</code></div><div class="role">extended by <code>project_account</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on | `agents/modules/generated/account.yaml` |
| `module.project` | depends_on, extends_model_from | `agents/modules/generated/project.yaml` |
| `module.project_hr_expense` | required_by | `agents/modules/generated/project_hr_expense.yaml` |
| `module.project_purchase` | required_by | `agents/modules/generated/project_purchase.yaml` |
| `module.sale_project` | required_by | `agents/modules/generated/sale_project.yaml` |

## Full wiki excerpt

- SME owner: [`module.project_account`](../../../agents/modules/generated/project_account.yaml)
- Domain: `projects_services`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_account)
- Direct dependencies: [`account`](../account/overview.md), [`project`](../project/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`project_hr_expense`](../project_hr_expense/overview.md), [`project_purchase`](../project_purchase/overview.md), [`sale_project`](../sale_project/overview.md)
- Impact graph: [`module:project_account`](../../impact-graph.json)

## Purpose

project profitability items computation

## Model relationships

- Extends `project.project` — defined by [`project`](../project/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on
- [`module.project`](../../../agents/modules/generated/project.yaml) — depends_on, extends_model_from
- [`module.project_hr_expense`](../../../agents/modules/generated/project_hr_expense.yaml) — required_by
- [`module.project_purchase`](../../../agents/modules/generated/project_purchase.yaml) — required_by
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — required_by

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`project`](../project/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
