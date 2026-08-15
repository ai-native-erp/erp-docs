---
layout: page
title: "Service Margins in Sales Orders (sale_timesheet_margin)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_timesheet_margin/
nav_order: 0
---
# Service Margins in Sales Orders — `sale_timesheet_margin`

**Source:** [`agents/modules/generated/sale_timesheet_margin.yaml`](../../agents/modules/generated/sale_timesheet_margin.yaml) · **Wiki:** [`knowledge/modules/sale_timesheet_margin/overview.md`](../../knowledge/modules/sale_timesheet_margin/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_timesheet_margin</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Service Margins in Sales Orders</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_timesheet_margin</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_timesheet_margin"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Bridge module between Sales Margin and Sales Timesheet

## Direct dependencies

[`sale_margin`](sale_margin.md), [`sale_timesheet`](sale_timesheet.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale_timesheet_margin</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_margin` | depends_on | `agents/modules/generated/sale_margin.yaml` |
| `module.sale_timesheet` | depends_on | `agents/modules/generated/sale_timesheet.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_timesheet_margin`](../../../agents/modules/generated/sale_timesheet_margin.yaml)
- Domain: `sales_crm`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_timesheet_margin)
- Direct dependencies: [`sale_margin`](../sale_margin/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:sale_timesheet_margin`](../../impact-graph.json)

## Purpose

Bridge module between Sales Margin and Sales Timesheet

## Model relationships

- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_margin`](../../../agents/modules/generated/sale_margin.yaml) — depends_on
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
