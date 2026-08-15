---
layout: page
title: "Mrp Repairs (mrp_repair)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mrp_repair/
nav_order: 0
---
# Mrp Repairs — `mrp_repair`

**Source:** [`agents/modules/generated/mrp_repair.yaml`](../../agents/modules/generated/mrp_repair.yaml) · **Wiki:** [`knowledge/modules/mrp_repair/overview.md`](../../knowledge/modules/mrp_repair/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mrp_repair</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Mrp Repairs</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">manufacturing</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mrp_repair</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_repair"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`mrp`](mrp.md), [`repair`](repair.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>repair.order</code></div><div class="role">extended by <code>mrp_repair</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>mrp_repair</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mrp` | depends_on | `agents/modules/generated/mrp.yaml` |
| `module.repair` | depends_on, extends_model_from | `agents/modules/generated/repair.yaml` |
| `module.stock` | extends_model_from | `agents/modules/generated/stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.mrp_repair`](../../../agents/modules/generated/mrp_repair.yaml)
- Domain: `manufacturing`
- Category: Inventory/Inventory
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_repair)
- Direct dependencies: [`mrp`](../mrp/overview.md), [`repair`](../repair/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:mrp_repair`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `repair.order` — defined by [`repair`](../repair/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — depends_on
- [`module.repair`](../../../agents/modules/generated/repair.yaml) — depends_on, extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`repair`](../repair/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
