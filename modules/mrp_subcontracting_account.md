---
layout: page
title: "Subcontracting Management with Stock Valuation (mrp_subcontracting_account)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mrp_subcontracting_account/
nav_order: 0
---
# Subcontracting Management with Stock Valuation — `mrp_subcontracting_account`

**Source:** [`agents/modules/generated/mrp_subcontracting_account.yaml`](../../agents/modules/generated/mrp_subcontracting_account.yaml) · **Wiki:** [`knowledge/modules/mrp_subcontracting_account/overview.md`](../../knowledge/modules/mrp_subcontracting_account/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mrp_subcontracting_account</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Subcontracting Management with Stock Valuation</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">manufacturing</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mrp_subcontracting_account</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_subcontracting_account"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`mrp_account`](mrp_account.md), [`mrp_subcontracting`](mrp_subcontracting.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mrp.production</code></div><div class="role">extended by <code>mrp_subcontracting_account</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>mrp_subcontracting_account</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>mrp_subcontracting_account</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>mrp_subcontracting_account</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mrp` | extends_model_from | `agents/modules/generated/mrp.yaml` |
| `module.mrp_account` | depends_on, extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.mrp_subcontracting` | depends_on, extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.stock` | extends_model_from | `agents/modules/generated/stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.mrp_subcontracting_account`](../../../agents/modules/generated/mrp_subcontracting_account.yaml)
- Domain: `manufacturing`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_subcontracting_account)
- Direct dependencies: [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:mrp_subcontracting_account`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `mrp.production` — defined by [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)

## Related SME agents

- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — depends_on, extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — depends_on, extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
