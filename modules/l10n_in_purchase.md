---
layout: page
title: "Indian - Purchase Report(GST) (l10n_in_purchase)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_in_purchase/
nav_order: 0
---
# Indian - Purchase Report(GST) — `l10n_in_purchase`

**Source:** [`agents/modules/generated/l10n_in_purchase.yaml`](../../agents/modules/generated/l10n_in_purchase.yaml) · **Wiki:** [`knowledge/modules/l10n_in_purchase/overview.md`](../../knowledge/modules/l10n_in_purchase/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_in_purchase</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Indian - Purchase Report(GST)</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_in_purchase</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_in_purchase"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_in`](l10n_in.md), [`purchase`](purchase.md)

## Reverse dependencies (modules that depend on this)

[`l10n_in_purchase_stock`](l10n_in_purchase_stock.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_in_purchase</code></div></div>
<div class="model"><div class="name"><code>purchase.order</code></div><div class="role">extended by <code>l10n_in_purchase</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.l10n_in` | depends_on | `agents/modules/generated/l10n_in.yaml` |
| `module.l10n_in_purchase_stock` | required_by | `agents/modules/generated/l10n_in_purchase_stock.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.purchase` | depends_on, extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_in_purchase`](../../../agents/modules/generated/l10n_in_purchase.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Purchase
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_in_purchase)
- Direct dependencies: [`l10n_in`](../l10n_in/overview.md), [`purchase`](../purchase/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md)
- Impact graph: [`module:l10n_in_purchase`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `purchase.order` — defined by [`purchase`](../purchase/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — depends_on
- [`module.l10n_in_purchase_stock`](../../../agents/modules/generated/l10n_in_purchase_stock.yaml) — required_by
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — depends_on, extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`purchase`](../purchase/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
