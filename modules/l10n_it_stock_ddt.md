---
layout: page
title: "Italy - Stock DDT (l10n_it_stock_ddt)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_it_stock_ddt/
nav_order: 0
---
# Italy - Stock DDT — `l10n_it_stock_ddt`

**Source:** [`agents/modules/generated/l10n_it_stock_ddt.yaml`](../../agents/modules/generated/l10n_it_stock_ddt.yaml) · **Wiki:** [`knowledge/modules/l10n_it_stock_ddt/overview.md`](../../knowledge/modules/l10n_it_stock_ddt/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_it_stock_ddt</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Italy - Stock DDT</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_it_stock_ddt</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_it_stock_ddt"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_it_edi`](l10n_it_edi.md), [`stock_account`](stock_account.md), [`stock_delivery`](stock_delivery.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_it_stock_ddt</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>l10n_it_stock_ddt</code></div></div>
<div class="model"><div class="name"><code>stock.picking.type</code></div><div class="role">extended by <code>l10n_it_stock_ddt</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.l10n_it_edi` | depends_on | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.stock` | extends_model_from | `agents/modules/generated/stock.yaml` |
| `module.stock_account` | depends_on | `agents/modules/generated/stock_account.yaml` |
| `module.stock_delivery` | depends_on | `agents/modules/generated/stock_delivery.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_it_stock_ddt`](../../../agents/modules/generated/l10n_it_stock_ddt.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/EDI
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_it_stock_ddt)
- Direct dependencies: [`l10n_it_edi`](../l10n_it_edi/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_it_stock_ddt`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)
- Extends `stock.picking.type` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — depends_on
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — depends_on
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`sale`](../sale/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
