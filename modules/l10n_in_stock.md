---
layout: page
title: "Indian - Stock Report(GST) (l10n_in_stock)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_in_stock/
nav_order: 0
---
# Indian - Stock Report(GST) — `l10n_in_stock`

**Source:** [`agents/modules/generated/l10n_in_stock.yaml`](../../agents/modules/generated/l10n_in_stock.yaml) · **Wiki:** [`knowledge/modules/l10n_in_stock/overview.md`](../../knowledge/modules/l10n_in_stock/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_in_stock</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Indian - Stock Report(GST)</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_in_stock</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_in_stock"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_in`](l10n_in.md), [`stock`](stock.md)

## Reverse dependencies (modules that depend on this)

[`l10n_in_ewaybill_stock`](l10n_in_ewaybill_stock.md), [`l10n_in_purchase_stock`](l10n_in_purchase_stock.md), [`l10n_in_sale_stock`](l10n_in_sale_stock.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>l10n_in_stock</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>l10n_in_stock</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_in` | depends_on | `agents/modules/generated/l10n_in.yaml` |
| `module.l10n_in_ewaybill_stock` | required_by | `agents/modules/generated/l10n_in_ewaybill_stock.yaml` |
| `module.l10n_in_purchase_stock` | required_by | `agents/modules/generated/l10n_in_purchase_stock.yaml` |
| `module.l10n_in_sale_stock` | required_by | `agents/modules/generated/l10n_in_sale_stock.yaml` |
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.stock` | depends_on, extends_model_from | `agents/modules/generated/stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_in_stock`](../../../agents/modules/generated/l10n_in_stock.yaml)
- Domain: `localization`
- Category: Accounting/Localizations
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_in_stock)
- Direct dependencies: [`l10n_in`](../l10n_in/overview.md), [`stock`](../stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_in_ewaybill_stock`](../l10n_in_ewaybill_stock/overview.md), [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md), [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md)
- Impact graph: [`module:l10n_in_stock`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)

## Related SME agents

- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — depends_on
- [`module.l10n_in_ewaybill_stock`](../../../agents/modules/generated/l10n_in_ewaybill_stock.yaml) — required_by
- [`module.l10n_in_purchase_stock`](../../../agents/modules/generated/l10n_in_purchase_stock.yaml) — required_by
- [`module.l10n_in_sale_stock`](../../../agents/modules/generated/l10n_in_sale_stock.yaml) — required_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
