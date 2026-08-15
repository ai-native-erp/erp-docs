---
layout: page
title: "Employee Hourly Wage (hr_hourly_cost)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_hourly_cost/
nav_order: 0
---
# Employee Hourly Wage — `hr_hourly_cost`

**Source:** [`agents/modules/generated/hr_hourly_cost.yaml`](../../agents/modules/generated/hr_hourly_cost.yaml) · **Wiki:** [`knowledge/modules/hr_hourly_cost/overview.md`](../../knowledge/modules/hr_hourly_cost/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_hourly_cost</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Employee Hourly Wage</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_hourly_cost</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_hourly_cost"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Employee Hourly Wage

## Direct dependencies

[`hr`](hr.md)

## Reverse dependencies (modules that depend on this)

[`hr_timesheet`](hr_timesheet.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr_hourly_cost</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.hr_timesheet` | required_by | `agents/modules/generated/hr_timesheet.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_hourly_cost`](../../../agents/modules/generated/hr_hourly_cost.yaml)
- Domain: `human_resources`
- Category: Services/Employee Hourly Cost
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_hourly_cost)
- Direct dependencies: [`hr`](../hr/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_timesheet`](../hr_timesheet/overview.md)
- Impact graph: [`module:hr_hourly_cost`](../../impact-graph.json)

## Purpose

Employee Hourly Wage

## Model relationships

- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)

## Related SME agents

- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`hr`](../hr/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
