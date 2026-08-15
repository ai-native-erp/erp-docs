---
layout: page
title: "Türkiye - Nilvera E-Invoice (l10n_tr_nilvera_einvoice)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_tr_nilvera_einvoice/
nav_order: 0
---
# Türkiye - Nilvera E-Invoice — `l10n_tr_nilvera_einvoice`

**Source:** [`agents/modules/generated/l10n_tr_nilvera_einvoice.yaml`](../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) · **Wiki:** [`knowledge/modules/l10n_tr_nilvera_einvoice/overview.md`](../../knowledge/modules/l10n_tr_nilvera_einvoice/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_tr_nilvera_einvoice</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Türkiye - Nilvera E-Invoice</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_tr_nilvera_einvoice</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_tr_nilvera_einvoice"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account_edi_ubl_cii`](account_edi_ubl_cii.md), [`l10n_tr_nilvera`](l10n_tr_nilvera.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.xml.ubl.tr</code></div><div class="role">defined by <code>l10n_tr_nilvera_einvoice</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">defined by <code>l10n_tr_nilvera_einvoice</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.xml.ubl_21</code></div><div class="role">extended by <code>l10n_tr_nilvera_einvoice</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>l10n_tr_nilvera_einvoice</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_tr_nilvera_einvoice</code></div></div>
<div class="model"><div class="name"><code>account.move.send</code></div><div class="role">extended by <code>l10n_tr_nilvera_einvoice</code></div></div>
<div class="model"><div class="name"><code>res.partner.category</code></div><div class="role">extended by <code>l10n_tr_nilvera_einvoice</code></div></div>
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
| `module.account_edi_ubl_cii` | depends_on, extends_model_from, model_extended_by | `agents/modules/generated/account_edi_ubl_cii.yaml` |
| `module.account_fleet` | model_extended_by | `agents/modules/generated/account_fleet.yaml` |
| `module.account_payment` | model_extended_by | `agents/modules/generated/account_payment.yaml` |
| `module.account_peppol` | model_extended_by | `agents/modules/generated/account_peppol.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml)
- Domain: `localization`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_tr_nilvera_einvoice)
- Direct dependencies: [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_tr_nilvera_einvoice`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `account.edi.xml.ubl.tr`
- `account.move` — extended by [`account`](../account/overview.md), [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_debit_note`](../account_debit_note/overview.md), [`account_debit_note_sequence`](../account_debit_note_sequence/overview.md), [`account_edi`](../account_edi/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_fleet`](../account_fleet/overview.md), [`account_payment`](../account_payment/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`account_peppol_selfbilling`](../account_peppol_selfbilling/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_au`](../l10n_au/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_cn`](../l10n_cn/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md), [`l10n_dk_bookkeeping`](../l10n_dk_bookkeeping/overview.md), [`l10n_dk_fik`](../l10n_dk_fik/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_facturae_invoice_period`](../l10n_es_edi_facturae_invoice_period/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_tbai_multi_refund`](../l10n_es_edi_tbai_multi_refund/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_fi`](../l10n_fi/overview.md), [`l10n_fr_facturx_chorus_pro`](../l10n_fr_facturx_chorus_pro/overview.md), [`l10n_fr_invoice_addr`](../l10n_fr_invoice_addr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_fr_pdp_pos`](../l10n_fr_pdp_pos/overview.md), [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id`](../l10n_id/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_ewaybill_port`](../l10n_in_ewaybill_port/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_in_purchase`](../l10n_in_purchase/overview.md), [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md), [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_it_edi_ndd`](../l10n_it_edi_ndd/overview.md), [`l10n_it_edi_ndd_account_dn`](../l10n_it_edi_ndd_account_dn/overview.md), [`l10n_it_edi_withholding`](../l10n_it_edi_withholding/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_mu_account`](../l10n_mu_account/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_nz`](../l10n_nz/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs`](../l10n_rs/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa`](../l10n_sa/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_sa_edi_pos`](../l10n_sa_edi_pos/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`l10n_zm_account`](../l10n_zm_account/overview.md), [`membership`](../membership/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`product_email_template`](../product_email_template/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `account.edi.xml.ubl_21` — defined by [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md)
- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.send` — defined by [`account`](../account/overview.md)
- Extends `res.partner.category` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from, model_extended_by
- [`module.account_audit_trail`](../../../agents/modules/generated/account_audit_trail.yaml) — model_extended_by
- [`module.account_check_printing`](../../../agents/modules/generated/account_check_printing.yaml) — model_extended_by
- [`module.account_debit_note`](../../../agents/modules/generated/account_debit_note.yaml) — model_extended_by
- [`module.account_debit_note_sequence`](../../../agents/modules/generated/account_debit_note_sequence.yaml) — model_extended_by
- [`module.account_edi`](../../../agents/modules/generated/account_edi.yaml) — model_extended_by
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.account_fleet`](../../../agents/modules/generated/account_fleet.yaml) — model_extended_by
- [`module.account_payment`](../../../agents/modules/generated/account_payment.yaml) — model_extended_by
- [`module.account_peppol`](../../../agents/modules/generated/account_peppol.yaml) — model_extended_by
- [`module.account_peppol_response`](../../../agents/modules/generated/account_peppol_response.yaml) — model_extended_by
- [`module.account_peppol_selfbilling`](../../../agents/modules/generated/account_peppol_selfbilling.yaml) — model_extended_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.event_booth_sale`](../../../agents/modules/generated/event_booth_sale.yaml) — model_extended_by
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — model_extended_by
- [`module.l10n_ar`](../../../agents/modules/generated/l10n_ar.yaml) — model_extended_by
- [`module.l10n_ar_withholding`](../../../agents/modules/generated/l10n_ar_withholding.yaml) — model_extended_by
- [`module.l10n_au`](../../../agents/modules/generated/l10n_au.yaml) — model_extended_by
- [`module.l10n_be`](../../../agents/modules/generated/l10n_be.yaml) — model_extended_by
- [`module.l10n_br`](../../../agents/modules/generated/l10n_br.yaml) — model_extended_by
- [`module.l10n_ch`](../../../agents/modules/generated/l10n_ch.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — model_extended_by
- [`module.l10n_cn`](../../../agents/modules/generated/l10n_cn.yaml) — model_extended_by
- [`module.l10n_cz`](../../../agents/modules/generated/l10n_cz.yaml) — model_extended_by
- [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml) — model_extended_by
- [`module.l10n_din5008`](../../../agents/modules/generated/l10n_din5008.yaml) — model_extended_by
- [`module.l10n_dk_bookkeeping`](../../../agents/modules/generated/l10n_dk_bookkeeping.yaml) — model_extended_by
- [`module.l10n_dk_fik`](../../../agents/modules/generated/l10n_dk_fik.yaml) — model_extended_by
- [`module.l10n_dk_oioubl`](../../../agents/modules/generated/l10n_dk_oioubl.yaml) — model_extended_by
- [`module.l10n_ec`](../../../agents/modules/generated/l10n_ec.yaml) — model_extended_by
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
- [`module.l10n_in_sale_stock`](../../../agents/modules/generated/l10n_in_sale_stock.yaml) — model_extended_by
- [`module.l10n_in_withholding`](../../../agents/modules/generated/l10n_in_withholding.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — model_extended_by
- [`module.l10n_it_edi_doi`](../../../agents/modules/generated/l10n_it_edi_doi.yaml) — model_extended_by
- [`module.l10n_it_edi_ndd`](../../../agents/modules/generated/l10n_it_edi_ndd.yaml) — model_extended_by
- [`module.l10n_it_edi_ndd_account_dn`](../../../agents/modules/generated/l10n_it_edi_ndd_account_dn.yaml) — model_extended_by
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
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — model_extended_by
- [`module.l10n_sg_ubl_pint`](../../../agents/modules/generated/l10n_sg_ubl_pint.yaml) — model_extended_by
- [`module.l10n_sk`](../../../agents/modules/generated/l10n_sk.yaml) — model_extended_by
- [`module.l10n_th`](../../../agents/modules/generated/l10n_th.yaml) — model_extended_by
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — depends_on
- [`module.l10n_uy`](../../../agents/modules/generated/l10n_uy.yaml) — model_extended_by
- [`module.l10n_vn_edi_viettel`](../../../agents/modules/generated/l10n_vn_edi_viettel.yaml) — model_extended_by
- [`module.l10n_zm_account`](../../../agents/modules/generated/l10n_zm_account.yaml) — model_extended_by
- [`module.membership`](../../../agents/modules/generated/membership.yaml) — model_extended_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.product_email_template`](../../../agents/modules/generated/product_email_template.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from, model_extended_by
- [`module.sale_expense`](../../../agents/modules/generated/sale_expense.yaml) — model_extended_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — model_extended_by
- [`module.snailmail_account`](../../../agents/modules/generated/snailmail_account.yaml) — model_extended_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — model_extended_by
- [`module.stock_landed_costs`](../../../agents/modules/generated/stock_landed_costs.yaml) — model_extended_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_debit_note`](../account_debit_note/overview.md), [`account_debit_note_sequence`](../account_debit_note_sequence/overview.md), [`account_edi`](../account_edi/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_fleet`](../account_fleet/overview.md), [`account_payment`](../account_payment/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`account_peppol_selfbilling`](../account_peppol_selfbilling/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_au`](../l10n_au/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_cn`](../l10n_cn/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md), [`l10n_dk_bookkeeping`](../l10n_dk_bookkeeping/overview.md), [`l10n_dk_fik`](../l10n_dk_fik/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_facturae_invoice_period`](../l10n_es_edi_facturae_invoice_period/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_tbai_multi_refund`](../l10n_es_edi_tbai_multi_refund/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_fi`](../l10n_fi/overview.md), [`l10n_fr_facturx_chorus_pro`](../l10n_fr_facturx_chorus_pro/overview.md), [`l10n_fr_invoice_addr`](../l10n_fr_invoice_addr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_fr_pdp_pos`](../l10n_fr_pdp_pos/overview.md), [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id`](../l10n_id/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_ewaybill_port`](../l10n_in_ewaybill_port/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_in_purchase`](../l10n_in_purchase/overview.md), [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md), [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_it_edi_ndd`](../l10n_it_edi_ndd/overview.md), [`l10n_it_edi_ndd_account_dn`](../l10n_it_edi_ndd_account_dn/overview.md), [`l10n_it_edi_withholding`](../l10n_it_edi_withholding/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_mu_account`](../l10n_mu_account/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_nz`](../l10n_nz/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs`](../l10n_rs/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa`](../l10n_sa/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_sa_edi_pos`](../l10n_sa_edi_pos/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`l10n_zm_account`](../l10n_zm_account/overview.md), [`membership`](../membership/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`product_email_template`](../product_email_template/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_sale`](../website_sale/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`base`](../base/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: frontend_owl, qa_upgrade.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
