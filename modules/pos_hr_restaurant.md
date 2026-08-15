---
layout: page
title: "POS HR Restaurant (pos_hr_restaurant)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_hr_restaurant/
nav_order: 0
---
# POS HR Restaurant — `pos_hr_restaurant`

**Source:** [`agents/modules/generated/pos_hr_restaurant.yaml`](../../agents/modules/generated/pos_hr_restaurant.yaml) · **Wiki:** [`knowledge/modules/pos_hr_restaurant/overview.md`](../../knowledge/modules/pos_hr_restaurant/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_hr_restaurant</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">POS HR Restaurant</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_hr_restaurant</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_hr_restaurant"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Link module between pos_hr and pos_restaurant

## Direct dependencies

[`pos_hr`](pos_hr.md), [`pos_restaurant`](pos_restaurant.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.pos_hr` | depends_on | `agents/modules/generated/pos_hr.yaml` |
| `module.pos_restaurant` | depends_on | `agents/modules/generated/pos_restaurant.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_hr_restaurant`](../../../agents/modules/generated/pos_hr_restaurant.yaml)
- Domain: `point_of_sale`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_hr_restaurant)
- Direct dependencies: [`pos_hr`](../pos_hr/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:pos_hr_restaurant`](../../impact-graph.json)

## Purpose

Link module between pos_hr and pos_restaurant

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.pos_hr`](../../../agents/modules/generated/pos_hr.yaml) — depends_on
- [`module.pos_restaurant`](../../../agents/modules/generated/pos_restaurant.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
