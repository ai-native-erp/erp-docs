---
layout: page
title: "G.C.C. - Arabic/English Invoice (l10n_gcc_invoice)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_gcc_invoice/
nav_order: 0
---
# G.C.C. - Arabic/English Invoice — `l10n_gcc_invoice`

**Source:** [`agents/modules/generated/l10n_gcc_invoice.yaml`](../../agents/modules/generated/l10n_gcc_invoice.yaml) · **Wiki:** [`knowledge/modules/l10n_gcc_invoice/overview.md`](../../knowledge/modules/l10n_gcc_invoice/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_gcc_invoice</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">G.C.C. - Arabic/English Invoice</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_gcc_invoice</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_gcc_invoice"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md)

## Reverse dependencies (modules that depend on this)

[`l10n_gcc_invoice_stock_account`](l10n_gcc_invoice_stock_account.md), [`l10n_gcc_pos`](l10n_gcc_pos.md), [`l10n_sa`](l10n_sa.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_gcc_invoice</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>l10n_gcc_invoice</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>l10n_gcc_invoice</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.l10n_gcc_invoice_stock_account` | required_by | `agents/modules/generated/l10n_gcc_invoice_stock_account.yaml` |
| `module.l10n_gcc_pos` | required_by | `agents/modules/generated/l10n_gcc_pos.yaml` |
| `module.l10n_sa` | required_by | `agents/modules/generated/l10n_sa.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_gcc_invoice`](../../../agents/modules/generated/l10n_gcc_invoice.yaml)
- Domain: `localization`
- Category: Accounting/Localizations
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_gcc_invoice)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_gcc_invoice_stock_account`](../l10n_gcc_invoice_stock_account/overview.md), [`l10n_gcc_pos`](../l10n_gcc_pos/overview.md), [`l10n_sa`](../l10n_sa/overview.md)
- Impact graph: [`module:l10n_gcc_invoice`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.l10n_gcc_invoice_stock_account`](../../../agents/modules/generated/l10n_gcc_invoice_stock_account.yaml) — required_by
- [`module.l10n_gcc_pos`](../../../agents/modules/generated/l10n_gcc_pos.yaml) — required_by
- [`module.l10n_sa`](../../../agents/modules/generated/l10n_sa.yaml) — required_by
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
