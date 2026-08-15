---
layout: page
title: "eCommerce (website_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_sale/
nav_order: 0
---
# eCommerce — `website_sale`

**Source:** [`agents/modules/generated/website_sale.yaml`](../../agents/modules/generated/website_sale.yaml) · **Wiki:** [`knowledge/modules/website_sale/overview.md`](../../knowledge/modules/website_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">eCommerce</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Sell your products online

## Direct dependencies

[`delivery`](delivery.md), [`digest`](digest.md), [`portal_rating`](portal_rating.md), [`sale`](sale.md), [`website`](website.md), [`website_mail`](website_mail.md), [`website_payment`](website_payment.md)

## Reverse dependencies (modules that depend on this)

[`l10n_ar_website_sale`](l10n_ar_website_sale.md), [`l10n_br_website_sale`](l10n_br_website_sale.md), [`l10n_ec_website_sale`](l10n_ec_website_sale.md), [`l10n_it_edi_website_sale`](l10n_it_edi_website_sale.md), [`l10n_pe_website_sale`](l10n_pe_website_sale.md), [`l10n_uy_website_sale`](l10n_uy_website_sale.md), [`spreadsheet_dashboard_website_sale`](spreadsheet_dashboard_website_sale.md), [`website_event_booth_sale`](website_event_booth_sale.md), [`website_event_sale`](website_event_sale.md), [`website_membership`](website_membership.md), [`website_sale_autocomplete`](website_sale_autocomplete.md), [`website_sale_comparison`](website_sale_comparison.md), [`website_sale_loyalty`](website_sale_loyalty.md), [`website_sale_mondialrelay`](website_sale_mondialrelay.md), [`website_sale_picking`](website_sale_picking.md), [`website_sale_product_configurator`](website_sale_product_configurator.md), [`website_sale_slides`](website_sale_slides.md), [`website_sale_stock`](website_sale_stock.md), [`website_sale_wishlist`](website_sale_wishlist.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>delivery.carrier</code></div><div class="role">defined by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.image</code></div><div class="role">defined by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.public.category</code></div><div class="role">defined by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.ribbon</code></div><div class="role">defined by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.tag</code></div><div class="role">defined by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">defined by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>website.base.unit</code></div><div class="role">defined by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>website.sale.extra.field</code></div><div class="role">defined by <code>website_sale</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>crm.team</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>delivery.carrier</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>digest.digest</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>image.mixin</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>payment.token</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.attribute</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.document</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.pricelist</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.public.category</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.tag</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.template.attribute.line</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>product.template.attribute.value</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>rating.mixin</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>res.country</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>sale.report</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>website.multi.mixin</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>website.published.multi.mixin</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>website.searchable.mixin</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>website.seo.metadata</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>website.snippet.filter</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>website.track</code></div><div class="role">extended by <code>website_sale</code></div></div>
<div class="model"><div class="name"><code>website.visitor</code></div><div class="role">extended by <code>website_sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from, model_extended_by | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.delivery` | depends_on, extends_model_from | `agents/modules/generated/delivery.yaml` |
| `module.delivery_mondialrelay` | model_extended_by | `agents/modules/generated/delivery_mondialrelay.yaml` |
| `module.digest` | depends_on, extends_model_from | `agents/modules/generated/digest.yaml` |
| `module.event_booth_sale` | model_extended_by | `agents/modules/generated/event_booth_sale.yaml` |
| `module.event_sale` | model_extended_by | `agents/modules/generated/event_sale.yaml` |
| `module.hr_expense` | model_extended_by | `agents/modules/generated/hr_expense.yaml` |
| `module.l10n_ar_website_sale` | required_by | `agents/modules/generated/l10n_ar_website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale)
- Direct dependencies: [`delivery`](../delivery/overview.md), [`digest`](../digest/overview.md), [`portal_rating`](../portal_rating/overview.md), [`sale`](../sale/overview.md), [`website`](../website/overview.md), [`website_mail`](../website_mail/overview.md), [`website_payment`](../website_payment/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_ar_website_sale`](../l10n_ar_website_sale/overview.md), [`l10n_br_website_sale`](../l10n_br_website_sale/overview.md), [`l10n_ec_website_sale`](../l10n_ec_website_sale/overview.md), [`l10n_it_edi_website_sale`](../l10n_it_edi_website_sale/overview.md), [`l10n_pe_website_sale`](../l10n_pe_website_sale/overview.md), [`l10n_uy_website_sale`](../l10n_uy_website_sale/overview.md), [`spreadsheet_dashboard_website_sale`](../spreadsheet_dashboard_website_sale/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_membership`](../website_membership/overview.md), [`website_sale_autocomplete`](../website_sale_autocomplete/overview.md), [`website_sale_comparison`](../website_sale_comparison/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md), [`website_sale_product_configurator`](../website_sale_product_configurator/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md)
- Impact graph: [`module:website_sale`](../../impact-graph.json)

## Purpose

Sell your products online

## Model relationships

- `delivery.carrier` — extended by [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`l10n_ro_edi_stock`](../l10n_ro_edi_stock/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md)
- `product.image`
- `product.public.category`
- `product.ribbon`
- `product.tag`
- `product.template` — extended by [`account`](../account/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_cpv_code`](../l10n_ro_cpv_code/overview.md), [`loyalty`](../loyalty/overview.md), [`membership`](../membership/overview.md), [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`product`](../product/overview.md), [`product_email_template`](../product_email_template/overview.md), [`product_expiry`](../product_expiry/overview.md), [`product_matrix`](../product_matrix/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_stock_wishlist`](../website_sale_stock_wishlist/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md)
- `website.base.unit`
- `website.sale.extra.field`
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `crm.team` — defined by [`crm`](../crm/overview.md), [`sales_team`](../sales_team/overview.md)
- Extends `delivery.carrier` — defined by [`delivery`](../delivery/overview.md)
- Extends `digest.digest` — defined by [`digest`](../digest/overview.md)
- Extends `image.mixin` — defined by [`base`](../base/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `payment.token` — defined by [`payment`](../payment/overview.md)
- Extends `product.attribute` — defined by [`product`](../product/overview.md)
- Extends `product.document` — defined by [`product`](../product/overview.md)
- Extends `product.pricelist` — defined by [`product`](../product/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.public.category` — framework/dynamic owner
- Extends `product.tag` — defined by [`product`](../product/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md)
- Extends `product.template.attribute.line` — defined by [`product`](../product/overview.md)
- Extends `product.template.attribute.value` — defined by [`product`](../product/overview.md)
- Extends `rating.mixin` — defined by [`rating`](../rating/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.country` — defined by [`base`](../base/overview.md), [`l10n_cl`](../l10n_cl/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)
- Extends `sale.report` — defined by [`sale`](../sale/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)
- Extends `website.multi.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.published.multi.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.searchable.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.seo.metadata` — defined by [`website`](../website/overview.md)
- Extends `website.snippet.filter` — defined by [`website`](../website/overview.md)
- Extends `website.track` — defined by [`website`](../website/overview.md)
- Extends `website.visitor` — defined by [`website`](../website/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from, model_extended_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — depends_on, extends_model_from
- [`module.delivery_mondialrelay`](../../../agents/modules/generated/delivery_mondialrelay.yaml) — model_extended_by
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — depends_on, extends_model_from
- [`module.event_booth_sale`](../../../agents/modules/generated/event_booth_sale.yaml) — model_extended_by
- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — model_extended_by
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — model_extended_by
- [`module.l10n_ar_website_sale`](../../../agents/modules/generated/l10n_ar_website_sale.yaml) — required_by
- [`module.l10n_br_website_sale`](../../../agents/modules/generated/l10n_br_website_sale.yaml) — required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml) — model_extended_by
- [`module.l10n_ec_website_sale`](../../../agents/modules/generated/l10n_ec_website_sale.yaml) — required_by
- [`module.l10n_eg_edi_eta`](../../../agents/modules/generated/l10n_eg_edi_eta.yaml) — model_extended_by
- [`module.l10n_hu_edi`](../../../agents/modules/generated/l10n_hu_edi.yaml) — model_extended_by
- [`module.l10n_id_efaktur_coretax`](../../../agents/modules/generated/l10n_id_efaktur_coretax.yaml) — model_extended_by
- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_it_edi_website_sale`](../../../agents/modules/generated/l10n_it_edi_website_sale.yaml) — required_by
- [`module.l10n_my_edi`](../../../agents/modules/generated/l10n_my_edi.yaml) — model_extended_by
- [`module.l10n_pe_website_sale`](../../../agents/modules/generated/l10n_pe_website_sale.yaml) — required_by
- [`module.l10n_pl`](../../../agents/modules/generated/l10n_pl.yaml) — model_extended_by
- [`module.l10n_ro_cpv_code`](../../../agents/modules/generated/l10n_ro_cpv_code.yaml) — model_extended_by
- [`module.l10n_ro_edi_stock`](../../../agents/modules/generated/l10n_ro_edi_stock.yaml) — model_extended_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.l10n_uy_website_sale`](../../../agents/modules/generated/l10n_uy_website_sale.yaml) — required_by
- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — model_extended_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.membership`](../../../agents/modules/generated/membership.yaml) — model_extended_by
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — model_extended_by
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from, model_extended_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.portal_rating`](../../../agents/modules/generated/portal_rating.yaml) — depends_on
- [`module.pos_self_order`](../../../agents/modules/generated/pos_self_order.yaml) — model_extended_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from, model_extended_by
- [`module.product_email_template`](../../../agents/modules/generated/product_email_template.yaml) — model_extended_by
- [`module.product_expiry`](../../../agents/modules/generated/product_expiry.yaml) — model_extended_by
- [`module.product_matrix`](../../../agents/modules/generated/product_matrix.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from, model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from, model_extended_by
- [`module.rating`](../../../agents/modules/generated/rating.yaml) — extends_model_from
- [`module.repair`](../../../agents/modules/generated/repair.yaml) — model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.sale_expense`](../../../agents/modules/generated/sale_expense.yaml) — model_extended_by
- [`module.sale_product_configurator`](../../../agents/modules/generated/sale_product_configurator.yaml) — model_extended_by
- [`module.sale_product_matrix`](../../../agents/modules/generated/sale_product_matrix.yaml) — model_extended_by
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — model_extended_by
- [`module.sale_purchase`](../../../agents/modules/generated/sale_purchase.yaml) — model_extended_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — model_extended_by
- [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.spreadsheet_dashboard_website_sale`](../../../agents/modules/generated/spreadsheet_dashboard_website_sale.yaml) — required_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — model_extended_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from, model_extended_by
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — model_extended_by
- [`module.stock_landed_costs`](../../../agents/modules/generated/stock_landed_costs.yaml) — model_extended_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on, extends_model_from
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — extends_model_from
- [`module.website_event_booth_sale`](../../../agents/modules/generated/website_event_booth_sale.yaml) — model_extended_by, required_by
- [`module.website_event_sale`](../../../agents/modules/generated/website_event_sale.yaml) — model_extended_by, required_by
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — extends_model_from
- [`module.website_mail`](../../../agents/modules/generated/website_mail.yaml) — depends_on
- [`module.website_membership`](../../../agents/modules/generated/website_membership.yaml) — required_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_payment`](../../../agents/modules/generated/website_payment.yaml) — depends_on
- [`module.website_sale_autocomplete`](../../../agents/modules/generated/website_sale_autocomplete.yaml) — required_by
- [`module.website_sale_comparison`](../../../agents/modules/generated/website_sale_comparison.yaml) — required_by
- [`module.website_sale_loyalty`](../../../agents/modules/generated/website_sale_loyalty.yaml) — required_by
- [`module.website_sale_mondialrelay`](../../../agents/modules/generated/website_sale_mondialrelay.yaml) — required_by
- [`module.website_sale_picking`](../../../agents/modules/generated/website_sale_picking.yaml) — model_extended_by, required_by
- [`module.website_sale_product_configurator`](../../../agents/modules/generated/website_sale_product_configurator.yaml) — required_by
- [`module.website_sale_slides`](../../../agents/modules/generated/website_sale_slides.yaml) — model_extended_by, required_by
- [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml) — model_extended_by, required_by
- [`module.website_sale_stock_wishlist`](../../../agents/modules/generated/website_sale_stock_wishlist.yaml) — model_extended_by
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — model_extended_by, required_by

## Regression impact checklist

- Review 19 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_cpv_code`](../l10n_ro_cpv_code/overview.md), [`l10n_ro_edi_stock`](../l10n_ro_edi_stock/overview.md), [`loyalty`](../loyalty/overview.md), [`membership`](../membership/overview.md), [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`product`](../product/overview.md), [`product_email_template`](../product_email_template/overview.md), [`product_expiry`](../product_expiry/overview.md), [`product_matrix`](../product_matrix/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_stock_wishlist`](../website_sale_stock_wishlist/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`delivery`](../delivery/overview.md), [`digest`](../digest/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`mrp_account`](../mrp_account/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`rating`](../rating/overview.md), [`sale`](../sale/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`stock_account`](../stock_account/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
