---
layout: page
title: "Products & Pricelists (product)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/product/
nav_order: 0
---
# Products & Pricelists — `product`

**Source:** [`agents/modules/generated/product.yaml`](../../agents/modules/generated/product.yaml) · **Wiki:** [`knowledge/modules/product/overview.md`](../../knowledge/modules/product/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>product</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Products & Pricelists</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/product</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/product"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md), [`mail`](mail.md), [`uom`](uom.md)

## Reverse dependencies (modules that depend on this)

[`account`](account.md), [`loyalty`](loyalty.md), [`mrp`](mrp.md), [`product_images`](product_images.md), [`stock`](stock.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.attribute</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.attribute.custom.value</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.attribute.value</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.catalog.mixin</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.category</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.document</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.label.layout</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.packaging</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.pricelist</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.pricelist.item</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.supplierinfo</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.tag</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.template.attribute.exclusion</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.template.attribute.line</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.template.attribute.value</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>report.product.report_pricelist</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>report.product.report_producttemplatelabel2x7</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>report.product.report_producttemplatelabel4x12</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>report.product.report_producttemplatelabel4x12noprice</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>report.product.report_producttemplatelabel4x7</code></div><div class="role">defined by <code>product</code></div></div>
<div class="model"><div class="name"><code>report.product.report_producttemplatelabel_dymo</code></div><div class="role">defined by <code>product</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>decimal.precision</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>image.mixin</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.attribute</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.attribute.value</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.category</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.pricelist</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.pricelist.item</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.supplierinfo</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.template.attribute.exclusion</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>product.template.attribute.value</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>res.country.group</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>res.currency</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>product</code></div></div>
<div class="model"><div class="name"><code>uom.uom</code></div><div class="role">extended by <code>product</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from, model_extended_by, required_by | `agents/modules/generated/account.yaml` |
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.delivery` | model_extended_by | `agents/modules/generated/delivery.yaml` |
| `module.event_booth_sale` | model_extended_by | `agents/modules/generated/event_booth_sale.yaml` |
| `module.event_sale` | model_extended_by | `agents/modules/generated/event_sale.yaml` |
| `module.hr_expense` | model_extended_by | `agents/modules/generated/hr_expense.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_de` | model_extended_by | `agents/modules/generated/l10n_de.yaml` |
| `module.l10n_eg_edi_eta` | model_extended_by | `agents/modules/generated/l10n_eg_edi_eta.yaml` |

## Conversation learnings

- [`2026-08-13-webclient-stale-view-after-quarantine`](../../knowledge/conversations/2026-08-13-webclient-stale-view-after-quarantine.json)

## Full wiki excerpt

- SME owner: [`module.product`](../../../agents/modules/generated/product.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/product)
- Direct dependencies: [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`uom`](../uom/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`account`](../account/overview.md), [`loyalty`](../loyalty/overview.md), [`mrp`](../mrp/overview.md), [`product_images`](../product_images/overview.md), [`stock`](../stock/overview.md)
- Impact graph: [`module:product`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `product.attribute` — extended by [`sale`](../sale/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_comparison`](../website_sale_comparison/overview.md)
- `product.attribute.custom.value` — extended by [`point_of_sale`](../point_of_sale/overview.md), [`sale`](../sale/overview.md)
- `product.attribute.value` — extended by [`sale`](../sale/overview.md)
- `product.catalog.mixin` — extended by [`purchase`](../purchase/overview.md), [`sale`](../sale/overview.md)
- `product.category` — extended by [`account`](../account/overview.md), [`delivery`](../delivery/overview.md), [`mrp_account`](../mrp_account/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md)
- `product.document` — extended by [`sale`](../sale/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`website_sale`](../website_sale/overview.md)
- `product.label.layout` — extended by [`stock`](../stock/overview.md)
- `product.packaging` — extended by [`purchase`](../purchase/overview.md), [`sale`](../sale/overview.md), [`stock`](../stock/overview.md)
- `product.pricelist` — extended by [`loyalty`](../loyalty/overview.md), [`website_sale`](../website_sale/overview.md)
- `product.pricelist.item` — extended by [`website_event_sale`](../website_event_sale/overview.md)
- `product.product` — extended by [`account`](../account/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`loyalty`](../loyalty/overview.md), [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_sale_product_configurator`](../pos_sale_product_configurator/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`pos_self_order_sale`](../pos_self_order_sale/overview.md), [`product_expiry`](../product_expiry/overview.md), [`product_images`](../product_images/overview.md), [`product_margin`](../product_margin/overview.md), [`purchase`](../purchase/overview.md), [`purchase_requisition`](../purchase_requisition/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale`](../sale/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_comparison`](../website_sale_comparison/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md)
- `product.supplierinfo` — extended by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`purchase`](../purchase/overview.md), [`purchase_requisition`](../purchase_requisition/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- `product.tag` — extended by [`website_sale`](../website_sale/overview.md)
- `product.template` — extended by [`account`](../account/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_cpv_code`](../l10n_ro_cpv_code/overview.md), [`loyalty`](../loyalty/overview.md), [`membership`](../membership/overview.md), [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`product_email_template`](../product_email_template/overview.md), [`product_expiry`](../product_expiry/overview.md), [`product_matrix`](../product_matrix/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_stock_wishlist`](../website_sale_stock_wishlist/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md)
- `product.template.attribute.exclusion`
- `product.template.attribute.line` — extended by [`website_sale`](../website_sale/overview.md), [`website_sale_comparison`](../website_sale_comparison/overview.md)
- `product.template.attribute.value` — extended by [`product_matrix`](../product_matrix/overview.md), [`website_sale`](../website_sale/overview.md)
- `report.product.report_pricelist`
- `report.product.report_producttemplatelabel2x7`
- `report.product.report_producttemplatelabel4x12`
- `report.product.report_producttemplatelabel4x12noprice`
- `report.product.report_producttemplatelabel4x7`
- `report.product.report_producttemplatelabel_dymo`
- Extends `decimal.precision` — defined by [`base`](../base/overview.md)
- Extends `image.mixin` — defined by [`base`](../base/overview.md)
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `product.attribute` — framework/dynamic owner
- Extends `product.attribute.value` — framework/dynamic owner
- Extends `product.category` — framework/dynamic owner
- Extends `product.pricelist` — framework/dynamic owner
- Extends `product.pricelist.item` — framework/dynamic owner
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.supplierinfo` — framework/dynamic owner
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `product.template.attribute.exclusion` — framework/dynamic owner
- Extends `product.template.attribute.value` — framework/dynamic owner
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.country.group` — defined by [`base`](../base/overview.md)
- Extends `res.currency` — defined by [`base`](../base/overview.md), [`l10n_cl`](../l10n_cl/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `uom.uom` — defined by [`uom`](../uom/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from, model_extended_by, required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — model_extended_by
- [`module.event_booth_sale`](../../../agents/modules/generated/event_booth_sale.yaml) — model_extended_by
- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — model_extended_by
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml) — model_extended_by
- [`module.l10n_eg_edi_eta`](../../../agents/modules/generated/l10n_eg_edi_eta.yaml) — model_extended_by
- [`module.l10n_gcc_invoice`](../../../agents/modules/generated/l10n_gcc_invoice.yaml) — model_extended_by
- [`module.l10n_hu_edi`](../../../agents/modules/generated/l10n_hu_edi.yaml) — model_extended_by
- [`module.l10n_id_efaktur_coretax`](../../../agents/modules/generated/l10n_id_efaktur_coretax.yaml) — model_extended_by
- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_my_edi`](../../../agents/modules/generated/l10n_my_edi.yaml) — model_extended_by
- [`module.l10n_pl`](../../../agents/modules/generated/l10n_pl.yaml) — model_extended_by
- [`module.l10n_ro_cpv_code`](../../../agents/modules/generated/l10n_ro_cpv_code.yaml) — model_extended_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — model_extended_by, required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.membership`](../../../agents/modules/generated/membership.yaml) — model_extended_by
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — model_extended_by, required_by
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from, model_extended_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — model_extended_by
- [`module.mrp_subcontracting_account`](../../../agents/modules/generated/mrp_subcontracting_account.yaml) — model_extended_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.pos_sale_product_configurator`](../../../agents/modules/generated/pos_sale_product_configurator.yaml) — model_extended_by
- [`module.pos_self_order`](../../../agents/modules/generated/pos_self_order.yaml) — model_extended_by
- [`module.pos_self_order_sale`](../../../agents/modules/generated/pos_self_order_sale.yaml) — model_extended_by
- [`module.product_email_template`](../../../agents/modules/generated/product_email_template.yaml) — model_extended_by
- [`module.product_expiry`](../../../agents/modules/generated/product_expiry.yaml) — model_extended_by
- [`module.product_images`](../../../agents/modules/generated/product_images.yaml) — model_extended_by, required_by
- [`module.product_margin`](../../../agents/modules/generated/product_margin.yaml) — model_extended_by
- [`module.product_matrix`](../../../agents/modules/generated/product_matrix.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from, model_extended_by
- [`module.purchase_requisition`](../../../agents/modules/generated/purchase_requisition.yaml) — model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from, model_extended_by
- [`module.repair`](../../../agents/modules/generated/repair.yaml) — model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — model_extended_by
- [`module.sale_expense`](../../../agents/modules/generated/sale_expense.yaml) — model_extended_by
- [`module.sale_pdf_quote_builder`](../../../agents/modules/generated/sale_pdf_quote_builder.yaml) — model_extended_by
- [`module.sale_product_configurator`](../../../agents/modules/generated/sale_product_configurator.yaml) — model_extended_by
- [`module.sale_product_matrix`](../../../agents/modules/generated/sale_product_matrix.yaml) — model_extended_by
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — model_extended_by
- [`module.sale_purchase`](../../../agents/modules/generated/sale_purchase.yaml) — model_extended_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — model_extended_by, required_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from, model_extended_by
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — model_extended_by
- [`module.stock_landed_costs`](../../../agents/modules/generated/stock_landed_costs.yaml) — model_extended_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.uom`](../../../agents/modules/generated/uom.yaml) — depends_on, extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_event_booth_sale`](../../../agents/modules/generated/website_event_booth_sale.yaml) — model_extended_by
- [`module.website_event_sale`](../../../agents/modules/generated/website_event_sale.yaml) — model_extended_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from, model_extended_by
- [`module.website_sale_comparison`](../../../agents/modules/generated/website_sale_comparison.yaml) — model_extended_by
- [`module.website_sale_slides`](../../../agents/modules/generated/website_sale_slides.yaml) — model_extended_by
- [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml) — model_extended_by
- [`module.website_sale_stock_wishlist`](../../../agents/modules/generated/website_sale_stock_wishlist.yaml) — model_extended_by
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — model_extended_by

## Regression impact checklist

- Review 5 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`delivery`](../delivery/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_cpv_code`](../l10n_ro_cpv_code/overview.md), [`loyalty`](../loyalty/overview.md), [`membership`](../membership/overview.md), [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_sale_product_configurator`](../pos_sale_product_configurator/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`pos_self_order_sale`](../pos_self_order_sale/overview.md), [`product_email_template`](../product_email_template/overview.md), [`product_expiry`](../product_expiry/overview.md), [`product_images`](../product_images/overview.md), [`product_margin`](../product_margin/overview.md), [`product_matrix`](../product_matrix/overview.md), [`purchase`](../purchase/overview.md), [`purchase_requisition`](../purchase_requisition/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_comparison`](../website_sale_comparison/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_stock_wishlist`](../website_sale_stock_wishlist/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mrp_account`](../mrp_account/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sms`](../sms/overview.md), [`stock_account`](../stock_account/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`uom`](../uom/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-13-webclient-stale-view-after-quarantine`](../../conversations/2026-08-13-webclient-stale-view-after-quarantine.json)
