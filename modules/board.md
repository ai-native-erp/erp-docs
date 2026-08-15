---
layout: page
title: "Dashboards (board)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/board/
nav_order: 0
---
# Dashboards — `board`

**Source:** [`agents/modules/generated/board.yaml`](../../agents/modules/generated/board.yaml) · **Wiki:** [`knowledge/modules/board/overview.md`](../../knowledge/modules/board/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>board</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Dashboards</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/board</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/board"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Build your own dashboards

## Direct dependencies

[`spreadsheet_dashboard`](spreadsheet_dashboard.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>board.board</code></div><div class="role">defined by <code>board</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.spreadsheet_dashboard` | depends_on | `agents/modules/generated/spreadsheet_dashboard.yaml` |

## Full wiki excerpt

- SME owner: [`module.board`](../../../agents/modules/generated/board.yaml)
- Domain: `platform_core`
- Category: Productivity
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/board)
- Direct dependencies: [`spreadsheet_dashboard`](../spreadsheet_dashboard/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:board`](../../impact-graph.json)

## Purpose

Build your own dashboards

## Model relationships

- `board.board`

## Related SME agents

- [`module.spreadsheet_dashboard`](../../../agents/modules/generated/spreadsheet_dashboard.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
