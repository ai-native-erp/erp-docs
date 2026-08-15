---
layout: page
title: "Point of Sale (point_of_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/point_of_sale/
nav_order: 0
---
# Point of Sale — `point_of_sale`

**Source:** [`agents/modules/generated/point_of_sale.yaml`](../../agents/modules/generated/point_of_sale.yaml) · **Wiki:** [`knowledge/modules/point_of_sale/overview.md`](../../knowledge/modules/point_of_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>point_of_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Point of Sale</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/point_of_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/point_of_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

User-friendly PoS interface for shops and restaurants

## Direct dependencies

[`barcodes`](barcodes.md), [`digest`](digest.md), [`stock_account`](stock_account.md), [`web_editor`](web_editor.md)

## Reverse dependencies (modules that depend on this)

[`l10n_ar_pos`](l10n_ar_pos.md), [`l10n_ch_pos`](l10n_ch_pos.md), [`l10n_co_pos`](l10n_co_pos.md), [`l10n_es_edi_verifactu_pos`](l10n_es_edi_verifactu_pos.md), [`l10n_es_pos`](l10n_es_pos.md), [`l10n_fr_pdp_pos`](l10n_fr_pdp_pos.md), [`l10n_fr_pos_cert`](l10n_fr_pos_cert.md), [`l10n_gcc_pos`](l10n_gcc_pos.md), [`l10n_in_pos`](l10n_in_pos.md), [`l10n_mt_pos`](l10n_mt_pos.md), [`l10n_pe_pos`](l10n_pe_pos.md), [`pos_adyen`](pos_adyen.md), [`pos_discount`](pos_discount.md), [`pos_epson_printer`](pos_epson_printer.md), [`pos_hr`](pos_hr.md), [`pos_loyalty`](pos_loyalty.md), [`pos_mercado_pago`](pos_mercado_pago.md), [`pos_mercury`](pos_mercury.md), [`pos_mrp`](pos_mrp.md), [`pos_online_payment`](pos_online_payment.md), [`pos_paytm`](pos_paytm.md), [`pos_razorpay`](pos_razorpay.md), [`pos_restaurant`](pos_restaurant.md), [`pos_sale`](pos_sale.md), [`pos_sale_product_configurator`](pos_sale_product_configurator.md), [`pos_six`](pos_six.md), [`pos_stripe`](pos_stripe.md), [`pos_viva_wallet`](pos_viva_wallet.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.bill</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.category</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.close.session.wizard</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.combo</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.combo.line</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.config</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.daily.sales.reports.wizard</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.details.wizard</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.make.payment</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.order.line</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.pack.operation.lot</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.payment</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.payment.method</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.printer</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>report.point_of_sale.report_invoice</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>report.point_of_sale.report_saledetails</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>report.pos.order</code></div><div class="role">defined by <code>point_of_sale</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.bank.statement.line</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>account.cash.rounding</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>account.fiscal.position</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>account.payment</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>account.tax</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>barcode.rule</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>digest.digest</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>portal.mixin</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>procurement.group</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>product.attribute.custom.value</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>stock.picking.type</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>stock.rule</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>stock.warehouse</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>uom.category</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
<div class="model"><div class="name"><code>uom.uom</code></div><div class="role">extended by <code>point_of_sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.barcodes` | depends_on, extends_model_from | `agents/modules/generated/barcodes.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.digest` | depends_on, extends_model_from | `agents/modules/generated/digest.yaml` |
| `module.l10n_ar_pos` | model_extended_by, required_by | `agents/modules/generated/l10n_ar_pos.yaml` |
| `module.l10n_be_pos_sale` | model_extended_by | `agents/modules/generated/l10n_be_pos_sale.yaml` |
| `module.l10n_ch_pos` | model_extended_by, required_by | `agents/modules/generated/l10n_ch_pos.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_co_pos` | model_extended_by, required_by | `agents/modules/generated/l10n_co_pos.yaml` |

## Conversation learnings

- [`2026-08-12-cmr-backup-restore-capacity`](../../knowledge/conversations/2026-08-12-cmr-backup-restore-capacity.json)
- [`2026-08-12-cmr-endpoint-bootstrap-enterprise-gate`](../../knowledge/conversations/2026-08-12-cmr-endpoint-bootstrap-enterprise-gate.json)
- [`2026-08-12-cmr-ho-store-isolation`](../../knowledge/conversations/2026-08-12-cmr-ho-store-isolation.json)

## Full wiki excerpt

- SME owner: [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml)
- Domain: `point_of_sale`
- Category: Sales/Point of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/point_of_sale)
- Direct dependencies: [`barcodes`](../barcodes/overview.md), [`digest`](../digest/overview.md), [`stock_account`](../stock_account/overview.md), [`web_editor`](../web_editor/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`l10n_co_pos`](../l10n_co_pos/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_fr_pdp_pos`](../l10n_fr_pdp_pos/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_gcc_pos`](../l10n_gcc_pos/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_mt_pos`](../l10n_mt_pos/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`pos_adyen`](../pos_adyen/overview.md), [`pos_discount`](../pos_discount/overview.md), [`pos_epson_printer`](../pos_epson_printer/overview.md), [`pos_hr`](../pos_hr/overview.md), [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_mercado_pago`](../pos_mercado_pago/overview.md), [`pos_mercury`](../pos_mercury/overview.md), [`pos_mrp`](../pos_mrp/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`pos_paytm`](../pos_paytm/overview.md), [`pos_razorpay`](../pos_razorpay/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md), [`pos_sale`](../pos_sale/overview.md), [`pos_sale_product_configurator`](../pos_sale_product_configurator/overview.md), [`pos_six`](../pos_six/overview.md), [`pos_stripe`](../pos_stripe/overview.md), [`pos_viva_wallet`](../pos_viva_wallet/overview.md)
- Impact graph: [`module:point_of_sale`](../../impact-graph.json)

## Purpose

User-friendly PoS interface for shops and restaurants

## Model relationships

- `pos.bill`
- `pos.category`
- `pos.close.session.wizard`
- `pos.combo`
- `pos.combo.line`
- `pos.config` — extended by [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_sa_edi_pos`](../l10n_sa_edi_pos/overview.md), [`l10n_sa_pos`](../l10n_sa_pos/overview.md), [`pos_adyen`](../pos_adyen/overview.md), [`pos_discount`](../pos_discount/overview.md), [`pos_epson_printer`](../pos_epson_printer/overview.md), [`pos_hr`](../pos_hr/overview.md), [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`pos_online_payment_self_order`](../pos_online_payment_self_order/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md), [`pos_sale`](../pos_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`pos_self_order_epson_printer`](../pos_self_order_epson_printer/overview.md), [`pos_six`](../pos_six/overview.md)
- `pos.daily.sales.reports.wizard`
- `pos.details.wizard`
- `pos.make.payment`
- `pos.order` — extended by [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`l10n_co_pos`](../l10n_co_pos/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_sa_pos`](../l10n_sa_pos/overview.md), [`pos_hr`](../pos_hr/overview.md), [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_mercury`](../pos_mercury/overview.md), [`pos_mrp`](../pos_mrp/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`pos_online_payment_self_order`](../pos_online_payment_self_order/overview.md), [`pos_paytm`](../pos_paytm/overview.md), [`pos_razorpay`](../pos_razorpay/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md), [`pos_restaurant_adyen`](../pos_restaurant_adyen/overview.md), [`pos_restaurant_stripe`](../pos_restaurant_stripe/overview.md), [`pos_sale`](../pos_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md)
- `pos.order.line` — extended by [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_mrp`](../pos_mrp/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md), [`pos_sale`](../pos_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md)
- `pos.pack.operation.lot`
- `pos.payment` — extended by [`pos_mercury`](../pos_mercury/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`pos_paytm`](../pos_paytm/overview.md), [`pos_razorpay`](../pos_razorpay/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md), [`pos_restaurant_adyen`](../pos_restaurant_adyen/overview.md), [`pos_restaurant_stripe`](../pos_restaurant_stripe/overview.md)
- `pos.payment.method` — extended by [`pos_adyen`](../pos_adyen/overview.md), [`pos_mercado_pago`](../pos_mercado_pago/overview.md), [`pos_mercury`](../pos_mercury/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`pos_paytm`](../pos_paytm/overview.md), [`pos_razorpay`](../pos_razorpay/overview.md), [`pos_restaurant_adyen`](../pos_restaurant_adyen/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`pos_self_order_adyen`](../pos_self_order_adyen/overview.md), [`pos_self_order_stripe`](../pos_self_order_stripe/overview.md), [`pos_six`](../pos_six/overview.md), [`pos_stripe`](../pos_stripe/overview.md), [`pos_viva_wallet`](../pos_viva_wallet/overview.md)
- `pos.printer` — extended by [`pos_epson_printer`](../pos_epson_printer/overview.md)
- `pos.session` — extended by [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_be_pos_sale`](../l10n_be_pos_sale/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`pos_adyen`](../pos_adyen/overview.md), [`pos_discount`](../pos_discount/overview.md), [`pos_epson_printer`](../pos_epson_printer/overview.md), [`pos_hr`](../pos_hr/overview.md), [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_mercado_pago`](../pos_mercado_pago/overview.md), [`pos_mercury`](../pos_mercury/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md), [`pos_restaurant_adyen`](../pos_restaurant_adyen/overview.md), [`pos_sale`](../pos_sale/overview.md), [`pos_sale_product_configurator`](../pos_sale_product_configurator/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`pos_six`](../pos_six/overview.md), [`pos_stripe`](../pos_stripe/overview.md), [`pos_viva_wallet`](../pos_viva_wallet/overview.md)
- `report.point_of_sale.report_invoice`
- `report.point_of_sale.report_saledetails`
- `report.pos.order` — extended by [`pos_hr`](../pos_hr/overview.md)
- Extends `account.bank.statement.line` — defined by [`account`](../account/overview.md)
- Extends `account.cash.rounding` — defined by [`account`](../account/overview.md)
- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.fiscal.position` — defined by [`account`](../account/overview.md)
- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `account.payment` — defined by [`account`](../account/overview.md)
- Extends `account.tax` — defined by [`account`](../account/overview.md)
- Extends `barcode.rule` — defined by [`barcodes`](../barcodes/overview.md)
- Extends `digest.digest` — defined by [`digest`](../digest/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `portal.mixin` — defined by [`portal`](../portal/overview.md)
- Extends `procurement.group` — defined by [`stock`](../stock/overview.md)
- Extends `product.attribute.custom.value` — defined by [`product`](../product/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)
- Extends `stock.picking.type` — defined by [`stock`](../stock/overview.md)
- Extends `stock.rule` — defined by [`stock`](../stock/overview.md)
- Extends `stock.warehouse` — defined by [`stock`](../stock/overview.md)
- Extends `uom.category` — defined by [`uom`](../uom/overview.md)
- Extends `uom.uom` — defined by [`uom`](../uom/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.barcodes`](../../../agents/modules/generated/barcodes.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — depends_on, extends_model_from
- [`module.l10n_ar_pos`](../../../agents/modules/generated/l10n_ar_pos.yaml) — model_extended_by, required_by
- [`module.l10n_be_pos_sale`](../../../agents/modules/generated/l10n_be_pos_sale.yaml) — model_extended_by
- [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml) — model_extended_by, required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_co_pos`](../../../agents/modules/generated/l10n_co_pos.yaml) — model_extended_by, required_by
- [`module.l10n_es_edi_verifactu_pos`](../../../agents/modules/generated/l10n_es_edi_verifactu_pos.yaml) — model_extended_by, required_by
- [`module.l10n_es_pos`](../../../agents/modules/generated/l10n_es_pos.yaml) — model_extended_by, required_by
- [`module.l10n_es_pos_tbai`](../../../agents/modules/generated/l10n_es_pos_tbai.yaml) — model_extended_by
- [`module.l10n_fr_pdp_pos`](../../../agents/modules/generated/l10n_fr_pdp_pos.yaml) — required_by
- [`module.l10n_fr_pos_cert`](../../../agents/modules/generated/l10n_fr_pos_cert.yaml) — model_extended_by, required_by
- [`module.l10n_gcc_pos`](../../../agents/modules/generated/l10n_gcc_pos.yaml) — required_by
- [`module.l10n_in_pos`](../../../agents/modules/generated/l10n_in_pos.yaml) — model_extended_by, required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_mt_pos`](../../../agents/modules/generated/l10n_mt_pos.yaml) — required_by
- [`module.l10n_pe_pos`](../../../agents/modules/generated/l10n_pe_pos.yaml) — model_extended_by, required_by
- [`module.l10n_sa_edi_pos`](../../../agents/modules/generated/l10n_sa_edi_pos.yaml) — model_extended_by
- [`module.l10n_sa_pos`](../../../agents/modules/generated/l10n_sa_pos.yaml) — model_extended_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — extends_model_from
- [`module.pos_adyen`](../../../agents/modules/generated/pos_adyen.yaml) — model_extended_by, required_by
- [`module.pos_discount`](../../../agents/modules/generated/pos_discount.yaml) — model_extended_by, required_by
- [`module.pos_epson_printer`](../../../agents/modules/generated/pos_epson_printer.yaml) — model_extended_by, required_by
- [`module.pos_hr`](../../../agents/modules/generated/pos_hr.yaml) — model_extended_by, required_by
- [`module.pos_loyalty`](../../../agents/modules/generated/pos_loyalty.yaml) — model_extended_by, required_by
- [`module.pos_mercado_pago`](../../../agents/modules/generated/pos_mercado_pago.yaml) — model_extended_by, required_by
- [`module.pos_mercury`](../../../agents/modules/generated/pos_mercury.yaml) — model_extended_by, required_by
- [`module.pos_mrp`](../../../agents/modules/generated/pos_mrp.yaml) — model_extended_by, required_by
- [`module.pos_online_payment`](../../../agents/modules/generated/pos_online_payment.yaml) — model_extended_by, required_by
- [`module.pos_online_payment_self_order`](../../../agents/modules/generated/pos_online_payment_self_order.yaml) — model_extended_by
- [`module.pos_paytm`](../../../agents/modules/generated/pos_paytm.yaml) — model_extended_by, required_by
- [`module.pos_razorpay`](../../../agents/modules/generated/pos_razorpay.yaml) — model_extended_by, required_by
- [`module.pos_restaurant`](../../../agents/modules/generated/pos_restaurant.yaml) — model_extended_by, required_by
- [`module.pos_restaurant_adyen`](../../../agents/modules/generated/pos_restaurant_adyen.yaml) — model_extended_by
- [`module.pos_restaurant_stripe`](../../../agents/modules/generated/pos_restaurant_stripe.yaml) — model_extended_by
- [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml) — model_extended_by, required_by
- [`module.pos_sale_product_configurator`](../../../agents/modules/generated/pos_sale_product_configurator.yaml) — model_extended_by, required_by
- [`module.pos_self_order`](../../../agents/modules/generated/pos_self_order.yaml) — model_extended_by
- [`module.pos_self_order_adyen`](../../../agents/modules/generated/pos_self_order_adyen.yaml) — model_extended_by
- [`module.pos_self_order_epson_printer`](../../../agents/modules/generated/pos_self_order_epson_printer.yaml) — model_extended_by
- [`module.pos_self_order_stripe`](../../../agents/modules/generated/pos_self_order_stripe.yaml) — model_extended_by
- [`module.pos_six`](../../../agents/modules/generated/pos_six.yaml) — model_extended_by, required_by
- [`module.pos_stripe`](../../../agents/modules/generated/pos_stripe.yaml) — model_extended_by, required_by
- [`module.pos_viva_wallet`](../../../agents/modules/generated/pos_viva_wallet.yaml) — model_extended_by, required_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — depends_on, extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.uom`](../../../agents/modules/generated/uom.yaml) — extends_model_from
- [`module.web_editor`](../../../agents/modules/generated/web_editor.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 28 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_be_pos_sale`](../l10n_be_pos_sale/overview.md), [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`l10n_co_pos`](../l10n_co_pos/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_sa_edi_pos`](../l10n_sa_edi_pos/overview.md), [`l10n_sa_pos`](../l10n_sa_pos/overview.md), [`pos_adyen`](../pos_adyen/overview.md), [`pos_discount`](../pos_discount/overview.md), [`pos_epson_printer`](../pos_epson_printer/overview.md), [`pos_hr`](../pos_hr/overview.md), [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_mercado_pago`](../pos_mercado_pago/overview.md), [`pos_mercury`](../pos_mercury/overview.md), [`pos_mrp`](../pos_mrp/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`pos_online_payment_self_order`](../pos_online_payment_self_order/overview.md), [`pos_paytm`](../pos_paytm/overview.md), [`pos_razorpay`](../pos_razorpay/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md), [`pos_restaurant_adyen`](../pos_restaurant_adyen/overview.md), [`pos_restaurant_stripe`](../pos_restaurant_stripe/overview.md), [`pos_sale`](../pos_sale/overview.md), [`pos_sale_product_configurator`](../pos_sale_product_configurator/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`pos_self_order_adyen`](../pos_self_order_adyen/overview.md), [`pos_self_order_epson_printer`](../pos_self_order_epson_printer/overview.md), [`pos_self_order_stripe`](../pos_self_order_stripe/overview.md), [`pos_six`](../pos_six/overview.md), [`pos_stripe`](../pos_stripe/overview.md), [`pos_viva_wallet`](../pos_viva_wallet/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`barcodes`](../barcodes/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`digest`](../digest/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`portal`](../portal/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sms`](../sms/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`uom`](../uom/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-12-cmr-backup-restore-capacity`](../../conversations/2026-08-12-cmr-backup-restore-capacity.json)
- [`2026-08-12-cmr-endpoint-bootstrap-enterprise-gate`](../../conversations/2026-08-12-cmr-endpoint-bootstrap-enterprise-gate.json)
- [`2026-08-12-cmr-ho-store-isolation`](../../conversations/2026-08-12-cmr-ho-store-isolation.json)
