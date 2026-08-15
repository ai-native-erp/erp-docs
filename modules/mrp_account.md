---
layout: page
title: "Accounting - MRP (mrp_account)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mrp_account/
nav_order: 0
---
# Accounting - MRP — `mrp_account`

**Source:** [`agents/modules/generated/mrp_account.yaml`](../../agents/modules/generated/mrp_account.yaml) · **Wiki:** [`knowledge/modules/mrp_account/overview.md`](../../knowledge/modules/mrp_account/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mrp_account</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Accounting - MRP</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">manufacturing</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mrp_account</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_account"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Analytic accounting in Manufacturing

## Direct dependencies

[`mrp`](mrp.md), [`stock_account`](stock_account.md)

## Reverse dependencies (modules that depend on this)

[`mrp_subcontracting_account`](mrp_subcontracting_account.md), [`project_mrp`](project_mrp.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>mrp.bom</code></div><div class="role">defined by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>mrp.production</code></div><div class="role">defined by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>mrp.workcenter</code></div><div class="role">defined by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">defined by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">defined by <code>mrp_account</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.analytic.account</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>account.analytic.applicability</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>account.analytic.line</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>analytic.mixin</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>mrp.bom</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>mrp.production</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>mrp.routing.workcenter</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>mrp.workcenter</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>mrp.workorder</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>product.category</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>report.mrp.report_mo_overview</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>mrp_account</code></div></div>
<div class="model"><div class="name"><code>stock.rule</code></div><div class="role">extended by <code>mrp_account</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from, model_extended_by | `agents/modules/generated/account.yaml` |
| `module.analytic` | extends_model_from | `agents/modules/generated/analytic.yaml` |
| `module.event_booth_sale` | model_extended_by | `agents/modules/generated/event_booth_sale.yaml` |
| `module.event_sale` | model_extended_by | `agents/modules/generated/event_sale.yaml` |
| `module.hr_expense` | model_extended_by | `agents/modules/generated/hr_expense.yaml` |
| `module.l10n_de` | model_extended_by | `agents/modules/generated/l10n_de.yaml` |
| `module.l10n_eg_edi_eta` | model_extended_by | `agents/modules/generated/l10n_eg_edi_eta.yaml` |
| `module.l10n_gcc_invoice` | model_extended_by | `agents/modules/generated/l10n_gcc_invoice.yaml` |
| `module.l10n_hu_edi` | model_extended_by | `agents/modules/generated/l10n_hu_edi.yaml` |
| `module.l10n_id_efaktur_coretax` | model_extended_by | `agents/modules/generated/l10n_id_efaktur_coretax.yaml` |

## Full wiki excerpt

- SME owner: [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml)
- Domain: `manufacturing`
- Category: Manufacturing/Manufacturing
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_account)
- Direct dependencies: [`mrp`](../mrp/overview.md), [`stock_account`](../stock_account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`project_mrp`](../project_mrp/overview.md)
- Impact graph: [`module:mrp_account`](../../impact-graph.json)

## Purpose

Analytic accounting in Manufacturing

## Model relationships

- `mrp.bom` — extended by [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md), [`sale_mrp`](../sale_mrp/overview.md)
- `mrp.production` — extended by [`mrp`](../mrp/overview.md), [`mrp_product_expiry`](../mrp_product_expiry/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`project_mrp`](../project_mrp/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md), [`sale_mrp`](../sale_mrp/overview.md)
- `mrp.workcenter` — extended by [`mrp`](../mrp/overview.md)
- `product.product` — extended by [`account`](../account/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`loyalty`](../loyalty/overview.md), [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_sale_product_configurator`](../pos_sale_product_configurator/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`pos_self_order_sale`](../pos_self_order_sale/overview.md), [`product`](../product/overview.md), [`product_expiry`](../product_expiry/overview.md), [`product_images`](../product_images/overview.md), [`product_margin`](../product_margin/overview.md), [`purchase`](../purchase/overview.md), [`purchase_requisition`](../purchase_requisition/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale`](../sale/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_comparison`](../website_sale_comparison/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md)
- `product.template` — extended by [`account`](../account/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_cpv_code`](../l10n_ro_cpv_code/overview.md), [`loyalty`](../loyalty/overview.md), [`membership`](../membership/overview.md), [`mrp`](../mrp/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`product`](../product/overview.md), [`product_email_template`](../product_email_template/overview.md), [`product_expiry`](../product_expiry/overview.md), [`product_matrix`](../product_matrix/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_stock_wishlist`](../website_sale_stock_wishlist/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md)
- Extends `account.analytic.account` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.analytic.applicability` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.analytic.line` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `analytic.mixin` — defined by [`analytic`](../analytic/overview.md)
- Extends `mrp.bom` — defined by [`mrp`](../mrp/overview.md)
- Extends `mrp.production` — defined by [`mrp`](../mrp/overview.md)
- Extends `mrp.routing.workcenter` — defined by [`mrp`](../mrp/overview.md)
- Extends `mrp.workcenter` — defined by [`mrp`](../mrp/overview.md)
- Extends `mrp.workorder` — defined by [`mrp`](../mrp/overview.md)
- Extends `product.category` — defined by [`product`](../product/overview.md)
- Extends `product.product` — defined by [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `report.mrp.report_mo_overview` — defined by [`mrp`](../mrp/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.rule` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from, model_extended_by
- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — extends_model_from
- [`module.event_booth_sale`](../../../agents/modules/generated/event_booth_sale.yaml) — model_extended_by
- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — model_extended_by
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — model_extended_by
- [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml) — model_extended_by
- [`module.l10n_eg_edi_eta`](../../../agents/modules/generated/l10n_eg_edi_eta.yaml) — model_extended_by
- [`module.l10n_gcc_invoice`](../../../agents/modules/generated/l10n_gcc_invoice.yaml) — model_extended_by
- [`module.l10n_hu_edi`](../../../agents/modules/generated/l10n_hu_edi.yaml) — model_extended_by
- [`module.l10n_id_efaktur_coretax`](../../../agents/modules/generated/l10n_id_efaktur_coretax.yaml) — model_extended_by
- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — model_extended_by
- [`module.l10n_my_edi`](../../../agents/modules/generated/l10n_my_edi.yaml) — model_extended_by
- [`module.l10n_pl`](../../../agents/modules/generated/l10n_pl.yaml) — model_extended_by
- [`module.l10n_ro_cpv_code`](../../../agents/modules/generated/l10n_ro_cpv_code.yaml) — model_extended_by
- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — model_extended_by
- [`module.membership`](../../../agents/modules/generated/membership.yaml) — model_extended_by
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.mrp_product_expiry`](../../../agents/modules/generated/mrp_product_expiry.yaml) — model_extended_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — model_extended_by
- [`module.mrp_subcontracting_account`](../../../agents/modules/generated/mrp_subcontracting_account.yaml) — model_extended_by, required_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.pos_sale_product_configurator`](../../../agents/modules/generated/pos_sale_product_configurator.yaml) — model_extended_by
- [`module.pos_self_order`](../../../agents/modules/generated/pos_self_order.yaml) — model_extended_by
- [`module.pos_self_order_sale`](../../../agents/modules/generated/pos_self_order_sale.yaml) — model_extended_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from, model_extended_by
- [`module.product_email_template`](../../../agents/modules/generated/product_email_template.yaml) — model_extended_by
- [`module.product_expiry`](../../../agents/modules/generated/product_expiry.yaml) — model_extended_by
- [`module.product_images`](../../../agents/modules/generated/product_images.yaml) — model_extended_by
- [`module.product_margin`](../../../agents/modules/generated/product_margin.yaml) — model_extended_by
- [`module.product_matrix`](../../../agents/modules/generated/product_matrix.yaml) — model_extended_by
- [`module.project_mrp`](../../../agents/modules/generated/project_mrp.yaml) — model_extended_by, required_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from, model_extended_by
- [`module.purchase_mrp`](../../../agents/modules/generated/purchase_mrp.yaml) — model_extended_by
- [`module.purchase_requisition`](../../../agents/modules/generated/purchase_requisition.yaml) — model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from, model_extended_by
- [`module.repair`](../../../agents/modules/generated/repair.yaml) — model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — model_extended_by
- [`module.sale_expense`](../../../agents/modules/generated/sale_expense.yaml) — model_extended_by
- [`module.sale_mrp`](../../../agents/modules/generated/sale_mrp.yaml) — model_extended_by
- [`module.sale_product_configurator`](../../../agents/modules/generated/sale_product_configurator.yaml) — model_extended_by
- [`module.sale_product_matrix`](../../../agents/modules/generated/sale_product_matrix.yaml) — model_extended_by
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — model_extended_by
- [`module.sale_purchase`](../../../agents/modules/generated/sale_purchase.yaml) — model_extended_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — model_extended_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from, model_extended_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — model_extended_by
- [`module.stock_landed_costs`](../../../agents/modules/generated/stock_landed_costs.yaml) — model_extended_by
- [`module.website_event_booth_sale`](../../../agents/modules/generated/website_event_booth_sale.yaml) — model_extended_by
- [`module.website_event_sale`](../../../agents/modules/generated/website_event_sale.yaml) — model_extended_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from, model_extended_by
- [`module.website_sale_comparison`](../../../agents/modules/generated/website_sale_comparison.yaml) — model_extended_by
- [`module.website_sale_slides`](../../../agents/modules/generated/website_sale_slides.yaml) — model_extended_by
- [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml) — model_extended_by
- [`module.website_sale_stock_wishlist`](../../../agents/modules/generated/website_sale_stock_wishlist.yaml) — model_extended_by
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — model_extended_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_cpv_code`](../l10n_ro_cpv_code/overview.md), [`loyalty`](../loyalty/overview.md), [`membership`](../membership/overview.md), [`mrp`](../mrp/overview.md), [`mrp_product_expiry`](../mrp_product_expiry/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_sale_product_configurator`](../pos_sale_product_configurator/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`pos_self_order_sale`](../pos_self_order_sale/overview.md), [`product`](../product/overview.md), [`product_email_template`](../product_email_template/overview.md), [`product_expiry`](../product_expiry/overview.md), [`product_images`](../product_images/overview.md), [`product_margin`](../product_margin/overview.md), [`product_matrix`](../product_matrix/overview.md), [`project_mrp`](../project_mrp/overview.md), [`purchase`](../purchase/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md), [`purchase_requisition`](../purchase_requisition/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_mrp`](../sale_mrp/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_comparison`](../website_sale_comparison/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_stock_wishlist`](../website_sale_stock_wishlist/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`analytic`](../analytic/overview.md), [`mrp`](../mrp/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
