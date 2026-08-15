---
layout: page
title: "Margins in Sales Orders (sale_margin)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_margin/
nav_order: 0
---
# Margins in Sales Orders — `sale_margin`

**Source:** [`agents/modules/generated/sale_margin.yaml`](../../agents/modules/generated/sale_margin.yaml) · **Wiki:** [`knowledge/modules/sale_margin/overview.md`](../../knowledge/modules/sale_margin/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_margin</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Margins in Sales Orders</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_margin</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_margin"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`sale_management`](sale_management.md)

## Reverse dependencies (modules that depend on this)

[`pos_sale_margin`](pos_sale_margin.md), [`sale_expense_margin`](sale_expense_margin.md), [`sale_stock_margin`](sale_stock_margin.md), [`sale_timesheet_margin`](sale_timesheet_margin.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_margin</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale_margin</code></div></div>
<div class="model"><div class="name"><code>sale.report</code></div><div class="role">extended by <code>sale_margin</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.pos_sale_margin` | required_by | `agents/modules/generated/pos_sale_margin.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_expense_margin` | required_by | `agents/modules/generated/sale_expense_margin.yaml` |
| `module.sale_management` | depends_on | `agents/modules/generated/sale_management.yaml` |
| `module.sale_stock_margin` | required_by | `agents/modules/generated/sale_stock_margin.yaml` |
| `module.sale_timesheet_margin` | required_by | `agents/modules/generated/sale_timesheet_margin.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_margin`](../../../agents/modules/generated/sale_margin.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_margin)
- Direct dependencies: [`sale_management`](../sale_management/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`pos_sale_margin`](../pos_sale_margin/overview.md), [`sale_expense_margin`](../sale_expense_margin/overview.md), [`sale_stock_margin`](../sale_stock_margin/overview.md), [`sale_timesheet_margin`](../sale_timesheet_margin/overview.md)
- Impact graph: [`module:sale_margin`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)
- Extends `sale.report` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.pos_sale_margin`](../../../agents/modules/generated/pos_sale_margin.yaml) — required_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_expense_margin`](../../../agents/modules/generated/sale_expense_margin.yaml) — required_by
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — depends_on
- [`module.sale_stock_margin`](../../../agents/modules/generated/sale_stock_margin.yaml) — required_by
- [`module.sale_timesheet_margin`](../../../agents/modules/generated/sale_timesheet_margin.yaml) — required_by

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
