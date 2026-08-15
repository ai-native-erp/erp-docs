---
layout: page
title: "POS Self Order Epson Printer (pos_self_order_epson_printer)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_self_order_epson_printer/
nav_order: 0
---
# POS Self Order Epson Printer — `pos_self_order_epson_printer`

**Source:** [`agents/modules/generated/pos_self_order_epson_printer.yaml`](../../agents/modules/generated/pos_self_order_epson_printer.yaml) · **Wiki:** [`knowledge/modules/pos_self_order_epson_printer/overview.md`](../../knowledge/modules/pos_self_order_epson_printer/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_self_order_epson_printer</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">POS Self Order Epson Printer</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_self_order_epson_printer</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_self_order_epson_printer"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Epson ePOS Printers in PoS Kiosk

## Direct dependencies

[`pos_epson_printer`](pos_epson_printer.md), [`pos_self_order`](pos_self_order.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.config</code></div><div class="role">extended by <code>pos_self_order_epson_printer</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.point_of_sale` | extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.pos_epson_printer` | depends_on | `agents/modules/generated/pos_epson_printer.yaml` |
| `module.pos_self_order` | depends_on | `agents/modules/generated/pos_self_order.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_self_order_epson_printer`](../../../agents/modules/generated/pos_self_order_epson_printer.yaml)
- Domain: `point_of_sale`
- Category: Sales/Point of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_self_order_epson_printer)
- Direct dependencies: [`pos_epson_printer`](../pos_epson_printer/overview.md), [`pos_self_order`](../pos_self_order/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:pos_self_order_epson_printer`](../../impact-graph.json)

## Purpose

Epson ePOS Printers in PoS Kiosk

## Model relationships

- Extends `pos.config` — defined by [`point_of_sale`](../point_of_sale/overview.md)

## Related SME agents

- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — extends_model_from
- [`module.pos_epson_printer`](../../../agents/modules/generated/pos_epson_printer.yaml) — depends_on
- [`module.pos_self_order`](../../../agents/modules/generated/pos_self_order.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`point_of_sale`](../point_of_sale/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
