---
layout: page
title: "Sale Project - Sale Stock (sale_project_stock)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_project_stock/
nav_order: 0
---
# Sale Project - Sale Stock — `sale_project_stock`

**Source:** [`agents/modules/generated/sale_project_stock.yaml`](../../agents/modules/generated/sale_project_stock.yaml) · **Wiki:** [`knowledge/modules/sale_project_stock/overview.md`](../../knowledge/modules/sale_project_stock/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_project_stock</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sale Project - Sale Stock</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_project_stock</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_project_stock"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Adds a full traceability of inventory operations on the profitability report.

## Direct dependencies

[`sale_project`](sale_project.md), [`sale_stock`](sale_stock.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale_project_stock</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_project` | depends_on | `agents/modules/generated/sale_project.yaml` |
| `module.sale_stock` | depends_on | `agents/modules/generated/sale_stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_project_stock`](../../../agents/modules/generated/sale_project_stock.yaml)
- Domain: `sales_crm`
- Category: Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_project_stock)
- Direct dependencies: [`sale_project`](../sale_project/overview.md), [`sale_stock`](../sale_stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:sale_project_stock`](../../impact-graph.json)

## Purpose

Adds a full traceability of inventory operations on the profitability report.

## Model relationships

- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — depends_on
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
