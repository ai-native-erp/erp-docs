---
layout: page
title: "pos_mrp (pos_mrp)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_mrp/
nav_order: 0
---
# pos_mrp — `pos_mrp`

**Source:** [`agents/modules/generated/pos_mrp.yaml`](../../agents/modules/generated/pos_mrp.yaml) · **Wiki:** [`knowledge/modules/pos_mrp/overview.md`](../../knowledge/modules/pos_mrp/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_mrp</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">pos_mrp</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_mrp</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_mrp"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Link module between Point of Sale and Mrp

## Direct dependencies

[`mrp`](mrp.md), [`point_of_sale`](point_of_sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">extended by <code>pos_mrp</code></div></div>
<div class="model"><div class="name"><code>pos.order.line</code></div><div class="role">extended by <code>pos_mrp</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>pos_mrp</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_ch_pos` | extends_model_from | `agents/modules/generated/l10n_ch_pos.yaml` |
| `module.mrp` | depends_on | `agents/modules/generated/mrp.yaml` |
| `module.point_of_sale` | depends_on, extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.stock` | extends_model_from | `agents/modules/generated/stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_mrp`](../../../agents/modules/generated/pos_mrp.yaml)
- Domain: `point_of_sale`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_mrp)
- Direct dependencies: [`mrp`](../mrp/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:pos_mrp`](../../impact-graph.json)

## Purpose

Link module between Point of Sale and Mrp

## Model relationships

- Extends `pos.order` — defined by [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.order.line` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml) — extends_model_from
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — depends_on
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on, extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
