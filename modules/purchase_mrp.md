---
layout: page
title: "Purchase and MRP Management (purchase_mrp)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/purchase_mrp/
nav_order: 0
---
# Purchase and MRP Management — `purchase_mrp`

**Source:** [`agents/modules/generated/purchase_mrp.yaml`](../../agents/modules/generated/purchase_mrp.yaml) · **Wiki:** [`knowledge/modules/purchase_mrp/overview.md`](../../knowledge/modules/purchase_mrp/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>purchase_mrp</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Purchase and MRP Management</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/purchase_mrp</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/purchase_mrp"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`mrp`](mrp.md), [`purchase_stock`](purchase_stock.md)

## Reverse dependencies (modules that depend on this)

[`mrp_subcontracting_purchase`](mrp_subcontracting_purchase.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>purchase_mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.bom</code></div><div class="role">extended by <code>purchase_mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.bom.line</code></div><div class="role">extended by <code>purchase_mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.production</code></div><div class="role">extended by <code>purchase_mrp</code></div></div>
<div class="model"><div class="name"><code>purchase.order</code></div><div class="role">extended by <code>purchase_mrp</code></div></div>
<div class="model"><div class="name"><code>purchase.order.line</code></div><div class="role">extended by <code>purchase_mrp</code></div></div>
<div class="model"><div class="name"><code>report.mrp.report_bom_structure</code></div><div class="role">extended by <code>purchase_mrp</code></div></div>
<div class="model"><div class="name"><code>report.mrp.report_mo_overview</code></div><div class="role">extended by <code>purchase_mrp</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>purchase_mrp</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.mrp` | depends_on, extends_model_from | `agents/modules/generated/mrp.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.mrp_subcontracting_purchase` | required_by | `agents/modules/generated/mrp_subcontracting_purchase.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | depends_on | `agents/modules/generated/purchase_stock.yaml` |
| `module.stock` | extends_model_from | `agents/modules/generated/stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.purchase_mrp`](../../../agents/modules/generated/purchase_mrp.yaml)
- Domain: `inventory_purchase`
- Category: Inventory/Purchase
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/purchase_mrp)
- Direct dependencies: [`mrp`](../mrp/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md)
- Impact graph: [`module:purchase_mrp`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `mrp.bom` — defined by [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md)
- Extends `mrp.bom.line` — defined by [`mrp`](../mrp/overview.md)
- Extends `mrp.production` — defined by [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md)
- Extends `purchase.order` — defined by [`purchase`](../purchase/overview.md)
- Extends `purchase.order.line` — defined by [`purchase`](../purchase/overview.md)
- Extends `report.mrp.report_bom_structure` — defined by [`mrp`](../mrp/overview.md)
- Extends `report.mrp.report_mo_overview` — defined by [`mrp`](../mrp/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — depends_on, extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.mrp_subcontracting_purchase`](../../../agents/modules/generated/mrp_subcontracting_purchase.yaml) — required_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — depends_on
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`purchase`](../purchase/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
