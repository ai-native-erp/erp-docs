---
layout: page
title: "Expenses (hr_expense)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_expense/
nav_order: 0
---
# Expenses — `hr_expense`

**Source:** [`agents/modules/generated/hr_expense.yaml`](../../agents/modules/generated/hr_expense.yaml) · **Wiki:** [`knowledge/modules/hr_expense/overview.md`](../../knowledge/modules/hr_expense/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_expense</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Expenses</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_expense</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_expense"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Submit, validate and reinvoice employee expenses

## Direct dependencies

[`account`](account.md), [`hr`](hr.md), [`web_tour`](web_tour.md)

## Reverse dependencies (modules that depend on this)

[`project_hr_expense`](project_hr_expense.md), [`sale_expense`](sale_expense.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.expense</code></div><div class="role">defined by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>hr.expense.approve.duplicate</code></div><div class="role">defined by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>hr.expense.refuse.wizard</code></div><div class="role">defined by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>hr.expense.sheet</code></div><div class="role">defined by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>hr.expense.split</code></div><div class="role">defined by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>hr.expense.split.wizard</code></div><div class="role">defined by <code>hr_expense</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.analytic.account</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>account.analytic.applicability</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>account.payment</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>account.payment.register</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>account.tax</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>analytic.mixin</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>hr.department</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>hr.employee.base</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>hr.employee.public</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>ir.actions.report</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>mail.thread.main.attachment</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>hr_expense</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>hr_expense</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.analytic` | extends_model_from | `agents/modules/generated/analytic.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml)
- Domain: `human_resources`
- Category: Human Resources/Expenses
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_expense)
- Direct dependencies: [`account`](../account/overview.md), [`hr`](../hr/overview.md), [`web_tour`](../web_tour/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`project_hr_expense`](../project_hr_expense/overview.md), [`sale_expense`](../sale_expense/overview.md)
- Impact graph: [`module:hr_expense`](../../impact-graph.json)

## Purpose

Submit, validate and reinvoice employee expenses

## Model relationships

- `hr.expense` — extended by [`project_hr_expense`](../project_hr_expense/overview.md), [`sale_expense`](../sale_expense/overview.md)
- `hr.expense.approve.duplicate`
- `hr.expense.refuse.wizard`
- `hr.expense.sheet` — extended by [`sale_expense`](../sale_expense/overview.md)
- `hr.expense.split` — extended by [`sale_expense`](../sale_expense/overview.md)
- `hr.expense.split.wizard`
- Extends `account.analytic.account` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.analytic.applicability` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `account.payment` — defined by [`account`](../account/overview.md)
- Extends `account.payment.register` — defined by [`account`](../account/overview.md)
- Extends `account.tax` — defined by [`account`](../account/overview.md)
- Extends `analytic.mixin` — defined by [`analytic`](../analytic/overview.md)
- Extends `hr.department` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee.base` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee.public` — defined by [`hr`](../hr/overview.md)
- Extends `ir.actions.report` — defined by [`base`](../base/overview.md)
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.main.attachment` — defined by [`mail`](../mail/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.project_hr_expense`](../../../agents/modules/generated/project_hr_expense.yaml) — model_extended_by, required_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_expense`](../../../agents/modules/generated/sale_expense.yaml) — model_extended_by, required_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.web_tour`](../../../agents/modules/generated/web_tour.yaml) — depends_on
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`project_hr_expense`](../project_hr_expense/overview.md), [`sale_expense`](../sale_expense/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`analytic`](../analytic/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`hr`](../hr/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`mrp_account`](../mrp_account/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
