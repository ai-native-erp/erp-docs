---
layout: page
title: "Sales Expense (sale_expense)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_expense/
nav_order: 0
---
# Sales Expense — `sale_expense`

**Source:** [`agents/modules/generated/sale_expense.yaml`](../../agents/modules/generated/sale_expense.yaml) · **Wiki:** [`knowledge/modules/sale_expense/overview.md`](../../knowledge/modules/sale_expense/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_expense</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sales Expense</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_expense</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_expense"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Quotation, Sales Orders, Delivery & Invoicing Control

## Direct dependencies

[`hr_expense`](hr_expense.md), [`sale_management`](sale_management.md)

## Reverse dependencies (modules that depend on this)

[`project_sale_expense`](project_sale_expense.md), [`sale_expense_margin`](sale_expense_margin.md), [`spreadsheet_dashboard_hr_expense`](spreadsheet_dashboard_hr_expense.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>sale_expense</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>sale_expense</code></div></div>
<div class="model"><div class="name"><code>hr.expense</code></div><div class="role">extended by <code>sale_expense</code></div></div>
<div class="model"><div class="name"><code>hr.expense.sheet</code></div><div class="role">extended by <code>sale_expense</code></div></div>
<div class="model"><div class="name"><code>hr.expense.split</code></div><div class="role">extended by <code>sale_expense</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>sale_expense</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_expense</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.hr_expense` | depends_on, extends_model_from | `agents/modules/generated/hr_expense.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.project_sale_expense` | required_by | `agents/modules/generated/project_sale_expense.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_expense_margin` | required_by | `agents/modules/generated/sale_expense_margin.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_expense`](../../../agents/modules/generated/sale_expense.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_expense)
- Direct dependencies: [`hr_expense`](../hr_expense/overview.md), [`sale_management`](../sale_management/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`project_sale_expense`](../project_sale_expense/overview.md), [`sale_expense_margin`](../sale_expense_margin/overview.md), [`spreadsheet_dashboard_hr_expense`](../spreadsheet_dashboard_hr_expense/overview.md)
- Impact graph: [`module:sale_expense`](../../impact-graph.json)

## Purpose

Quotation, Sales Orders, Delivery & Invoicing Control

## Model relationships

- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `hr.expense` — defined by [`hr_expense`](../hr_expense/overview.md)
- Extends `hr.expense.sheet` — defined by [`hr_expense`](../hr_expense/overview.md)
- Extends `hr.expense.split` — defined by [`hr_expense`](../hr_expense/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — depends_on, extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.project_sale_expense`](../../../agents/modules/generated/project_sale_expense.yaml) — required_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_expense_margin`](../../../agents/modules/generated/sale_expense_margin.yaml) — required_by
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — depends_on
- [`module.spreadsheet_dashboard_hr_expense`](../../../agents/modules/generated/spreadsheet_dashboard_hr_expense.yaml) — required_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
