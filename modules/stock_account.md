---
layout: page
title: "WMS Accounting (stock_account)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/stock_account/
nav_order: 0
---
# WMS Accounting — `stock_account`

**Source:** [`agents/modules/generated/stock_account.yaml`](../../agents/modules/generated/stock_account.yaml) · **Wiki:** [`knowledge/modules/stock_account/overview.md`](../../knowledge/modules/stock_account/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>stock_account</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">WMS Accounting</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/stock_account</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock_account"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Inventory, Logistic, Valuation, Accounting

## Direct dependencies

[`account`](account.md), [`stock`](stock.md)

## Reverse dependencies (modules that depend on this)

[`l10n_gcc_invoice_stock_account`](l10n_gcc_invoice_stock_account.md), [`l10n_it_stock_ddt`](l10n_it_stock_ddt.md), [`mrp_account`](mrp_account.md), [`point_of_sale`](point_of_sale.md), [`purchase_stock`](purchase_stock.md), [`sale_stock`](sale_stock.md), [`spreadsheet_dashboard_stock_account`](spreadsheet_dashboard_stock_account.md), [`stock_landed_costs`](stock_landed_costs.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.template</code></div><div class="role">defined by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>stock.valuation.layer</code></div><div class="role">defined by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>stock.valuation.layer.revaluation</code></div><div class="role">defined by <code>stock_account</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.analytic.account</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>account.analytic.plan</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>product.category</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>stock.forecasted_product_product</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>stock.location</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>stock.move.line</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>stock.quant</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>stock.quantity.history</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>stock.request.count</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>stock.return.picking</code></div><div class="role">extended by <code>stock_account</code></div></div>
<div class="model"><div class="name"><code>stock.return.picking.line</code></div><div class="role">extended by <code>stock_account</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from, model_extended_by | `agents/modules/generated/account.yaml` |
| `module.analytic` | extends_model_from | `agents/modules/generated/analytic.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.event_booth_sale` | model_extended_by | `agents/modules/generated/event_booth_sale.yaml` |
| `module.event_sale` | model_extended_by | `agents/modules/generated/event_sale.yaml` |
| `module.hr_expense` | model_extended_by | `agents/modules/generated/hr_expense.yaml` |
| `module.l10n_de` | model_extended_by | `agents/modules/generated/l10n_de.yaml` |
| `module.l10n_eg_edi_eta` | model_extended_by | `agents/modules/generated/l10n_eg_edi_eta.yaml` |
| `module.l10n_gcc_invoice_stock_account` | required_by | `agents/modules/generated/l10n_gcc_invoice_stock_account.yaml` |
| `module.l10n_hu_edi` | model_extended_by | `agents/modules/generated/l10n_hu_edi.yaml` |

## Full wiki excerpt

- SME owner: [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml)
- Domain: `inventory_purchase`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock_account)
- Direct dependencies: [`account`](../account/overview.md), [`stock`](../stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_gcc_invoice_stock_account`](../l10n_gcc_invoice_stock_account/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`mrp_account`](../mrp_account/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale_stock`](../sale_stock/overview.md), [`spreadsheet_dashboard_stock_account`](../spreadsheet_dashboard_stock_account/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md)
- Impact graph: [`module:stock_account`](../../impact-graph.json)

## Purpose

Inventory, Logistic, Valuation, Accounting

## Model relationships

- `product.template` — extended by [`account`](../account/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_cpv_code`](../l10n_ro_cpv_code/overview.md), [`loyalty`](../loyalty/overview.md), [`membership`](../membership/overview.md), [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`product`](../product/overview.md), [`product_email_template`](../product_email_template/overview.md), [`product_expiry`](../product_expiry/overview.md), [`product_matrix`](../product_matrix/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock`](../stock/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_stock_wishlist`](../website_sale_stock_wishlist/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md)
- `stock.valuation.layer` — extended by [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale_stock`](../sale_stock/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md)
- `stock.valuation.layer.revaluation`
- Extends `account.analytic.account` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.analytic.plan` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `product.category` — defined by [`product`](../product/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `stock.forecasted_product_product` — defined by [`stock`](../stock/overview.md)
- Extends `stock.location` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move.line` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)
- Extends `stock.quant` — defined by [`stock`](../stock/overview.md)
- Extends `stock.quantity.history` — defined by [`stock`](../stock/overview.md)
- Extends `stock.request.count` — defined by [`stock`](../stock/overview.md)
- Extends `stock.return.picking` — defined by [`stock`](../stock/overview.md)
- Extends `stock.return.picking.line` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.event_booth_sale`](../../../agents/modules/generated/event_booth_sale.yaml) — model_extended_by
- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — model_extended_by
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — model_extended_by
- [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml) — model_extended_by
- [`module.l10n_eg_edi_eta`](../../../agents/modules/generated/l10n_eg_edi_eta.yaml) — model_extended_by
- [`module.l10n_gcc_invoice_stock_account`](../../../agents/modules/generated/l10n_gcc_invoice_stock_account.yaml) — required_by
- [`module.l10n_hu_edi`](../../../agents/modules/generated/l10n_hu_edi.yaml) — model_extended_by
- [`module.l10n_id_efaktur_coretax`](../../../agents/modules/generated/l10n_id_efaktur_coretax.yaml) — model_extended_by
- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — model_extended_by
- [`module.l10n_it_stock_ddt`](../../../agents/modules/generated/l10n_it_stock_ddt.yaml) — required_by
- [`module.l10n_my_edi`](../../../agents/modules/generated/l10n_my_edi.yaml) — model_extended_by
- [`module.l10n_pl`](../../../agents/modules/generated/l10n_pl.yaml) — model_extended_by
- [`module.l10n_ro_cpv_code`](../../../agents/modules/generated/l10n_ro_cpv_code.yaml) — model_extended_by
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — model_extended_by
- [`module.membership`](../../../agents/modules/generated/membership.yaml) — model_extended_by
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — model_extended_by
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from, model_extended_by, required_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.mrp_subcontracting_purchase`](../../../agents/modules/generated/mrp_subcontracting_purchase.yaml) — model_extended_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by, required_by
- [`module.pos_self_order`](../../../agents/modules/generated/pos_self_order.yaml) — model_extended_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from, model_extended_by
- [`module.product_email_template`](../../../agents/modules/generated/product_email_template.yaml) — model_extended_by
- [`module.product_expiry`](../../../agents/modules/generated/product_expiry.yaml) — model_extended_by
- [`module.product_matrix`](../../../agents/modules/generated/product_matrix.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from, model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from, model_extended_by, required_by
- [`module.repair`](../../../agents/modules/generated/repair.yaml) — model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from, model_extended_by
- [`module.sale_expense`](../../../agents/modules/generated/sale_expense.yaml) — model_extended_by
- [`module.sale_product_configurator`](../../../agents/modules/generated/sale_product_configurator.yaml) — model_extended_by
- [`module.sale_product_matrix`](../../../agents/modules/generated/sale_product_matrix.yaml) — model_extended_by
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — model_extended_by
- [`module.sale_purchase`](../../../agents/modules/generated/sale_purchase.yaml) — model_extended_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by, required_by
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — model_extended_by
- [`module.spreadsheet_dashboard_stock_account`](../../../agents/modules/generated/spreadsheet_dashboard_stock_account.yaml) — required_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — model_extended_by
- [`module.stock_landed_costs`](../../../agents/modules/generated/stock_landed_costs.yaml) — model_extended_by, required_by
- [`module.website_event_booth_sale`](../../../agents/modules/generated/website_event_booth_sale.yaml) — model_extended_by
- [`module.website_event_sale`](../../../agents/modules/generated/website_event_sale.yaml) — model_extended_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from, model_extended_by
- [`module.website_sale_slides`](../../../agents/modules/generated/website_sale_slides.yaml) — model_extended_by
- [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml) — model_extended_by
- [`module.website_sale_stock_wishlist`](../../../agents/modules/generated/website_sale_stock_wishlist.yaml) — model_extended_by
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — model_extended_by

## Regression impact checklist

- Review 8 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_cpv_code`](../l10n_ro_cpv_code/overview.md), [`loyalty`](../loyalty/overview.md), [`membership`](../membership/overview.md), [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`product`](../product/overview.md), [`product_email_template`](../product_email_template/overview.md), [`product_expiry`](../product_expiry/overview.md), [`product_matrix`](../product_matrix/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock`](../stock/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_stock_wishlist`](../website_sale_stock_wishlist/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`analytic`](../analytic/overview.md), [`base`](../base/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock`](../stock/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
