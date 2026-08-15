---
layout: page
title: "POS - Sales (pos_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_sale/
nav_order: 0
---
# POS - Sales — `pos_sale`

**Source:** [`agents/modules/generated/pos_sale.yaml`](../../agents/modules/generated/pos_sale.yaml) · **Wiki:** [`knowledge/modules/pos_sale/overview.md`](../../knowledge/modules/pos_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">POS - Sales</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Link module between Point of Sale and Sales

## Direct dependencies

[`point_of_sale`](point_of_sale.md), [`sale_management`](sale_management.md)

## Reverse dependencies (modules that depend on this)

[`l10n_be_pos_sale`](l10n_be_pos_sale.md), [`pos_sale_loyalty`](pos_sale_loyalty.md), [`pos_sale_margin`](pos_sale_margin.md), [`pos_self_order_sale`](pos_self_order_sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.team</code></div><div class="role">extended by <code>pos_sale</code></div></div>
<div class="model"><div class="name"><code>pos.config</code></div><div class="role">extended by <code>pos_sale</code></div></div>
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">extended by <code>pos_sale</code></div></div>
<div class="model"><div class="name"><code>pos.order.line</code></div><div class="role">extended by <code>pos_sale</code></div></div>
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>pos_sale</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>pos_sale</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>pos_sale</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>pos_sale</code></div></div>
<div class="model"><div class="name"><code>sale.report</code></div><div class="role">extended by <code>pos_sale</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>pos_sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.l10n_be_pos_sale` | required_by | `agents/modules/generated/l10n_be_pos_sale.yaml` |
| `module.l10n_ch_pos` | extends_model_from | `agents/modules/generated/l10n_ch_pos.yaml` |
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.point_of_sale` | depends_on, extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.pos_sale_loyalty` | required_by | `agents/modules/generated/pos_sale_loyalty.yaml` |
| `module.pos_sale_margin` | required_by | `agents/modules/generated/pos_sale_margin.yaml` |
| `module.pos_self_order_sale` | required_by | `agents/modules/generated/pos_self_order_sale.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml)
- Domain: `point_of_sale`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_sale)
- Direct dependencies: [`point_of_sale`](../point_of_sale/overview.md), [`sale_management`](../sale_management/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_be_pos_sale`](../l10n_be_pos_sale/overview.md), [`pos_sale_loyalty`](../pos_sale_loyalty/overview.md), [`pos_sale_margin`](../pos_sale_margin/overview.md), [`pos_self_order_sale`](../pos_self_order_sale/overview.md)
- Impact graph: [`module:pos_sale`](../../impact-graph.json)

## Purpose

Link module between Point of Sale and Sales

## Model relationships

- Extends `crm.team` — defined by [`crm`](../crm/overview.md), [`sales_team`](../sales_team/overview.md)
- Extends `pos.config` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.order` — defined by [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.order.line` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)
- Extends `sale.report` — defined by [`sale`](../sale/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.l10n_be_pos_sale`](../../../agents/modules/generated/l10n_be_pos_sale.yaml) — required_by
- [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on, extends_model_from
- [`module.pos_sale_loyalty`](../../../agents/modules/generated/pos_sale_loyalty.yaml) — required_by
- [`module.pos_sale_margin`](../../../agents/modules/generated/pos_sale_margin.yaml) — required_by
- [`module.pos_self_order_sale`](../../../agents/modules/generated/pos_self_order_sale.yaml) — required_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — depends_on
- [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`sale`](../sale/overview.md), [`sales_team`](../sales_team/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
