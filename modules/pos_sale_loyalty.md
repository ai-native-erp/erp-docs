---
layout: page
title: "POS - Sales Loyality (pos_sale_loyalty)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_sale_loyalty/
nav_order: 0
---
# POS - Sales Loyality — `pos_sale_loyalty`

**Source:** [`agents/modules/generated/pos_sale_loyalty.yaml`](../../agents/modules/generated/pos_sale_loyalty.yaml) · **Wiki:** [`knowledge/modules/pos_sale_loyalty/overview.md`](../../knowledge/modules/pos_sale_loyalty/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_sale_loyalty</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">POS - Sales Loyality</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_sale_loyalty</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_sale_loyalty"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Link module between pos_sale and pos_loyalty

## Direct dependencies

[`pos_loyalty`](pos_loyalty.md), [`pos_sale`](pos_sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>pos_sale_loyalty</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.pos_loyalty` | depends_on | `agents/modules/generated/pos_loyalty.yaml` |
| `module.pos_sale` | depends_on | `agents/modules/generated/pos_sale.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_sale_loyalty`](../../../agents/modules/generated/pos_sale_loyalty.yaml)
- Domain: `point_of_sale`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_sale_loyalty)
- Direct dependencies: [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_sale`](../pos_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:pos_sale_loyalty`](../../impact-graph.json)

## Purpose

Link module between pos_sale and pos_loyalty

## Model relationships

- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.pos_loyalty`](../../../agents/modules/generated/pos_loyalty.yaml) — depends_on
- [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml) — depends_on
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`sale`](../sale/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
