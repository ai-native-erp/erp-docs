---
layout: page
title: "India Sales and Warehouse Management (l10n_in_sale_stock)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_in_sale_stock/
nav_order: 0
---
# India Sales and Warehouse Management — `l10n_in_sale_stock`

**Source:** [`agents/modules/generated/l10n_in_sale_stock.yaml`](../../agents/modules/generated/l10n_in_sale_stock.yaml) · **Wiki:** [`knowledge/modules/l10n_in_sale_stock/overview.md`](../../knowledge/modules/l10n_in_sale_stock/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_in_sale_stock</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">India Sales and Warehouse Management</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_in_sale_stock</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_in_sale_stock"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Get warehouse address if the invoice is created from Sale Order

## Direct dependencies

[`l10n_in_sale`](l10n_in_sale.md), [`l10n_in_stock`](l10n_in_stock.md), [`sale_stock`](sale_stock.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_in_sale_stock</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>l10n_in_sale_stock</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>l10n_in_sale_stock</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.l10n_in_sale` | depends_on | `agents/modules/generated/l10n_in_sale.yaml` |
| `module.l10n_in_stock` | depends_on | `agents/modules/generated/l10n_in_stock.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sale_stock` | depends_on | `agents/modules/generated/sale_stock.yaml` |
| `module.stock` | extends_model_from | `agents/modules/generated/stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_in_sale_stock`](../../../agents/modules/generated/l10n_in_sale_stock.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_in_sale_stock)
- Direct dependencies: [`l10n_in_sale`](../l10n_in_sale/overview.md), [`l10n_in_stock`](../l10n_in_stock/overview.md), [`sale_stock`](../sale_stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_in_sale_stock`](../../impact-graph.json)

## Purpose

Get warehouse address if the invoice is created from Sale Order

## Model relationships

- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.l10n_in_sale`](../../../agents/modules/generated/l10n_in_sale.yaml) — depends_on
- [`module.l10n_in_stock`](../../../agents/modules/generated/l10n_in_stock.yaml) — depends_on
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — depends_on
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`sale`](../sale/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
