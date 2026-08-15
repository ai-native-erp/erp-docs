---
layout: page
title: "Landed Costs On MO (mrp_landed_costs)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mrp_landed_costs/
nav_order: 0
---
# Landed Costs On MO — `mrp_landed_costs`

**Source:** [`agents/modules/generated/mrp_landed_costs.yaml`](../../agents/modules/generated/mrp_landed_costs.yaml) · **Wiki:** [`knowledge/modules/mrp_landed_costs/overview.md`](../../knowledge/modules/mrp_landed_costs/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mrp_landed_costs</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Landed Costs On MO</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">manufacturing</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mrp_landed_costs</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_landed_costs"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Landed Costs on Manufacturing Order

## Direct dependencies

[`mrp`](mrp.md), [`stock_landed_costs`](stock_landed_costs.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>stock.landed.cost</code></div><div class="role">extended by <code>mrp_landed_costs</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mrp` | depends_on | `agents/modules/generated/mrp.yaml` |
| `module.stock_landed_costs` | depends_on, extends_model_from | `agents/modules/generated/stock_landed_costs.yaml` |

## Full wiki excerpt

- SME owner: [`module.mrp_landed_costs`](../../../agents/modules/generated/mrp_landed_costs.yaml)
- Domain: `manufacturing`
- Category: Manufacturing/Manufacturing
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_landed_costs)
- Direct dependencies: [`mrp`](../mrp/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:mrp_landed_costs`](../../impact-graph.json)

## Purpose

Landed Costs on Manufacturing Order

## Model relationships

- Extends `stock.landed.cost` — defined by [`stock_landed_costs`](../stock_landed_costs/overview.md)

## Related SME agents

- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — depends_on
- [`module.stock_landed_costs`](../../../agents/modules/generated/stock_landed_costs.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`stock_landed_costs`](../stock_landed_costs/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
