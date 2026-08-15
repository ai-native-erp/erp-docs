---
layout: page
title: "Spreadsheet dashboard for purchases (spreadsheet_dashboard_purchase_stock)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/spreadsheet_dashboard_purchase_stock/
nav_order: 0
---
# Spreadsheet dashboard for purchases — `spreadsheet_dashboard_purchase_stock`

**Source:** [`agents/modules/generated/spreadsheet_dashboard_purchase_stock.yaml`](../../agents/modules/generated/spreadsheet_dashboard_purchase_stock.yaml) · **Wiki:** [`knowledge/modules/spreadsheet_dashboard_purchase_stock/overview.md`](../../knowledge/modules/spreadsheet_dashboard_purchase_stock/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>spreadsheet_dashboard_purchase_stock</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Spreadsheet dashboard for purchases</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/spreadsheet_dashboard_purchase_stock</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/spreadsheet_dashboard_purchase_stock"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Spreadsheet

## Direct dependencies

[`purchase_stock`](purchase_stock.md), [`spreadsheet_dashboard`](spreadsheet_dashboard.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.purchase_stock` | depends_on | `agents/modules/generated/purchase_stock.yaml` |
| `module.spreadsheet_dashboard` | depends_on | `agents/modules/generated/spreadsheet_dashboard.yaml` |

## Conversation learnings

- [`2026-08-12-store-missing-filestore-dashboard-repair`](../../knowledge/conversations/2026-08-12-store-missing-filestore-dashboard-repair.json)

## Full wiki excerpt

- SME owner: [`module.spreadsheet_dashboard_purchase_stock`](../../../agents/modules/generated/spreadsheet_dashboard_purchase_stock.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/spreadsheet_dashboard_purchase_stock)
- Direct dependencies: [`purchase_stock`](../purchase_stock/overview.md), [`spreadsheet_dashboard`](../spreadsheet_dashboard/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:spreadsheet_dashboard_purchase_stock`](../../impact-graph.json)

## Purpose

Spreadsheet

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — depends_on
- [`module.spreadsheet_dashboard`](../../../agents/modules/generated/spreadsheet_dashboard.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-12-store-missing-filestore-dashboard-repair`](../../conversations/2026-08-12-store-missing-filestore-dashboard-repair.json)
