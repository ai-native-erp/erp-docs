---
layout: page
title: "MTO Sale <-> Purchase (sale_purchase_stock)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_purchase_stock/
nav_order: 0
---
# MTO Sale <-> Purchase — `sale_purchase_stock`

**Source:** [`agents/modules/generated/sale_purchase_stock.yaml`](../../agents/modules/generated/sale_purchase_stock.yaml) · **Wiki:** [`knowledge/modules/sale_purchase_stock/overview.md`](../../knowledge/modules/sale_purchase_stock/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_purchase_stock</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">MTO Sale <-> Purchase</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_purchase_stock</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_purchase_stock"><code>126b5bd</code></a></div></div>
</div>
## Purpose

SO/PO relation in case of MTO

## Direct dependencies

[`purchase_stock`](purchase_stock.md), [`sale_purchase`](sale_purchase.md), [`sale_stock`](sale_stock.md)

## Reverse dependencies (modules that depend on this)

[`stock_dropshipping`](stock_dropshipping.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>purchase.order</code></div><div class="role">extended by <code>sale_purchase_stock</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_purchase_stock</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | depends_on | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_purchase` | depends_on | `agents/modules/generated/sale_purchase.yaml` |
| `module.sale_stock` | depends_on | `agents/modules/generated/sale_stock.yaml` |
| `module.stock_dropshipping` | required_by | `agents/modules/generated/stock_dropshipping.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_purchase_stock`](../../../agents/modules/generated/sale_purchase_stock.yaml)
- Domain: `sales_crm`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_purchase_stock)
- Direct dependencies: [`purchase_stock`](../purchase_stock/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_stock`](../sale_stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`stock_dropshipping`](../stock_dropshipping/overview.md)
- Impact graph: [`module:sale_purchase_stock`](../../impact-graph.json)

## Purpose

SO/PO relation in case of MTO

## Model relationships

- Extends `purchase.order` — defined by [`purchase`](../purchase/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — depends_on
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_purchase`](../../../agents/modules/generated/sale_purchase.yaml) — depends_on
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — depends_on
- [`module.stock_dropshipping`](../../../agents/modules/generated/stock_dropshipping.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`purchase`](../purchase/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
