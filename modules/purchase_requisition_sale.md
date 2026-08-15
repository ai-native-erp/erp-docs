---
layout: page
title: "Purchase Requisition Sale (purchase_requisition_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/purchase_requisition_sale/
nav_order: 0
---
# Purchase Requisition Sale — `purchase_requisition_sale`

**Source:** [`agents/modules/generated/purchase_requisition_sale.yaml`](../../agents/modules/generated/purchase_requisition_sale.yaml) · **Wiki:** [`knowledge/modules/purchase_requisition_sale/overview.md`](../../knowledge/modules/purchase_requisition_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>purchase_requisition_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Purchase Requisition Sale</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/purchase_requisition_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/purchase_requisition_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`purchase_requisition`](purchase_requisition.md), [`sale_purchase`](sale_purchase.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>purchase.requisition.create.alternative</code></div><div class="role">extended by <code>purchase_requisition_sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.purchase_requisition` | depends_on, extends_model_from | `agents/modules/generated/purchase_requisition.yaml` |
| `module.sale_purchase` | depends_on | `agents/modules/generated/sale_purchase.yaml` |

## Full wiki excerpt

- SME owner: [`module.purchase_requisition_sale`](../../../agents/modules/generated/purchase_requisition_sale.yaml)
- Domain: `inventory_purchase`
- Category: Inventory/Purchase
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/purchase_requisition_sale)
- Direct dependencies: [`purchase_requisition`](../purchase_requisition/overview.md), [`sale_purchase`](../sale_purchase/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:purchase_requisition_sale`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `purchase.requisition.create.alternative` — defined by [`purchase_requisition`](../purchase_requisition/overview.md)

## Related SME agents

- [`module.purchase_requisition`](../../../agents/modules/generated/purchase_requisition.yaml) — depends_on, extends_model_from
- [`module.sale_purchase`](../../../agents/modules/generated/sale_purchase.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`purchase_requisition`](../purchase_requisition/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
