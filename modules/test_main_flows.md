---
layout: page
title: "Test Main Flow (test_main_flows)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_main_flows/
nav_order: 0
---
# Test Main Flow — `test_main_flows`

**Source:** [`agents/modules/generated/test_main_flows.yaml`](../../agents/modules/generated/test_main_flows.yaml) · **Wiki:** [`knowledge/modules/test_main_flows/overview.md`](../../knowledge/modules/test_main_flows/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_main_flows</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Test Main Flow</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/test_main_flows</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_main_flows"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md), [`crm`](crm.md), [`mrp`](mrp.md), [`purchase_stock`](purchase_stock.md), [`sale_timesheet`](sale_timesheet.md), [`web_tour`](web_tour.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>test.model_multicompany</code></div><div class="role">defined by <code>test_main_flows</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on | `agents/modules/generated/account.yaml` |
| `module.crm` | depends_on | `agents/modules/generated/crm.yaml` |
| `module.mrp` | depends_on | `agents/modules/generated/mrp.yaml` |
| `module.purchase_stock` | depends_on | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale_timesheet` | depends_on | `agents/modules/generated/sale_timesheet.yaml` |
| `module.web_tour` | depends_on | `agents/modules/generated/web_tour.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_main_flows`](../../../agents/modules/generated/test_main_flows.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_main_flows)
- Direct dependencies: [`account`](../account/overview.md), [`crm`](../crm/overview.md), [`mrp`](../mrp/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`web_tour`](../web_tour/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_main_flows`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `test.model_multicompany`

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — depends_on
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — depends_on
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — depends_on
- [`module.web_tour`](../../../agents/modules/generated/web_tour.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
