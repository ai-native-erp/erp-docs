---
layout: page
title: "Sales - Project (sale_project)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_project/
nav_order: 0
---
# Sales - Project — `sale_project`

**Source:** [`agents/modules/generated/sale_project.yaml`](../../agents/modules/generated/sale_project.yaml) · **Wiki:** [`knowledge/modules/sale_project/overview.md`](../../knowledge/modules/sale_project/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_project</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sales - Project</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_project</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_project"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Task Generation from Sales Orders

## Direct dependencies

[`project_account`](project_account.md), [`sale_management`](sale_management.md), [`sale_service`](sale_service.md)

## Reverse dependencies (modules that depend on this)

[`project_sale_expense`](project_sale_expense.md), [`sale_project_stock`](sale_project_stock.md), [`sale_timesheet`](sale_timesheet.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>project.milestone</code></div><div class="role">defined by <code>sale_project</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>sale_project</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>sale_project</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>sale_project</code></div></div>
<div class="model"><div class="name"><code>project.milestone</code></div><div class="role">extended by <code>sale_project</code></div></div>
<div class="model"><div class="name"><code>project.project</code></div><div class="role">extended by <code>sale_project</code></div></div>
<div class="model"><div class="name"><code>project.task</code></div><div class="role">extended by <code>sale_project</code></div></div>
<div class="model"><div class="name"><code>project.task.recurrence</code></div><div class="role">extended by <code>sale_project</code></div></div>
<div class="model"><div class="name"><code>report.project.task.user</code></div><div class="role">extended by <code>sale_project</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>sale_project</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_project</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale_project</code></div></div>
<div class="model"><div class="name"><code>sale.order.template.line</code></div><div class="role">extended by <code>sale_project</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.hr_timesheet` | extends_model_from | `agents/modules/generated/hr_timesheet.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.project` | extends_model_from | `agents/modules/generated/project.yaml` |
| `module.project_account` | depends_on | `agents/modules/generated/project_account.yaml` |
| `module.project_sale_expense` | required_by | `agents/modules/generated/project_sale_expense.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml)
- Domain: `sales_crm`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_project)
- Direct dependencies: [`project_account`](../project_account/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_service`](../sale_service/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`project_sale_expense`](../project_sale_expense/overview.md), [`sale_project_stock`](../sale_project_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md)
- Impact graph: [`module:sale_project`](../../impact-graph.json)

## Purpose

Task Generation from Sales Orders

## Model relationships

- `project.milestone`
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `project.milestone` — defined by [`project`](../project/overview.md)
- Extends `project.project` — defined by [`project`](../project/overview.md)
- Extends `project.task` — defined by [`hr_timesheet`](../hr_timesheet/overview.md), [`project`](../project/overview.md)
- Extends `project.task.recurrence` — defined by [`project`](../project/overview.md)
- Extends `report.project.task.user` — defined by [`project`](../project/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.template.line` — defined by [`sale_management`](../sale_management/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.project`](../../../agents/modules/generated/project.yaml) — extends_model_from
- [`module.project_account`](../../../agents/modules/generated/project_account.yaml) — depends_on
- [`module.project_sale_expense`](../../../agents/modules/generated/project_sale_expense.yaml) — required_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — depends_on, extends_model_from
- [`module.sale_project_stock`](../../../agents/modules/generated/sale_project_stock.yaml) — required_by
- [`module.sale_service`](../../../agents/modules/generated/sale_service.yaml) — depends_on
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — required_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sale_management`](../sale_management/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
