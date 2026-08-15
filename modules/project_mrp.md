---
layout: page
title: "MRP Project (project_mrp)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/project_mrp/
nav_order: 0
---
# MRP Project — `project_mrp`

**Source:** [`agents/modules/generated/project_mrp.yaml`](../../agents/modules/generated/project_mrp.yaml) · **Wiki:** [`knowledge/modules/project_mrp/overview.md`](../../knowledge/modules/project_mrp/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>project_mrp</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">MRP Project</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">projects_services</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/project_mrp</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_mrp"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Monitor MRP using project

## Direct dependencies

[`mrp_account`](mrp_account.md), [`project`](project.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mrp.production</code></div><div class="role">extended by <code>project_mrp</code></div></div>
<div class="model"><div class="name"><code>project.project</code></div><div class="role">extended by <code>project_mrp</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mrp` | extends_model_from | `agents/modules/generated/mrp.yaml` |
| `module.mrp_account` | depends_on, extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.project` | depends_on, extends_model_from | `agents/modules/generated/project.yaml` |

## Full wiki excerpt

- SME owner: [`module.project_mrp`](../../../agents/modules/generated/project_mrp.yaml)
- Domain: `projects_services`
- Category: Services/Project
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_mrp)
- Direct dependencies: [`mrp_account`](../mrp_account/overview.md), [`project`](../project/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:project_mrp`](../../impact-graph.json)

## Purpose

Monitor MRP using project

## Model relationships

- Extends `mrp.production` — defined by [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md)
- Extends `project.project` — defined by [`project`](../project/overview.md)

## Related SME agents

- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — depends_on, extends_model_from
- [`module.project`](../../../agents/modules/generated/project.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`project`](../project/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
