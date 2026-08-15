---
layout: page
title: "Sales Expense Margin (sale_expense_margin)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_expense_margin/
nav_order: 0
---
# Sales Expense Margin — `sale_expense_margin`

**Source:** [`agents/modules/generated/sale_expense_margin.yaml`](../../agents/modules/generated/sale_expense_margin.yaml) · **Wiki:** [`knowledge/modules/sale_expense_margin/overview.md`](../../knowledge/modules/sale_expense_margin/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_expense_margin</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sales Expense Margin</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_expense_margin</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_expense_margin"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`sale_expense`](sale_expense.md), [`sale_margin`](sale_margin.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>sale_expense_margin</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale_expense_margin</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_expense` | depends_on | `agents/modules/generated/sale_expense.yaml` |
| `module.sale_margin` | depends_on | `agents/modules/generated/sale_margin.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_expense_margin`](../../../agents/modules/generated/sale_expense_margin.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_expense_margin)
- Direct dependencies: [`sale_expense`](../sale_expense/overview.md), [`sale_margin`](../sale_margin/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:sale_expense_margin`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_expense`](../../../agents/modules/generated/sale_expense.yaml) — depends_on
- [`module.sale_margin`](../../../agents/modules/generated/sale_margin.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
