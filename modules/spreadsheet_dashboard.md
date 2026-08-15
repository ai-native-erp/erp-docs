---
layout: page
title: "Spreadsheet dashboard (spreadsheet_dashboard)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/spreadsheet_dashboard/
nav_order: 0
---
# Spreadsheet dashboard — `spreadsheet_dashboard`

**Source:** [`agents/modules/generated/spreadsheet_dashboard.yaml`](../../agents/modules/generated/spreadsheet_dashboard.yaml) · **Wiki:** [`knowledge/modules/spreadsheet_dashboard/overview.md`](../../knowledge/modules/spreadsheet_dashboard/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>spreadsheet_dashboard</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Spreadsheet dashboard</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/spreadsheet_dashboard</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/spreadsheet_dashboard"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Spreadsheet

## Direct dependencies

[`spreadsheet`](spreadsheet.md)

## Reverse dependencies (modules that depend on this)

[`board`](board.md), [`spreadsheet_dashboard_account`](spreadsheet_dashboard_account.md), [`spreadsheet_dashboard_event_sale`](spreadsheet_dashboard_event_sale.md), [`spreadsheet_dashboard_hr_expense`](spreadsheet_dashboard_hr_expense.md), [`spreadsheet_dashboard_hr_timesheet`](spreadsheet_dashboard_hr_timesheet.md), [`spreadsheet_dashboard_im_livechat`](spreadsheet_dashboard_im_livechat.md), [`spreadsheet_dashboard_pos_hr`](spreadsheet_dashboard_pos_hr.md), [`spreadsheet_dashboard_purchase`](spreadsheet_dashboard_purchase.md), [`spreadsheet_dashboard_purchase_stock`](spreadsheet_dashboard_purchase_stock.md), [`spreadsheet_dashboard_sale`](spreadsheet_dashboard_sale.md), [`spreadsheet_dashboard_sale_timesheet`](spreadsheet_dashboard_sale_timesheet.md), [`spreadsheet_dashboard_stock_account`](spreadsheet_dashboard_stock_account.md), [`spreadsheet_dashboard_website_sale`](spreadsheet_dashboard_website_sale.md), [`spreadsheet_dashboard_website_sale_slides`](spreadsheet_dashboard_website_sale_slides.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>spreadsheet.dashboard</code></div><div class="role">defined by <code>spreadsheet_dashboard</code></div></div>
<div class="model"><div class="name"><code>spreadsheet.dashboard.group</code></div><div class="role">defined by <code>spreadsheet_dashboard</code></div></div>
<div class="model"><div class="name"><code>spreadsheet.dashboard.share</code></div><div class="role">defined by <code>spreadsheet_dashboard</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>spreadsheet.mixin</code></div><div class="role">extended by <code>spreadsheet_dashboard</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.board` | required_by | `agents/modules/generated/board.yaml` |
| `module.spreadsheet` | depends_on, extends_model_from | `agents/modules/generated/spreadsheet.yaml` |
| `module.spreadsheet_dashboard_account` | required_by | `agents/modules/generated/spreadsheet_dashboard_account.yaml` |
| `module.spreadsheet_dashboard_event_sale` | required_by | `agents/modules/generated/spreadsheet_dashboard_event_sale.yaml` |
| `module.spreadsheet_dashboard_hr_expense` | required_by | `agents/modules/generated/spreadsheet_dashboard_hr_expense.yaml` |
| `module.spreadsheet_dashboard_hr_timesheet` | required_by | `agents/modules/generated/spreadsheet_dashboard_hr_timesheet.yaml` |
| `module.spreadsheet_dashboard_im_livechat` | required_by | `agents/modules/generated/spreadsheet_dashboard_im_livechat.yaml` |
| `module.spreadsheet_dashboard_pos_hr` | required_by | `agents/modules/generated/spreadsheet_dashboard_pos_hr.yaml` |
| `module.spreadsheet_dashboard_purchase` | required_by | `agents/modules/generated/spreadsheet_dashboard_purchase.yaml` |
| `module.spreadsheet_dashboard_purchase_stock` | required_by | `agents/modules/generated/spreadsheet_dashboard_purchase_stock.yaml` |

## Conversation learnings

- [`2026-08-12-store-missing-filestore-dashboard-repair`](../../knowledge/conversations/2026-08-12-store-missing-filestore-dashboard-repair.json)

## Full wiki excerpt

- SME owner: [`module.spreadsheet_dashboard`](../../../agents/modules/generated/spreadsheet_dashboard.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/spreadsheet_dashboard)
- Direct dependencies: [`spreadsheet`](../spreadsheet/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`board`](../board/overview.md), [`spreadsheet_dashboard_account`](../spreadsheet_dashboard_account/overview.md), [`spreadsheet_dashboard_event_sale`](../spreadsheet_dashboard_event_sale/overview.md), [`spreadsheet_dashboard_hr_expense`](../spreadsheet_dashboard_hr_expense/overview.md), [`spreadsheet_dashboard_hr_timesheet`](../spreadsheet_dashboard_hr_timesheet/overview.md), [`spreadsheet_dashboard_im_livechat`](../spreadsheet_dashboard_im_livechat/overview.md), [`spreadsheet_dashboard_pos_hr`](../spreadsheet_dashboard_pos_hr/overview.md), [`spreadsheet_dashboard_purchase`](../spreadsheet_dashboard_purchase/overview.md), [`spreadsheet_dashboard_purchase_stock`](../spreadsheet_dashboard_purchase_stock/overview.md), [`spreadsheet_dashboard_sale`](../spreadsheet_dashboard_sale/overview.md), [`spreadsheet_dashboard_sale_timesheet`](../spreadsheet_dashboard_sale_timesheet/overview.md), [`spreadsheet_dashboard_stock_account`](../spreadsheet_dashboard_stock_account/overview.md), [`spreadsheet_dashboard_website_sale`](../spreadsheet_dashboard_website_sale/overview.md), [`spreadsheet_dashboard_website_sale_slides`](../spreadsheet_dashboard_website_sale_slides/overview.md)
- Impact graph: [`module:spreadsheet_dashboard`](../../impact-graph.json)

## Purpose

Spreadsheet

## Model relationships

- `spreadsheet.dashboard`
- `spreadsheet.dashboard.group`
- `spreadsheet.dashboard.share`
- Extends `spreadsheet.mixin` — defined by [`spreadsheet`](../spreadsheet/overview.md)

## Related SME agents

- [`module.board`](../../../agents/modules/generated/board.yaml) — required_by
- [`module.spreadsheet`](../../../agents/modules/generated/spreadsheet.yaml) — depends_on, extends_model_from
- [`module.spreadsheet_dashboard_account`](../../../agents/modules/generated/spreadsheet_dashboard_account.yaml) — required_by
- [`module.spreadsheet_dashboard_event_sale`](../../../agents/modules/generated/spreadsheet_dashboard_event_sale.yaml) — required_by
- [`module.spreadsheet_dashboard_hr_expense`](../../../agents/modules/generated/spreadsheet_dashboard_hr_expense.yaml) — required_by
- [`module.spreadsheet_dashboard_hr_timesheet`](../../../agents/modules/generated/spreadsheet_dashboard_hr_timesheet.yaml) — required_by
- [`module.spreadsheet_dashboard_im_livechat`](../../../agents/modules/generated/spreadsheet_dashboard_im_livechat.yaml) — required_by
- [`module.spreadsheet_dashboard_pos_hr`](../../../agents/modules/generated/spreadsheet_dashboard_pos_hr.yaml) — required_by
- [`module.spreadsheet_dashboard_purchase`](../../../agents/modules/generated/spreadsheet_dashboard_purchase.yaml) — required_by
- [`module.spreadsheet_dashboard_purchase_stock`](../../../agents/modules/generated/spreadsheet_dashboard_purchase_stock.yaml) — required_by
- [`module.spreadsheet_dashboard_sale`](../../../agents/modules/generated/spreadsheet_dashboard_sale.yaml) — required_by
- [`module.spreadsheet_dashboard_sale_timesheet`](../../../agents/modules/generated/spreadsheet_dashboard_sale_timesheet.yaml) — required_by
- [`module.spreadsheet_dashboard_stock_account`](../../../agents/modules/generated/spreadsheet_dashboard_stock_account.yaml) — required_by
- [`module.spreadsheet_dashboard_website_sale`](../../../agents/modules/generated/spreadsheet_dashboard_website_sale.yaml) — required_by
- [`module.spreadsheet_dashboard_website_sale_slides`](../../../agents/modules/generated/spreadsheet_dashboard_website_sale_slides.yaml) — required_by

## Regression impact checklist

- Review 14 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`spreadsheet`](../spreadsheet/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-12-store-missing-filestore-dashboard-repair`](../../conversations/2026-08-12-store-missing-filestore-dashboard-repair.json)
