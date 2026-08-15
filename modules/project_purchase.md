---
layout: page
title: "Project Purchase (project_purchase)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/project_purchase/
nav_order: 0
---
# Project Purchase — `project_purchase`

**Source:** [`agents/modules/generated/project_purchase.yaml`](../../agents/modules/generated/project_purchase.yaml) · **Wiki:** [`knowledge/modules/project_purchase/overview.md`](../../knowledge/modules/project_purchase/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>project_purchase</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Project Purchase</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">projects_services</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/project_purchase</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_purchase"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Monitor purchase in project

## Direct dependencies

[`project_account`](project_account.md), [`purchase`](purchase.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>project.project</code></div><div class="role">extended by <code>project_purchase</code></div></div>
<div class="model"><div class="name"><code>purchase.order.line</code></div><div class="role">extended by <code>project_purchase</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.project` | extends_model_from | `agents/modules/generated/project.yaml` |
| `module.project_account` | depends_on | `agents/modules/generated/project_account.yaml` |
| `module.purchase` | depends_on, extends_model_from | `agents/modules/generated/purchase.yaml` |

## Full wiki excerpt

- SME owner: [`module.project_purchase`](../../../agents/modules/generated/project_purchase.yaml)
- Domain: `projects_services`
- Category: Services/Project
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_purchase)
- Direct dependencies: [`project_account`](../project_account/overview.md), [`purchase`](../purchase/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:project_purchase`](../../impact-graph.json)

## Purpose

Monitor purchase in project

## Model relationships

- Extends `project.project` — defined by [`project`](../project/overview.md)
- Extends `purchase.order.line` — defined by [`purchase`](../purchase/overview.md)

## Related SME agents

- [`module.project`](../../../agents/modules/generated/project.yaml) — extends_model_from
- [`module.project_account`](../../../agents/modules/generated/project_account.yaml) — depends_on
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`project`](../project/overview.md), [`purchase`](../purchase/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
