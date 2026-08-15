---
layout: page
title: "Sales - Service (sale_service)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_service/
nav_order: 0
---
# Sales - Service — `sale_service`

**Source:** [`agents/modules/generated/sale_service.yaml`](../../agents/modules/generated/sale_service.yaml) · **Wiki:** [`knowledge/modules/sale_service/overview.md`](../../knowledge/modules/sale_service/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_service</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sales - Service</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_service</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_service"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Interaction between Sales and services apps (project and planning)

## Direct dependencies

[`sale_management`](sale_management.md)

## Reverse dependencies (modules that depend on this)

[`sale_project`](sale_project.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale_service</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_management` | depends_on | `agents/modules/generated/sale_management.yaml` |
| `module.sale_project` | required_by | `agents/modules/generated/sale_project.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_service`](../../../agents/modules/generated/sale_service.yaml)
- Domain: `sales_crm`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_service)
- Direct dependencies: [`sale_management`](../sale_management/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`sale_project`](../sale_project/overview.md)
- Impact graph: [`module:sale_service`](../../impact-graph.json)

## Purpose

Interaction between Sales and services apps (project and planning)

## Model relationships

- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — depends_on
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
