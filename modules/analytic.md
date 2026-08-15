---
layout: page
title: "Analytic Accounting (analytic)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/analytic/
nav_order: 0
---
# Analytic Accounting — `analytic`

**Source:** [`agents/modules/generated/analytic.yaml`](../../agents/modules/generated/analytic.yaml) · **Wiki:** [`knowledge/modules/analytic/overview.md`](../../knowledge/modules/analytic/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>analytic</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Analytic Accounting</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/analytic</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/analytic"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md), [`mail`](mail.md), [`uom`](uom.md)

## Reverse dependencies (modules that depend on this)

[`account`](account.md), [`hr_timesheet`](hr_timesheet.md), [`project`](project.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.analytic.account</code></div><div class="role">defined by <code>analytic</code></div></div>
<div class="model"><div class="name"><code>account.analytic.applicability</code></div><div class="role">defined by <code>analytic</code></div></div>
<div class="model"><div class="name"><code>account.analytic.distribution.model</code></div><div class="role">defined by <code>analytic</code></div></div>
<div class="model"><div class="name"><code>account.analytic.line</code></div><div class="role">defined by <code>analytic</code></div></div>
<div class="model"><div class="name"><code>account.analytic.plan</code></div><div class="role">defined by <code>analytic</code></div></div>
<div class="model"><div class="name"><code>analytic.mixin</code></div><div class="role">defined by <code>analytic</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.analytic.account</code></div><div class="role">extended by <code>analytic</code></div></div>
<div class="model"><div class="name"><code>account.analytic.line</code></div><div class="role">extended by <code>analytic</code></div></div>
<div class="model"><div class="name"><code>analytic.mixin</code></div><div class="role">extended by <code>analytic</code></div></div>
<div class="model"><div class="name"><code>ir.config_parameter</code></div><div class="role">extended by <code>analytic</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>analytic</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>analytic</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | model_extended_by, required_by | `agents/modules/generated/account.yaml` |
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.hr_expense` | model_extended_by | `agents/modules/generated/hr_expense.yaml` |
| `module.hr_timesheet` | model_extended_by, required_by | `agents/modules/generated/hr_timesheet.yaml` |
| `module.l10n_din5008` | model_extended_by | `agents/modules/generated/l10n_din5008.yaml` |
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mrp_account` | model_extended_by | `agents/modules/generated/mrp_account.yaml` |
| `module.project` | model_extended_by, required_by | `agents/modules/generated/project.yaml` |
| `module.project_timesheet_holidays` | model_extended_by | `agents/modules/generated/project_timesheet_holidays.yaml` |
| `module.purchase` | model_extended_by | `agents/modules/generated/purchase.yaml` |

## Full wiki excerpt

- SME owner: [`module.analytic`](../../../agents/modules/generated/analytic.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/analytic)
- Direct dependencies: [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`uom`](../uom/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`account`](../account/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`project`](../project/overview.md)
- Impact graph: [`module:analytic`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `account.analytic.account` — extended by [`account`](../account/overview.md), [`hr_expense`](../hr_expense/overview.md), [`mrp_account`](../mrp_account/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`stock_account`](../stock_account/overview.md)
- `account.analytic.applicability` — extended by [`account`](../account/overview.md), [`hr_expense`](../hr_expense/overview.md), [`mrp_account`](../mrp_account/overview.md), [`purchase`](../purchase/overview.md), [`sale`](../sale/overview.md)
- `account.analytic.distribution.model` — extended by [`account`](../account/overview.md)
- `account.analytic.line` — extended by [`account`](../account/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md), [`mrp_account`](../mrp_account/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`sale`](../sale/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md)
- `account.analytic.plan` — extended by [`stock_account`](../stock_account/overview.md)
- `analytic.mixin` — extended by [`account`](../account/overview.md), [`hr_expense`](../hr_expense/overview.md), [`mrp_account`](../mrp_account/overview.md), [`purchase`](../purchase/overview.md), [`purchase_requisition`](../purchase_requisition/overview.md), [`sale`](../sale/overview.md)
- Extends `account.analytic.account` — framework/dynamic owner
- Extends `account.analytic.line` — framework/dynamic owner
- Extends `analytic.mixin` — framework/dynamic owner
- Extends `ir.config_parameter` — defined by [`base`](../base/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — model_extended_by, required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — model_extended_by
- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — model_extended_by, required_by
- [`module.l10n_din5008`](../../../agents/modules/generated/l10n_din5008.yaml) — model_extended_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — model_extended_by
- [`module.project`](../../../agents/modules/generated/project.yaml) — model_extended_by, required_by
- [`module.project_timesheet_holidays`](../../../agents/modules/generated/project_timesheet_holidays.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — model_extended_by
- [`module.purchase_requisition`](../../../agents/modules/generated/purchase_requisition.yaml) — model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — model_extended_by
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — model_extended_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — model_extended_by
- [`module.uom`](../../../agents/modules/generated/uom.yaml) — depends_on

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md), [`mrp_account`](../mrp_account/overview.md), [`project`](../project/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`purchase`](../purchase/overview.md), [`purchase_requisition`](../purchase_requisition/overview.md), [`sale`](../sale/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock_account`](../stock_account/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`mail`](../mail/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl, qa_upgrade.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
