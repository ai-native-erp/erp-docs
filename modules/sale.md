---
layout: page
title: "Sales (sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale/
nav_order: 0
---
# Sales — `sale`

**Source:** [`agents/modules/generated/sale.yaml`](../../agents/modules/generated/sale.yaml) · **Wiki:** [`knowledge/modules/sale/overview.md`](../../knowledge/modules/sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sales</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Sales internal machinery

## Direct dependencies

[`account_payment`](account_payment.md), [`sales_team`](sales_team.md), [`utm`](utm.md)

## Reverse dependencies (modules that depend on this)

[`delivery`](delivery.md), [`l10n_br_sales`](l10n_br_sales.md), [`l10n_din5008_sale`](l10n_din5008_sale.md), [`l10n_fi_sale`](l10n_fi_sale.md), [`l10n_in_sale`](l10n_in_sale.md), [`l10n_it_edi_doi`](l10n_it_edi_doi.md), [`l10n_it_edi_sale`](l10n_it_edi_sale.md), [`mass_mailing_sale`](mass_mailing_sale.md), [`sale_async_emails`](sale_async_emails.md), [`sale_crm`](sale_crm.md), [`sale_loyalty`](sale_loyalty.md), [`sale_management`](sale_management.md), [`sale_order_extension`](sale_order_extension.md), [`sale_product_configurator`](sale_product_configurator.md), [`sale_product_matrix`](sale_product_matrix.md), [`sale_purchase`](sale_purchase.md), [`sale_sms`](sale_sms.md), [`sale_stock`](sale_stock.md), [`spreadsheet_dashboard_sale`](spreadsheet_dashboard_sale.md), [`website_sale`](website_sale.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move</code></div><div class="role">defined by <code>sale</code></div></div>
<div class="model"><div class="name"><code>sale.advance.payment.inv</code></div><div class="role">defined by <code>sale</code></div></div>
<div class="model"><div class="name"><code>sale.mass.cancel.orders</code></div><div class="role">defined by <code>sale</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">defined by <code>sale</code></div></div>
<div class="model"><div class="name"><code>sale.order.cancel</code></div><div class="role">defined by <code>sale</code></div></div>
<div class="model"><div class="name"><code>sale.order.discount</code></div><div class="role">defined by <code>sale</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">defined by <code>sale</code></div></div>
<div class="model"><div class="name"><code>sale.payment.provider.onboarding.wizard</code></div><div class="role">defined by <code>sale</code></div></div>
<div class="model"><div class="name"><code>sale.report</code></div><div class="role">defined by <code>sale</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.analytic.applicability</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>account.analytic.line</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>account.invoice.report</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>account.payment.register</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>analytic.mixin</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>crm.team</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>ir.config_parameter</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>mail.composer.mixin</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>onboarding.onboarding</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>onboarding.onboarding.step</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>payment.link.wizard</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>payment.provider</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>payment.provider.onboarding.wizard</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>payment.transaction</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>portal.mixin</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>product.attribute</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>product.attribute.custom.value</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>product.attribute.value</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>product.catalog.mixin</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>product.document</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>product.packaging</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>utm.campaign</code></div><div class="role">extended by <code>sale</code></div></div>
<div class="model"><div class="name"><code>utm.mixin</code></div><div class="role">extended by <code>sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from, model_extended_by | `agents/modules/generated/account.yaml` |
| `module.account_audit_trail` | model_extended_by | `agents/modules/generated/account_audit_trail.yaml` |
| `module.account_check_printing` | model_extended_by | `agents/modules/generated/account_check_printing.yaml` |
| `module.account_debit_note` | model_extended_by | `agents/modules/generated/account_debit_note.yaml` |
| `module.account_debit_note_sequence` | model_extended_by | `agents/modules/generated/account_debit_note_sequence.yaml` |
| `module.account_edi` | model_extended_by | `agents/modules/generated/account_edi.yaml` |
| `module.account_edi_ubl_cii` | model_extended_by | `agents/modules/generated/account_edi_ubl_cii.yaml` |
| `module.account_fleet` | model_extended_by | `agents/modules/generated/account_fleet.yaml` |
| `module.account_payment` | depends_on, model_extended_by | `agents/modules/generated/account_payment.yaml` |
| `module.account_peppol` | model_extended_by | `agents/modules/generated/account_peppol.yaml` |

## Conversation learnings

- [`2026-08-10-sale-servicenow-patterns`](../../knowledge/conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-11-sale-order-workspace`](../../knowledge/conversations/2026-08-11-sale-order-workspace.json)
- [`2026-08-12-odoo-17-customer-baseline`](../../knowledge/conversations/2026-08-12-odoo-17-customer-baseline.json)
- [`2026-08-13-ho-missing-enterprise-metadata-quarantine`](../../knowledge/conversations/2026-08-13-ho-missing-enterprise-metadata-quarantine.json)
- [`2026-08-14-ho-enterprise-source-restored`](../../knowledge/conversations/2026-08-14-ho-enterprise-source-restored.json)

## Full wiki excerpt

- SME owner: [`module.sale`](../../../agents/modules/generated/sale.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale)
- Direct dependencies: [`account_payment`](../account_payment/overview.md), [`sales_team`](../sales_team/overview.md), [`utm`](../utm/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`delivery`](../delivery/overview.md), [`l10n_br_sales`](../l10n_br_sales/overview.md), [`l10n_din5008_sale`](../l10n_din5008_sale/overview.md), [`l10n_fi_sale`](../l10n_fi_sale/overview.md), [`l10n_in_sale`](../l10n_in_sale/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_it_edi_sale`](../l10n_it_edi_sale/overview.md), [`mass_mailing_sale`](../mass_mailing_sale/overview.md), [`sale_async_emails`](../sale_async_emails/overview.md), [`sale_crm`](../sale_crm/overview.md), [`sale_loyalty`](../sale_loyalty/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_order_extension`](../sale_order_extension/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_sms`](../sale_sms/overview.md), [`sale_stock`](../sale_stock/overview.md), [`spreadsheet_dashboard_sale`](../spreadsheet_dashboard_sale/overview.md), [`website_sale`](../website_sale/overview.md)
- Impact graph: [`module:sale`](../../impact-graph.json)

## Purpose

Sales internal machinery

## Model relationships

- `account.move` — extended by [`account`](../account/overview.md), [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_debit_note`](../account_debit_note/overview.md), [`account_debit_note_sequence`](../account_debit_note_sequence/overview.md), [`account_edi`](../account_edi/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_fleet`](../account_fleet/overview.md), [`account_payment`](../account_payment/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`account_peppol_selfbilling`](../account_peppol_selfbilling/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_au`](../l10n_au/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_cn`](../l10n_cn/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md), [`l10n_dk_bookkeeping`](../l10n_dk_bookkeeping/overview.md), [`l10n_dk_fik`](../l10n_dk_fik/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_facturae_invoice_period`](../l10n_es_edi_facturae_invoice_period/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_tbai_multi_refund`](../l10n_es_edi_tbai_multi_refund/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_fi`](../l10n_fi/overview.md), [`l10n_fr_facturx_chorus_pro`](../l10n_fr_facturx_chorus_pro/overview.md), [`l10n_fr_invoice_addr`](../l10n_fr_invoice_addr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_fr_pdp_pos`](../l10n_fr_pdp_pos/overview.md), [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id`](../l10n_id/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_ewaybill_port`](../l10n_in_ewaybill_port/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_in_purchase`](../l10n_in_purchase/overview.md), [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md), [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_it_edi_ndd`](../l10n_it_edi_ndd/overview.md), [`l10n_it_edi_ndd_account_dn`](../l10n_it_edi_ndd_account_dn/overview.md), [`l10n_it_edi_withholding`](../l10n_it_edi_withholding/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_mu_account`](../l10n_mu_account/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_nz`](../l10n_nz/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs`](../l10n_rs/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa`](../l10n_sa/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_sa_edi_pos`](../l10n_sa_edi_pos/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`l10n_zm_account`](../l10n_zm_account/overview.md), [`membership`](../membership/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`product_email_template`](../product_email_template/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_sale`](../website_sale/overview.md)
- `sale.advance.payment.inv` — extended by [`l10n_in_sale`](../l10n_in_sale/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md)
- `sale.mass.cancel.orders`
- `sale.order` — extended by [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`l10n_ar_website_sale`](../l10n_ar_website_sale/overview.md), [`l10n_br_sales`](../l10n_br_sales/overview.md), [`l10n_din5008_sale`](../l10n_din5008_sale/overview.md), [`l10n_ec_website_sale`](../l10n_ec_website_sale/overview.md), [`l10n_fi_sale`](../l10n_fi_sale/overview.md), [`l10n_in_sale`](../l10n_in_sale/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_it_edi_sale`](../l10n_it_edi_sale/overview.md), [`mass_mailing_sale`](../mass_mailing_sale/overview.md), [`pos_sale`](../pos_sale/overview.md), [`repair`](../repair/overview.md), [`sale_async_emails`](../sale_async_emails/overview.md), [`sale_crm`](../sale_crm/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_loyalty`](../sale_loyalty/overview.md), [`sale_loyalty_delivery`](../sale_loyalty_delivery/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_margin`](../sale_margin/overview.md), [`sale_mrp`](../sale_mrp/overview.md), [`sale_order_extension`](../sale_order_extension/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_purchase_stock`](../sale_purchase_stock/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_mrp`](../website_sale_mrp/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md), [`website_sale_product_configurator`](../website_sale_product_configurator/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md)
- `sale.order.cancel` — extended by [`sale_purchase`](../sale_purchase/overview.md), [`sale_stock`](../sale_stock/overview.md)
- `sale.order.discount`
- `sale.order.line` — extended by [`delivery`](../delivery/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`pos_sale`](../pos_sale/overview.md), [`pos_sale_loyalty`](../pos_sale_loyalty/overview.md), [`repair`](../repair/overview.md), [`sale_expense_margin`](../sale_expense_margin/overview.md), [`sale_loyalty`](../sale_loyalty/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_margin`](../sale_margin/overview.md), [`sale_mrp`](../sale_mrp/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_project_stock`](../sale_project_stock/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_service`](../sale_service/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_stock_margin`](../sale_stock_margin/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`sale_timesheet_margin`](../sale_timesheet_margin/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md)
- `sale.payment.provider.onboarding.wizard`
- `sale.report` — extended by [`pos_sale`](../pos_sale/overview.md), [`pos_sale_margin`](../pos_sale_margin/overview.md), [`sale_margin`](../sale_margin/overview.md), [`sale_stock`](../sale_stock/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `account.analytic.applicability` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.analytic.line` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.invoice.report` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `account.payment.register` — defined by [`account`](../account/overview.md)
- Extends `analytic.mixin` — defined by [`analytic`](../analytic/overview.md)
- Extends `crm.team` — defined by [`crm`](../crm/overview.md), [`sales_team`](../sales_team/overview.md)
- Extends `ir.config_parameter` — defined by [`base`](../base/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.composer.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `onboarding.onboarding` — defined by [`onboarding`](../onboarding/overview.md)
- Extends `onboarding.onboarding.step` — defined by [`onboarding`](../onboarding/overview.md)
- Extends `payment.link.wizard` — defined by [`payment`](../payment/overview.md)
- Extends `payment.provider` — defined by [`payment`](../payment/overview.md)
- Extends `payment.provider.onboarding.wizard` — defined by [`payment`](../payment/overview.md)
- Extends `payment.transaction` — defined by [`payment`](../payment/overview.md)
- Extends `portal.mixin` — defined by [`portal`](../portal/overview.md)
- Extends `product.attribute` — defined by [`product`](../product/overview.md)
- Extends `product.attribute.custom.value` — defined by [`product`](../product/overview.md)
- Extends `product.attribute.value` — defined by [`product`](../product/overview.md)
- Extends `product.catalog.mixin` — defined by [`product`](../product/overview.md)
- Extends `product.document` — defined by [`product`](../product/overview.md)
- Extends `product.packaging` — defined by [`product`](../product/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `sale.order` — framework/dynamic owner
- Extends `sale.order.line` — framework/dynamic owner
- Extends `utm.campaign` — defined by [`utm`](../utm/overview.md)
- Extends `utm.mixin` — defined by [`utm`](../utm/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from, model_extended_by
- [`module.account_audit_trail`](../../../agents/modules/generated/account_audit_trail.yaml) — model_extended_by
- [`module.account_check_printing`](../../../agents/modules/generated/account_check_printing.yaml) — model_extended_by
- [`module.account_debit_note`](../../../agents/modules/generated/account_debit_note.yaml) — model_extended_by
- [`module.account_debit_note_sequence`](../../../agents/modules/generated/account_debit_note_sequence.yaml) — model_extended_by
- [`module.account_edi`](../../../agents/modules/generated/account_edi.yaml) — model_extended_by
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — model_extended_by
- [`module.account_fleet`](../../../agents/modules/generated/account_fleet.yaml) — model_extended_by
- [`module.account_payment`](../../../agents/modules/generated/account_payment.yaml) — depends_on, model_extended_by
- [`module.account_peppol`](../../../agents/modules/generated/account_peppol.yaml) — model_extended_by
- [`module.account_peppol_response`](../../../agents/modules/generated/account_peppol_response.yaml) — model_extended_by
- [`module.account_peppol_selfbilling`](../../../agents/modules/generated/account_peppol_selfbilling.yaml) — model_extended_by
- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — model_extended_by, required_by
- [`module.delivery_mondialrelay`](../../../agents/modules/generated/delivery_mondialrelay.yaml) — model_extended_by
- [`module.event_booth_sale`](../../../agents/modules/generated/event_booth_sale.yaml) — model_extended_by
- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — model_extended_by
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — model_extended_by
- [`module.l10n_ar`](../../../agents/modules/generated/l10n_ar.yaml) — model_extended_by
- [`module.l10n_ar_website_sale`](../../../agents/modules/generated/l10n_ar_website_sale.yaml) — model_extended_by
- [`module.l10n_ar_withholding`](../../../agents/modules/generated/l10n_ar_withholding.yaml) — model_extended_by
- [`module.l10n_au`](../../../agents/modules/generated/l10n_au.yaml) — model_extended_by
- [`module.l10n_be`](../../../agents/modules/generated/l10n_be.yaml) — model_extended_by
- [`module.l10n_br`](../../../agents/modules/generated/l10n_br.yaml) — model_extended_by
- [`module.l10n_br_sales`](../../../agents/modules/generated/l10n_br_sales.yaml) — model_extended_by, required_by
- [`module.l10n_ch`](../../../agents/modules/generated/l10n_ch.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from, model_extended_by
- [`module.l10n_cn`](../../../agents/modules/generated/l10n_cn.yaml) — model_extended_by
- [`module.l10n_cz`](../../../agents/modules/generated/l10n_cz.yaml) — model_extended_by
- [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml) — model_extended_by
- [`module.l10n_din5008`](../../../agents/modules/generated/l10n_din5008.yaml) — model_extended_by
- [`module.l10n_din5008_sale`](../../../agents/modules/generated/l10n_din5008_sale.yaml) — model_extended_by, required_by
- [`module.l10n_dk_bookkeeping`](../../../agents/modules/generated/l10n_dk_bookkeeping.yaml) — model_extended_by
- [`module.l10n_dk_fik`](../../../agents/modules/generated/l10n_dk_fik.yaml) — model_extended_by
- [`module.l10n_dk_oioubl`](../../../agents/modules/generated/l10n_dk_oioubl.yaml) — model_extended_by
- [`module.l10n_ec`](../../../agents/modules/generated/l10n_ec.yaml) — model_extended_by
- [`module.l10n_ec_website_sale`](../../../agents/modules/generated/l10n_ec_website_sale.yaml) — model_extended_by
- [`module.l10n_eg_edi_eta`](../../../agents/modules/generated/l10n_eg_edi_eta.yaml) — model_extended_by
- [`module.l10n_es`](../../../agents/modules/generated/l10n_es.yaml) — model_extended_by
- [`module.l10n_es_edi_facturae`](../../../agents/modules/generated/l10n_es_edi_facturae.yaml) — model_extended_by
- [`module.l10n_es_edi_facturae_adm_centers`](../../../agents/modules/generated/l10n_es_edi_facturae_adm_centers.yaml) — model_extended_by
- [`module.l10n_es_edi_facturae_invoice_period`](../../../agents/modules/generated/l10n_es_edi_facturae_invoice_period.yaml) — model_extended_by
- [`module.l10n_es_edi_sii`](../../../agents/modules/generated/l10n_es_edi_sii.yaml) — model_extended_by
- [`module.l10n_es_edi_tbai`](../../../agents/modules/generated/l10n_es_edi_tbai.yaml) — model_extended_by
- [`module.l10n_es_edi_tbai_multi_refund`](../../../agents/modules/generated/l10n_es_edi_tbai_multi_refund.yaml) — model_extended_by
- [`module.l10n_es_edi_verifactu`](../../../agents/modules/generated/l10n_es_edi_verifactu.yaml) — model_extended_by
- [`module.l10n_es_edi_verifactu_pos`](../../../agents/modules/generated/l10n_es_edi_verifactu_pos.yaml) — model_extended_by
- [`module.l10n_es_pos`](../../../agents/modules/generated/l10n_es_pos.yaml) — model_extended_by
- [`module.l10n_es_pos_tbai`](../../../agents/modules/generated/l10n_es_pos_tbai.yaml) — model_extended_by
- [`module.l10n_fi`](../../../agents/modules/generated/l10n_fi.yaml) — model_extended_by
- [`module.l10n_fi_sale`](../../../agents/modules/generated/l10n_fi_sale.yaml) — model_extended_by, required_by
- [`module.l10n_fr_facturx_chorus_pro`](../../../agents/modules/generated/l10n_fr_facturx_chorus_pro.yaml) — model_extended_by
- [`module.l10n_fr_invoice_addr`](../../../agents/modules/generated/l10n_fr_invoice_addr.yaml) — model_extended_by
- [`module.l10n_fr_pdp`](../../../agents/modules/generated/l10n_fr_pdp.yaml) — model_extended_by
- [`module.l10n_fr_pdp_pos`](../../../agents/modules/generated/l10n_fr_pdp_pos.yaml) — model_extended_by
- [`module.l10n_gcc_invoice`](../../../agents/modules/generated/l10n_gcc_invoice.yaml) — model_extended_by
- [`module.l10n_hu`](../../../agents/modules/generated/l10n_hu.yaml) — model_extended_by
- [`module.l10n_hu_edi`](../../../agents/modules/generated/l10n_hu_edi.yaml) — model_extended_by
- [`module.l10n_id`](../../../agents/modules/generated/l10n_id.yaml) — model_extended_by
- [`module.l10n_id_efaktur`](../../../agents/modules/generated/l10n_id_efaktur.yaml) — model_extended_by
- [`module.l10n_id_efaktur_coretax`](../../../agents/modules/generated/l10n_id_efaktur_coretax.yaml) — model_extended_by
- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — model_extended_by
- [`module.l10n_in_edi`](../../../agents/modules/generated/l10n_in_edi.yaml) — model_extended_by
- [`module.l10n_in_edi_ewaybill`](../../../agents/modules/generated/l10n_in_edi_ewaybill.yaml) — model_extended_by
- [`module.l10n_in_ewaybill_port`](../../../agents/modules/generated/l10n_in_ewaybill_port.yaml) — model_extended_by
- [`module.l10n_in_pos`](../../../agents/modules/generated/l10n_in_pos.yaml) — model_extended_by
- [`module.l10n_in_purchase`](../../../agents/modules/generated/l10n_in_purchase.yaml) — model_extended_by
- [`module.l10n_in_purchase_stock`](../../../agents/modules/generated/l10n_in_purchase_stock.yaml) — model_extended_by
- [`module.l10n_in_sale`](../../../agents/modules/generated/l10n_in_sale.yaml) — model_extended_by, required_by
- [`module.l10n_in_sale_stock`](../../../agents/modules/generated/l10n_in_sale_stock.yaml) — model_extended_by
- [`module.l10n_in_withholding`](../../../agents/modules/generated/l10n_in_withholding.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from, model_extended_by
- [`module.l10n_it_edi_doi`](../../../agents/modules/generated/l10n_it_edi_doi.yaml) — model_extended_by, required_by
- [`module.l10n_it_edi_ndd`](../../../agents/modules/generated/l10n_it_edi_ndd.yaml) — model_extended_by
- [`module.l10n_it_edi_ndd_account_dn`](../../../agents/modules/generated/l10n_it_edi_ndd_account_dn.yaml) — model_extended_by
- [`module.l10n_it_edi_sale`](../../../agents/modules/generated/l10n_it_edi_sale.yaml) — model_extended_by, required_by
- [`module.l10n_it_edi_withholding`](../../../agents/modules/generated/l10n_it_edi_withholding.yaml) — model_extended_by
- [`module.l10n_it_stock_ddt`](../../../agents/modules/generated/l10n_it_stock_ddt.yaml) — model_extended_by
- [`module.l10n_jo_edi`](../../../agents/modules/generated/l10n_jo_edi.yaml) — model_extended_by
- [`module.l10n_jo_edi_extended`](../../../agents/modules/generated/l10n_jo_edi_extended.yaml) — model_extended_by
- [`module.l10n_ke_edi_tremol`](../../../agents/modules/generated/l10n_ke_edi_tremol.yaml) — model_extended_by
- [`module.l10n_latam_invoice_document`](../../../agents/modules/generated/l10n_latam_invoice_document.yaml) — model_extended_by
- [`module.l10n_mu_account`](../../../agents/modules/generated/l10n_mu_account.yaml) — model_extended_by
- [`module.l10n_my_edi`](../../../agents/modules/generated/l10n_my_edi.yaml) — model_extended_by
- [`module.l10n_my_edi_extended`](../../../agents/modules/generated/l10n_my_edi_extended.yaml) — model_extended_by
- [`module.l10n_no`](../../../agents/modules/generated/l10n_no.yaml) — model_extended_by
- [`module.l10n_nz`](../../../agents/modules/generated/l10n_nz.yaml) — model_extended_by
- [`module.l10n_pe`](../../../agents/modules/generated/l10n_pe.yaml) — model_extended_by
- [`module.l10n_ph`](../../../agents/modules/generated/l10n_ph.yaml) — model_extended_by
- [`module.l10n_pl`](../../../agents/modules/generated/l10n_pl.yaml) — model_extended_by
- [`module.l10n_ro_efactura`](../../../agents/modules/generated/l10n_ro_efactura.yaml) — model_extended_by
- [`module.l10n_ro_efactura_synchronize`](../../../agents/modules/generated/l10n_ro_efactura_synchronize.yaml) — model_extended_by
- [`module.l10n_rs`](../../../agents/modules/generated/l10n_rs.yaml) — model_extended_by
- [`module.l10n_rs_edi`](../../../agents/modules/generated/l10n_rs_edi.yaml) — model_extended_by
- [`module.l10n_sa`](../../../agents/modules/generated/l10n_sa.yaml) — model_extended_by
- [`module.l10n_sa_edi`](../../../agents/modules/generated/l10n_sa_edi.yaml) — model_extended_by
- [`module.l10n_sa_edi_pos`](../../../agents/modules/generated/l10n_sa_edi_pos.yaml) — model_extended_by
- [`module.l10n_se`](../../../agents/modules/generated/l10n_se.yaml) — model_extended_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from, model_extended_by
- [`module.l10n_sg_ubl_pint`](../../../agents/modules/generated/l10n_sg_ubl_pint.yaml) — model_extended_by
- [`module.l10n_sk`](../../../agents/modules/generated/l10n_sk.yaml) — model_extended_by
- [`module.l10n_th`](../../../agents/modules/generated/l10n_th.yaml) — model_extended_by
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from, model_extended_by
- [`module.l10n_uy`](../../../agents/modules/generated/l10n_uy.yaml) — model_extended_by
- [`module.l10n_vn_edi_viettel`](../../../agents/modules/generated/l10n_vn_edi_viettel.yaml) — model_extended_by
- [`module.l10n_zm_account`](../../../agents/modules/generated/l10n_zm_account.yaml) — model_extended_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing_sale`](../../../agents/modules/generated/mass_mailing_sale.yaml) — model_extended_by, required_by
- [`module.membership`](../../../agents/modules/generated/membership.yaml) — model_extended_by
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.onboarding`](../../../agents/modules/generated/onboarding.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — extends_model_from
- [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml) — model_extended_by
- [`module.pos_sale_loyalty`](../../../agents/modules/generated/pos_sale_loyalty.yaml) — model_extended_by
- [`module.pos_sale_margin`](../../../agents/modules/generated/pos_sale_margin.yaml) — model_extended_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.product_email_template`](../../../agents/modules/generated/product_email_template.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from, model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from, model_extended_by
- [`module.repair`](../../../agents/modules/generated/repair.yaml) — model_extended_by
- [`module.sale_async_emails`](../../../agents/modules/generated/sale_async_emails.yaml) — model_extended_by, required_by
- [`module.sale_crm`](../../../agents/modules/generated/sale_crm.yaml) — model_extended_by, required_by
- [`module.sale_expense`](../../../agents/modules/generated/sale_expense.yaml) — model_extended_by
- [`module.sale_expense_margin`](../../../agents/modules/generated/sale_expense_margin.yaml) — model_extended_by
- [`module.sale_loyalty`](../../../agents/modules/generated/sale_loyalty.yaml) — model_extended_by, required_by
- [`module.sale_loyalty_delivery`](../../../agents/modules/generated/sale_loyalty_delivery.yaml) — model_extended_by
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — model_extended_by, required_by
- [`module.sale_margin`](../../../agents/modules/generated/sale_margin.yaml) — model_extended_by
- [`module.sale_mrp`](../../../agents/modules/generated/sale_mrp.yaml) — model_extended_by
- [`module.sale_order_extension`](../../../agents/modules/generated/sale_order_extension.yaml) — model_extended_by, required_by
- [`module.sale_pdf_quote_builder`](../../../agents/modules/generated/sale_pdf_quote_builder.yaml) — model_extended_by
- [`module.sale_product_configurator`](../../../agents/modules/generated/sale_product_configurator.yaml) — model_extended_by, required_by
- [`module.sale_product_matrix`](../../../agents/modules/generated/sale_product_matrix.yaml) — model_extended_by, required_by
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — model_extended_by
- [`module.sale_project_stock`](../../../agents/modules/generated/sale_project_stock.yaml) — model_extended_by
- [`module.sale_purchase`](../../../agents/modules/generated/sale_purchase.yaml) — model_extended_by, required_by
- [`module.sale_purchase_stock`](../../../agents/modules/generated/sale_purchase_stock.yaml) — model_extended_by
- [`module.sale_service`](../../../agents/modules/generated/sale_service.yaml) — model_extended_by
- [`module.sale_sms`](../../../agents/modules/generated/sale_sms.yaml) — required_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by, required_by
- [`module.sale_stock_margin`](../../../agents/modules/generated/sale_stock_margin.yaml) — model_extended_by
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — model_extended_by
- [`module.sale_timesheet_margin`](../../../agents/modules/generated/sale_timesheet_margin.yaml) — model_extended_by
- [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml) — depends_on, extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.snailmail_account`](../../../agents/modules/generated/snailmail_account.yaml) — model_extended_by
- [`module.spreadsheet_dashboard_sale`](../../../agents/modules/generated/spreadsheet_dashboard_sale.yaml) — required_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from, model_extended_by
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — model_extended_by
- [`module.stock_dropshipping`](../../../agents/modules/generated/stock_dropshipping.yaml) — model_extended_by
- [`module.stock_landed_costs`](../../../agents/modules/generated/stock_landed_costs.yaml) — model_extended_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — depends_on, extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_event_booth_sale`](../../../agents/modules/generated/website_event_booth_sale.yaml) — model_extended_by
- [`module.website_event_sale`](../../../agents/modules/generated/website_event_sale.yaml) — model_extended_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from, model_extended_by, required_by
- [`module.website_sale_loyalty`](../../../agents/modules/generated/website_sale_loyalty.yaml) — model_extended_by
- [`module.website_sale_mondialrelay`](../../../agents/modules/generated/website_sale_mondialrelay.yaml) — model_extended_by
- [`module.website_sale_mrp`](../../../agents/modules/generated/website_sale_mrp.yaml) — model_extended_by
- [`module.website_sale_picking`](../../../agents/modules/generated/website_sale_picking.yaml) — model_extended_by
- [`module.website_sale_product_configurator`](../../../agents/modules/generated/website_sale_product_configurator.yaml) — model_extended_by
- [`module.website_sale_slides`](../../../agents/modules/generated/website_sale_slides.yaml) — model_extended_by
- [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml) — model_extended_by

## Regression impact checklist

- Review 20 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_debit_note`](../account_debit_note/overview.md), [`account_debit_note_sequence`](../account_debit_note_sequence/overview.md), [`account_edi`](../account_edi/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_fleet`](../account_fleet/overview.md), [`account_payment`](../account_payment/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`account_peppol_selfbilling`](../account_peppol_selfbilling/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_website_sale`](../l10n_ar_website_sale/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_au`](../l10n_au/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_br_sales`](../l10n_br_sales/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_cn`](../l10n_cn/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md), [`l10n_din5008_sale`](../l10n_din5008_sale/overview.md), [`l10n_dk_bookkeeping`](../l10n_dk_bookkeeping/overview.md), [`l10n_dk_fik`](../l10n_dk_fik/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_ec_website_sale`](../l10n_ec_website_sale/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_facturae_invoice_period`](../l10n_es_edi_facturae_invoice_period/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_tbai_multi_refund`](../l10n_es_edi_tbai_multi_refund/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_fi`](../l10n_fi/overview.md), [`l10n_fi_sale`](../l10n_fi_sale/overview.md), [`l10n_fr_facturx_chorus_pro`](../l10n_fr_facturx_chorus_pro/overview.md), [`l10n_fr_invoice_addr`](../l10n_fr_invoice_addr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_fr_pdp_pos`](../l10n_fr_pdp_pos/overview.md), [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id`](../l10n_id/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_ewaybill_port`](../l10n_in_ewaybill_port/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_in_purchase`](../l10n_in_purchase/overview.md), [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md), [`l10n_in_sale`](../l10n_in_sale/overview.md), [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_it_edi_ndd`](../l10n_it_edi_ndd/overview.md), [`l10n_it_edi_ndd_account_dn`](../l10n_it_edi_ndd_account_dn/overview.md), [`l10n_it_edi_sale`](../l10n_it_edi_sale/overview.md), [`l10n_it_edi_withholding`](../l10n_it_edi_withholding/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_mu_account`](../l10n_mu_account/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_nz`](../l10n_nz/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs`](../l10n_rs/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa`](../l10n_sa/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_sa_edi_pos`](../l10n_sa_edi_pos/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`l10n_zm_account`](../l10n_zm_account/overview.md), [`mass_mailing_sale`](../mass_mailing_sale/overview.md), [`membership`](../membership/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_sale`](../pos_sale/overview.md), [`pos_sale_loyalty`](../pos_sale_loyalty/overview.md), [`pos_sale_margin`](../pos_sale_margin/overview.md), [`product_email_template`](../product_email_template/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale_async_emails`](../sale_async_emails/overview.md), [`sale_crm`](../sale_crm/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_expense_margin`](../sale_expense_margin/overview.md), [`sale_loyalty`](../sale_loyalty/overview.md), [`sale_loyalty_delivery`](../sale_loyalty_delivery/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_margin`](../sale_margin/overview.md), [`sale_mrp`](../sale_mrp/overview.md), [`sale_order_extension`](../sale_order_extension/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_project_stock`](../sale_project_stock/overview.md), [`sale_purchase`](../sale_purchase/overview.md), [`sale_purchase_stock`](../sale_purchase_stock/overview.md), [`sale_service`](../sale_service/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_stock_margin`](../sale_stock_margin/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`sale_timesheet_margin`](../sale_timesheet_margin/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_mrp`](../website_sale_mrp/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md), [`website_sale_product_configurator`](../website_sale_product_configurator/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`analytic`](../analytic/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`mrp_account`](../mrp_account/overview.md), [`onboarding`](../onboarding/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`portal`](../portal/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`stock_account`](../stock_account/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`utm`](../utm/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-10-sale-servicenow-patterns`](../../conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-11-sale-order-workspace`](../../conversations/2026-08-11-sale-order-workspace.json)
- [`2026-08-12-odoo-17-customer-baseline`](../../conversations/2026-08-12-odoo-17-customer-baseline.json)
- [`2026-08-13-ho-missing-enterprise-metadata-quarantine`](../../conversations/2026-08-13-ho-missing-enterprise-metadata-quarantine.json)
- [`2026-08-14-ho-enterprise-source-restored`](../../conversations/2026-08-14-ho-enterprise-source-restored.json)
