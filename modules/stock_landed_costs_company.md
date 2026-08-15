---
layout: page
title: "Landed Costs for company's branches (stock_landed_costs_company)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/stock_landed_costs_company/
nav_order: 0
---
# Landed Costs for company's branches — `stock_landed_costs_company`

**Source:** [`agents/modules/generated/stock_landed_costs_company.yaml`](../../agents/modules/generated/stock_landed_costs_company.yaml) · **Wiki:** [`knowledge/modules/stock_landed_costs_company/overview.md`](../../knowledge/modules/stock_landed_costs_company/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>stock_landed_costs_company</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Landed Costs for company's branches</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/stock_landed_costs_company</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock_landed_costs_company"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`stock_landed_costs`](stock_landed_costs.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>stock.landed.cost</code></div><div class="role">extended by <code>stock_landed_costs_company</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.stock_landed_costs` | depends_on, extends_model_from | `agents/modules/generated/stock_landed_costs.yaml` |

## Full wiki excerpt

- SME owner: [`module.stock_landed_costs_company`](../../../agents/modules/generated/stock_landed_costs_company.yaml)
- Domain: `inventory_purchase`
- Category: Inventory/Inventory
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock_landed_costs_company)
- Direct dependencies: [`stock_landed_costs`](../stock_landed_costs/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:stock_landed_costs_company`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `stock.landed.cost` — defined by [`stock_landed_costs`](../stock_landed_costs/overview.md)

## Related SME agents

- [`module.stock_landed_costs`](../../../agents/modules/generated/stock_landed_costs.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`stock_landed_costs`](../stock_landed_costs/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
