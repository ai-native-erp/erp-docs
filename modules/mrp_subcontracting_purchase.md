---
layout: page
title: "Purchase and Subcontracting Management (mrp_subcontracting_purchase)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mrp_subcontracting_purchase/
nav_order: 0
---
# Purchase and Subcontracting Management — `mrp_subcontracting_purchase`

**Source:** [`agents/modules/generated/mrp_subcontracting_purchase.yaml`](../../agents/modules/generated/mrp_subcontracting_purchase.yaml) · **Wiki:** [`knowledge/modules/mrp_subcontracting_purchase/overview.md`](../../knowledge/modules/mrp_subcontracting_purchase/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mrp_subcontracting_purchase</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Purchase and Subcontracting Management</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">manufacturing</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mrp_subcontracting_purchase</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_subcontracting_purchase"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`mrp_subcontracting`](mrp_subcontracting.md), [`purchase_mrp`](purchase_mrp.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>mrp_subcontracting_purchase</code></div></div>
<div class="model"><div class="name"><code>purchase.order</code></div><div class="role">extended by <code>mrp_subcontracting_purchase</code></div></div>
<div class="model"><div class="name"><code>report.mrp.report_bom_structure</code></div><div class="role">extended by <code>mrp_subcontracting_purchase</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>mrp_subcontracting_purchase</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>mrp_subcontracting_purchase</code></div></div>
<div class="model"><div class="name"><code>stock.rule</code></div><div class="role">extended by <code>mrp_subcontracting_purchase</code></div></div>
<div class="model"><div class="name"><code>stock.valuation.layer</code></div><div class="role">extended by <code>mrp_subcontracting_purchase</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.mrp` | extends_model_from | `agents/modules/generated/mrp.yaml` |
| `module.mrp_subcontracting` | depends_on, extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_mrp` | depends_on | `agents/modules/generated/purchase_mrp.yaml` |
| `module.stock` | extends_model_from | `agents/modules/generated/stock.yaml` |
| `module.stock_account` | extends_model_from | `agents/modules/generated/stock_account.yaml` |

## Full wiki excerpt

- SME owner: [`module.mrp_subcontracting_purchase`](../../../agents/modules/generated/mrp_subcontracting_purchase.yaml)
- Domain: `manufacturing`
- Category: Manufacturing/Purchase
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_subcontracting_purchase)
- Direct dependencies: [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:mrp_subcontracting_purchase`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `purchase.order` — defined by [`purchase`](../purchase/overview.md)
- Extends `report.mrp.report_bom_structure` — defined by [`mrp`](../mrp/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)
- Extends `stock.rule` — defined by [`stock`](../stock/overview.md)
- Extends `stock.valuation.layer` — defined by [`stock_account`](../stock_account/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — depends_on, extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_mrp`](../../../agents/modules/generated/purchase_mrp.yaml) — depends_on
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`purchase`](../purchase/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
