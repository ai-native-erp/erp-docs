---
layout: page
title: "WMS Landed Costs (stock_landed_costs)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/stock_landed_costs/
nav_order: 0
---
# WMS Landed Costs — `stock_landed_costs`

**Source:** [`agents/modules/generated/stock_landed_costs.yaml`](../../agents/modules/generated/stock_landed_costs.yaml) · **Wiki:** [`knowledge/modules/stock_landed_costs/overview.md`](../../knowledge/modules/stock_landed_costs/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>stock_landed_costs</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">WMS Landed Costs</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/stock_landed_costs</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock_landed_costs"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Landed Costs

## Direct dependencies

[`purchase_stock`](purchase_stock.md), [`stock_account`](stock_account.md)

## Reverse dependencies (modules that depend on this)

[`mrp_landed_costs`](mrp_landed_costs.md), [`mrp_subonctracting_landed_costs`](mrp_subonctracting_landed_costs.md), [`stock_landed_costs_company`](stock_landed_costs_company.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>stock.landed.cost</code></div><div class="role">defined by <code>stock_landed_costs</code></div></div>
<div class="model"><div class="name"><code>stock.landed.cost.lines</code></div><div class="role">defined by <code>stock_landed_costs</code></div></div>
<div class="model"><div class="name"><code>stock.valuation.adjustment.lines</code></div><div class="role">defined by <code>stock_landed_costs</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>stock_landed_costs</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>stock_landed_costs</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>stock_landed_costs</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>stock_landed_costs</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>stock_landed_costs</code></div></div>
<div class="model"><div class="name"><code>purchase.order.line</code></div><div class="role">extended by <code>stock_landed_costs</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>stock_landed_costs</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>stock_landed_costs</code></div></div>
<div class="model"><div class="name"><code>stock.valuation.layer</code></div><div class="role">extended by <code>stock_landed_costs</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.mrp_landed_costs` | model_extended_by, required_by | `agents/modules/generated/mrp_landed_costs.yaml` |
| `module.mrp_subonctracting_landed_costs` | required_by | `agents/modules/generated/mrp_subonctracting_landed_costs.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |

## Full wiki excerpt

- SME owner: [`module.stock_landed_costs`](../../../agents/modules/generated/stock_landed_costs.yaml)
- Domain: `inventory_purchase`
- Category: Inventory/Inventory
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock_landed_costs)
- Direct dependencies: [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`mrp_landed_costs`](../mrp_landed_costs/overview.md), [`mrp_subonctracting_landed_costs`](../mrp_subonctracting_landed_costs/overview.md), [`stock_landed_costs_company`](../stock_landed_costs_company/overview.md)
- Impact graph: [`module:stock_landed_costs`](../../impact-graph.json)

## Purpose

Landed Costs

## Model relationships

- `stock.landed.cost` — extended by [`mrp_landed_costs`](../mrp_landed_costs/overview.md), [`stock_landed_costs_company`](../stock_landed_costs_company/overview.md)
- `stock.landed.cost.lines`
- `stock.valuation.adjustment.lines`
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `purchase.order.line` — defined by [`purchase`](../purchase/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `stock.valuation.layer` — defined by [`stock_account`](../stock_account/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.mrp_landed_costs`](../../../agents/modules/generated/mrp_landed_costs.yaml) — model_extended_by, required_by
- [`module.mrp_subonctracting_landed_costs`](../../../agents/modules/generated/mrp_subonctracting_landed_costs.yaml) — required_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — depends_on, extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — depends_on, extends_model_from
- [`module.stock_landed_costs_company`](../../../agents/modules/generated/stock_landed_costs_company.yaml) — model_extended_by, required_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`mrp_landed_costs`](../mrp_landed_costs/overview.md), [`stock_landed_costs_company`](../stock_landed_costs_company/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`mrp_account`](../mrp_account/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
