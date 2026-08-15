---
layout: page
title: "Purchase Matrix (purchase_product_matrix)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/purchase_product_matrix/
nav_order: 0
---
# Purchase Matrix — `purchase_product_matrix`

**Source:** [`agents/modules/generated/purchase_product_matrix.yaml`](../../agents/modules/generated/purchase_product_matrix.yaml) · **Wiki:** [`knowledge/modules/purchase_product_matrix/overview.md`](../../knowledge/modules/purchase_product_matrix/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>purchase_product_matrix</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Purchase Matrix</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/purchase_product_matrix</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/purchase_product_matrix"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Add variants to your purchase orders through an Order Grid Entry.

## Direct dependencies

[`product_matrix`](product_matrix.md), [`purchase`](purchase.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>purchase.order</code></div><div class="role">extended by <code>purchase_product_matrix</code></div></div>
<div class="model"><div class="name"><code>purchase.order.line</code></div><div class="role">extended by <code>purchase_product_matrix</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.product_matrix` | depends_on | `agents/modules/generated/product_matrix.yaml` |
| `module.purchase` | depends_on, extends_model_from | `agents/modules/generated/purchase.yaml` |

## Full wiki excerpt

- SME owner: [`module.purchase_product_matrix`](../../../agents/modules/generated/purchase_product_matrix.yaml)
- Domain: `inventory_purchase`
- Category: Inventory/Purchase
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/purchase_product_matrix)
- Direct dependencies: [`product_matrix`](../product_matrix/overview.md), [`purchase`](../purchase/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:purchase_product_matrix`](../../impact-graph.json)

## Purpose

Add variants to your purchase orders through an Order Grid Entry.

## Model relationships

- Extends `purchase.order` — defined by [`purchase`](../purchase/overview.md)
- Extends `purchase.order.line` — defined by [`purchase`](../purchase/overview.md)

## Related SME agents

- [`module.product_matrix`](../../../agents/modules/generated/product_matrix.yaml) — depends_on
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`purchase`](../purchase/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
