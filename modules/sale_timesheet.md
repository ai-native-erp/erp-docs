---
layout: page
title: "Sales Timesheet (sale_timesheet)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_timesheet/
nav_order: 0
---
# Sales Timesheet — `sale_timesheet`

**Source:** [`agents/modules/generated/sale_timesheet.yaml`](../../agents/modules/generated/sale_timesheet.yaml) · **Wiki:** [`knowledge/modules/sale_timesheet/overview.md`](../../knowledge/modules/sale_timesheet/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_timesheet</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sales Timesheet</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_timesheet</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_timesheet"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Sell based on timesheets

## Direct dependencies

[`hr_timesheet`](hr_timesheet.md), [`sale_project`](sale_project.md)

## Reverse dependencies (modules that depend on this)

[`sale_timesheet_margin`](sale_timesheet_margin.md), [`spreadsheet_dashboard_sale_timesheet`](spreadsheet_dashboard_sale_timesheet.md), [`test_main_flows`](test_main_flows.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>project.create.invoice</code></div><div class="role">defined by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>project.create.sale.order</code></div><div class="role">defined by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>project.create.sale.order.line</code></div><div class="role">defined by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>project.sale.line.employee.map</code></div><div class="role">defined by <code>sale_timesheet</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.analytic.line</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>account.move.reversal</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>project.project</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>project.task</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>project.task.recurrence</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>project.update</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>report.project.task.user</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>sale.advance.payment.inv</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
<div class="model"><div class="name"><code>timesheets.analysis.report</code></div><div class="role">extended by <code>sale_timesheet</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.analytic` | extends_model_from | `agents/modules/generated/analytic.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.hr` | extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.hr_timesheet` | depends_on, extends_model_from | `agents/modules/generated/hr_timesheet.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.project` | extends_model_from | `agents/modules/generated/project.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml)
- Domain: `sales_crm`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_timesheet)
- Direct dependencies: [`hr_timesheet`](../hr_timesheet/overview.md), [`sale_project`](../sale_project/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`sale_timesheet_margin`](../sale_timesheet_margin/overview.md), [`spreadsheet_dashboard_sale_timesheet`](../spreadsheet_dashboard_sale_timesheet/overview.md), [`test_main_flows`](../test_main_flows/overview.md)
- Impact graph: [`module:sale_timesheet`](../../impact-graph.json)

## Purpose

Sell based on timesheets

## Model relationships

- `project.create.invoice`
- `project.create.sale.order`
- `project.create.sale.order.line`
- `project.sale.line.employee.map`
- Extends `account.analytic.line` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `account.move.reversal` — defined by [`account`](../account/overview.md)
- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `project.project` — defined by [`project`](../project/overview.md)
- Extends `project.task` — defined by [`hr_timesheet`](../hr_timesheet/overview.md), [`project`](../project/overview.md)
- Extends `project.task.recurrence` — defined by [`project`](../project/overview.md)
- Extends `project.update` — defined by [`project`](../project/overview.md)
- Extends `report.project.task.user` — defined by [`project`](../project/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `sale.advance.payment.inv` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)
- Extends `timesheets.analysis.report` — defined by [`hr_timesheet`](../hr_timesheet/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — extends_model_from
- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — depends_on, extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.project`](../../../agents/modules/generated/project.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — depends_on
- [`module.sale_timesheet_margin`](../../../agents/modules/generated/sale_timesheet_margin.yaml) — required_by
- [`module.spreadsheet_dashboard_sale_timesheet`](../../../agents/modules/generated/spreadsheet_dashboard_sale_timesheet.yaml) — required_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.test_main_flows`](../../../agents/modules/generated/test_main_flows.yaml) — required_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`analytic`](../analytic/overview.md), [`base`](../base/overview.md), [`hr`](../hr/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
