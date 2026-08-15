---
layout: page
title: "Sale Mrp Margin (sale_mrp_margin)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_mrp_margin/
nav_order: 0
---
# Sale Mrp Margin — `sale_mrp_margin`

**Source:** [`agents/modules/generated/sale_mrp_margin.yaml`](../../agents/modules/generated/sale_mrp_margin.yaml) · **Wiki:** [`knowledge/modules/sale_mrp_margin/overview.md`](../../knowledge/modules/sale_mrp_margin/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_mrp_margin</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sale Mrp Margin</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_mrp_margin</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_mrp_margin"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`sale_mrp`](sale_mrp.md), [`sale_stock_margin`](sale_stock_margin.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.sale_mrp` | depends_on | `agents/modules/generated/sale_mrp.yaml` |
| `module.sale_stock_margin` | depends_on | `agents/modules/generated/sale_stock_margin.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_mrp_margin`](../../../agents/modules/generated/sale_mrp_margin.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_mrp_margin)
- Direct dependencies: [`sale_mrp`](../sale_mrp/overview.md), [`sale_stock_margin`](../sale_stock_margin/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:sale_mrp_margin`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.sale_mrp`](../../../agents/modules/generated/sale_mrp.yaml) — depends_on
- [`module.sale_stock_margin`](../../../agents/modules/generated/sale_stock_margin.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
