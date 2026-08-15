---
layout: page
title: "Invoicing (account)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account/
nav_order: 0
---
# Invoicing — `account`

**Source:** [`agents/modules/generated/account.yaml`](../../agents/modules/generated/account.yaml) · **Wiki:** [`knowledge/modules/account/overview.md`](../../knowledge/modules/account/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Invoicing</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Invoices & Payments

## Direct dependencies

[`analytic`](analytic.md), [`base_setup`](base_setup.md), [`digest`](digest.md), [`onboarding`](onboarding.md), [`portal`](portal.md), [`product`](product.md)

## Reverse dependencies (modules that depend on this)

[`account_add_gln`](account_add_gln.md), [`account_audit_trail`](account_audit_trail.md), [`account_check_printing`](account_check_printing.md), [`account_debit_note`](account_debit_note.md), [`account_edi`](account_edi.md), [`account_edi_proxy_client`](account_edi_proxy_client.md), [`account_edi_ubl_cii`](account_edi_ubl_cii.md), [`account_fleet`](account_fleet.md), [`account_lock`](account_lock.md), [`account_payment`](account_payment.md), [`account_payment_term`](account_payment_term.md), [`account_qr_code_emv`](account_qr_code_emv.md), [`account_qr_code_sepa`](account_qr_code_sepa.md), [`account_tax_python`](account_tax_python.md), [`account_test`](account_test.md), [`account_update_tax_tags`](account_update_tax_tags.md), [`base_iban`](base_iban.md), [`base_vat`](base_vat.md), [`hr_expense`](hr_expense.md), [`l10n_ae`](l10n_ae.md), [`l10n_at`](l10n_at.md), [`l10n_au`](l10n_au.md), [`l10n_bd`](l10n_bd.md), [`l10n_be`](l10n_be.md), [`l10n_bg`](l10n_bg.md), [`l10n_bh`](l10n_bh.md), [`l10n_bo`](l10n_bo.md), [`l10n_br`](l10n_br.md), [`l10n_ca`](l10n_ca.md), [`l10n_ch`](l10n_ch.md), [`l10n_cl`](l10n_cl.md), [`l10n_cn`](l10n_cn.md), [`l10n_co`](l10n_co.md), [`l10n_cr`](l10n_cr.md), [`l10n_cy`](l10n_cy.md), [`l10n_cz`](l10n_cz.md), [`l10n_din5008`](l10n_din5008.md), [`l10n_dk`](l10n_dk.md), [`l10n_do`](l10n_do.md), [`l10n_dz`](l10n_dz.md), [`l10n_ec`](l10n_ec.md), [`l10n_ee`](l10n_ee.md), [`l10n_eg`](l10n_eg.md), [`l10n_es`](l10n_es.md), [`l10n_et`](l10n_et.md), [`l10n_eu_oss`](l10n_eu_oss.md), [`l10n_fi`](l10n_fi.md), [`l10n_fr`](l10n_fr.md), [`l10n_fr_facturx_chorus_pro`](l10n_fr_facturx_chorus_pro.md), [`l10n_fr_fec`](l10n_fr_fec.md), [`l10n_gcc_invoice`](l10n_gcc_invoice.md), [`l10n_gr`](l10n_gr.md), [`l10n_gt`](l10n_gt.md), [`l10n_hn`](l10n_hn.md), [`l10n_hr`](l10n_hr.md), [`l10n_hr_kuna`](l10n_hr_kuna.md), [`l10n_hu`](l10n_hu.md), [`l10n_id`](l10n_id.md), [`l10n_ie`](l10n_ie.md), [`l10n_il`](l10n_il.md), [`l10n_iq`](l10n_iq.md), [`l10n_it`](l10n_it.md), [`l10n_jo`](l10n_jo.md), [`l10n_jp`](l10n_jp.md), [`l10n_ke`](l10n_ke.md), [`l10n_kw`](l10n_kw.md), [`l10n_kz`](l10n_kz.md), [`l10n_latam_invoice_document`](l10n_latam_invoice_document.md), [`l10n_lb_account`](l10n_lb_account.md), [`l10n_lt`](l10n_lt.md), [`l10n_lu`](l10n_lu.md), [`l10n_lv`](l10n_lv.md), [`l10n_ma`](l10n_ma.md), [`l10n_mn`](l10n_mn.md), [`l10n_mr`](l10n_mr.md), [`l10n_mt`](l10n_mt.md), [`l10n_mu_account`](l10n_mu_account.md), [`l10n_mx`](l10n_mx.md), [`l10n_my`](l10n_my.md), [`l10n_mz`](l10n_mz.md), [`l10n_nl`](l10n_nl.md), [`l10n_no`](l10n_no.md), [`l10n_nz`](l10n_nz.md), [`l10n_pa`](l10n_pa.md), [`l10n_pe`](l10n_pe.md), [`l10n_ph`](l10n_ph.md), [`l10n_pk`](l10n_pk.md), [`l10n_pl`](l10n_pl.md), [`l10n_pt`](l10n_pt.md), [`l10n_qa`](l10n_qa.md), [`l10n_ro`](l10n_ro.md), [`l10n_rs`](l10n_rs.md), [`l10n_rw`](l10n_rw.md), [`l10n_sa`](l10n_sa.md), [`l10n_se`](l10n_se.md), [`l10n_si`](l10n_si.md), [`l10n_sk`](l10n_sk.md), [`l10n_syscohada`](l10n_syscohada.md), [`l10n_tn`](l10n_tn.md), [`l10n_tr`](l10n_tr.md), [`l10n_tw`](l10n_tw.md), [`l10n_tz_account`](l10n_tz_account.md), [`l10n_ua`](l10n_ua.md), [`l10n_ug`](l10n_ug.md), [`l10n_uk`](l10n_uk.md), [`l10n_us`](l10n_us.md), [`l10n_uy`](l10n_uy.md), [`l10n_ve`](l10n_ve.md), [`l10n_za`](l10n_za.md), [`l10n_zm_account`](l10n_zm_account.md), [`membership`](membership.md), [`product_email_template`](product_email_template.md), [`product_margin`](product_margin.md), [`product_matrix`](product_matrix.md), [`project_account`](project_account.md), [`purchase`](purchase.md), [`snailmail_account`](snailmail_account.md), [`spreadsheet_account`](spreadsheet_account.md), [`spreadsheet_dashboard_account`](spreadsheet_dashboard_account.md), [`stock_account`](stock_account.md), [`test_main_flows`](test_main_flows.md), [`website_crm_partner_assign`](website_crm_partner_assign.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.account</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.account.tag</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.accrued.orders.wizard</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.automatic.entry.wizard</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.bank.statement</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.bank.statement.line</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.cash.rounding</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.financial.year.op</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.fiscal.position</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.fiscal.position.account</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.fiscal.position.tax</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.full.reconcile</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.group</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.incoterms</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.invoice.report</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.journal.group</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.move.reversal</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.move.send</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.partial.reconcile</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.payment</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.payment.method</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.payment.method.line</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.payment.register</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.payment.term</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.payment.term.line</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.reconcile.model</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.reconcile.model.line</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.reconcile.model.partner.mapping</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.report</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.report.column</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.report.expression</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.report.external.value</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.report.line</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.resequence.wizard</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.root</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.setup.bank.manual.config</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.tax</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.tax.group</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.tax.repartition.line</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.tour.upload.bill</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.tour.upload.bill.email.confirm</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.unreconcile</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>report.account.report_hash_integrity</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>report.account.report_invoice</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>report.account.report_invoice_with_payments</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>res.partner.bank</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>sequence.mixin</code></div><div class="role">defined by <code>account</code></div></div>
<div class="model"><div class="name"><code>validate.account.move</code></div><div class="role">defined by <code>account</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.analytic.account</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.analytic.applicability</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.analytic.distribution.model</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.analytic.line</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.bank.statement</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.bank.statement.line</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.payment</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.reconcile.model</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>account.reconcile.model.line</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>analytic.mixin</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>base.document.layout</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>base.partner.merge.automatic.wizard</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>decimal.precision</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>digest.digest</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>ir.actions.report</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>ir.module.module</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>kpi.provider</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>mail.alias.mixin.optional</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>mail.thread.main.attachment</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>onboarding.onboarding</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>onboarding.onboarding.step</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>portal.mixin</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>product.category</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>report.account.report_invoice</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>res.currency</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>res.groups</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>res.partner.bank</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>sequence.mixin</code></div><div class="role">extended by <code>account</code></div></div>
<div class="model"><div class="name"><code>uom.uom</code></div><div class="role">extended by <code>account</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account_add_gln` | model_extended_by, required_by | `agents/modules/generated/account_add_gln.yaml` |
| `module.account_audit_trail` | model_extended_by, required_by | `agents/modules/generated/account_audit_trail.yaml` |
| `module.account_check_printing` | model_extended_by, required_by | `agents/modules/generated/account_check_printing.yaml` |
| `module.account_debit_note` | model_extended_by, required_by | `agents/modules/generated/account_debit_note.yaml` |
| `module.account_debit_note_sequence` | model_extended_by | `agents/modules/generated/account_debit_note_sequence.yaml` |
| `module.account_edi` | model_extended_by, required_by | `agents/modules/generated/account_edi.yaml` |
| `module.account_edi_proxy_client` | model_extended_by, required_by | `agents/modules/generated/account_edi_proxy_client.yaml` |
| `module.account_edi_ubl_cii` | model_extended_by, required_by | `agents/modules/generated/account_edi_ubl_cii.yaml` |
| `module.account_edi_ubl_cii_tax_extension` | model_extended_by | `agents/modules/generated/account_edi_ubl_cii_tax_extension.yaml` |
| `module.account_fleet` | model_extended_by, required_by | `agents/modules/generated/account_fleet.yaml` |

## Conversation learnings

- [`2026-08-12-cmr-endpoint-bootstrap-enterprise-gate`](../../knowledge/conversations/2026-08-12-cmr-endpoint-bootstrap-enterprise-gate.json)
- [`2026-08-12-cmr-ho-store-isolation`](../../knowledge/conversations/2026-08-12-cmr-ho-store-isolation.json)

## Full wiki excerpt

- SME owner: [`module.account`](../../../agents/modules/generated/account.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account)
- Direct dependencies: [`analytic`](../analytic/overview.md), [`base_setup`](../base_setup/overview.md), [`digest`](../digest/overview.md), [`onboarding`](../onboarding/overview.md), [`portal`](../portal/overview.md), [`product`](../product/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`account_add_gln`](../account_add_gln/overview.md), [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_debit_note`](../account_debit_note/overview.md), [`account_edi`](../account_edi/overview.md), [`account_edi_proxy_client`](../account_edi_proxy_client/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_fleet`](../account_fleet/overview.md), [`account_lock`](../account_lock/overview.md), [`account_payment`](../account_payment/overview.md), [`account_payment_term`](../account_payment_term/overview.md), [`account_qr_code_emv`](../account_qr_code_emv/overview.md), [`account_qr_code_sepa`](../account_qr_code_sepa/overview.md), [`account_tax_python`](../account_tax_python/overview.md), [`account_test`](../account_test/overview.md), [`account_update_tax_tags`](../account_update_tax_tags/overview.md), [`base_iban`](../base_iban/overview.md), [`base_vat`](../base_vat/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_ae`](../l10n_ae/overview.md), [`l10n_at`](../l10n_at/overview.md), [`l10n_au`](../l10n_au/overview.md), [`l10n_bd`](../l10n_bd/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_bg`](../l10n_bg/overview.md), [`l10n_bh`](../l10n_bh/overview.md), [`l10n_bo`](../l10n_bo/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_cn`](../l10n_cn/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_cr`](../l10n_cr/overview.md), [`l10n_cy`](../l10n_cy/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_do`](../l10n_do/overview.md), [`l10n_dz`](../l10n_dz/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_ee`](../l10n_ee/overview.md), [`l10n_eg`](../l10n_eg/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_et`](../l10n_et/overview.md), [`l10n_eu_oss`](../l10n_eu_oss/overview.md), [`l10n_fi`](../l10n_fi/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_facturx_chorus_pro`](../l10n_fr_facturx_chorus_pro/overview.md), [`l10n_fr_fec`](../l10n_fr_fec/overview.md), [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`l10n_gr`](../l10n_gr/overview.md), [`l10n_gt`](../l10n_gt/overview.md), [`l10n_hn`](../l10n_hn/overview.md), [`l10n_hr`](../l10n_hr/overview.md), [`l10n_hr_kuna`](../l10n_hr_kuna/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_id`](../l10n_id/overview.md), [`l10n_ie`](../l10n_ie/overview.md), [`l10n_il`](../l10n_il/overview.md), [`l10n_iq`](../l10n_iq/overview.md), [`l10n_it`](../l10n_it/overview.md), [`l10n_jo`](../l10n_jo/overview.md), [`l10n_jp`](../l10n_jp/overview.md), [`l10n_ke`](../l10n_ke/overview.md), [`l10n_kw`](../l10n_kw/overview.md), [`l10n_kz`](../l10n_kz/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_lb_account`](../l10n_lb_account/overview.md), [`l10n_lt`](../l10n_lt/overview.md), [`l10n_lu`](../l10n_lu/overview.md), [`l10n_lv`](../l10n_lv/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_mn`](../l10n_mn/overview.md), [`l10n_mr`](../l10n_mr/overview.md), [`l10n_mt`](../l10n_mt/overview.md), [`l10n_mu_account`](../l10n_mu_account/overview.md), [`l10n_mx`](../l10n_mx/overview.md), [`l10n_my`](../l10n_my/overview.md), [`l10n_mz`](../l10n_mz/overview.md), [`l10n_nl`](../l10n_nl/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_nz`](../l10n_nz/overview.md), [`l10n_pa`](../l10n_pa/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pk`](../l10n_pk/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_pt`](../l10n_pt/overview.md), [`l10n_qa`](../l10n_qa/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_rs`](../l10n_rs/overview.md), [`l10n_rw`](../l10n_rw/overview.md), [`l10n_sa`](../l10n_sa/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_si`](../l10n_si/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_syscohada`](../l10n_syscohada/overview.md), [`l10n_tn`](../l10n_tn/overview.md), [`l10n_tr`](../l10n_tr/overview.md), [`l10n_tw`](../l10n_tw/overview.md), [`l10n_tz_account`](../l10n_tz_account/overview.md), [`l10n_ua`](../l10n_ua/overview.md), [`l10n_ug`](../l10n_ug/overview.md), [`l10n_uk`](../l10n_uk/overview.md), [`l10n_us`](../l10n_us/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_ve`](../l10n_ve/overview.md), [`l10n_za`](../l10n_za/overview.md), [`l10n_zm_account`](../l10n_zm_account/overview.md), [`membership`](../membership/overview.md), [`product_email_template`](../product_email_template/overview.md), [`product_margin`](../product_margin/overview.md), [`product_matrix`](../product_matrix/overview.md), [`project_account`](../project_account/overview.md), [`purchase`](../purchase/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`spreadsheet_account`](../spreadsheet_account/overview.md), [`spreadsheet_dashboard_account`](../spreadsheet_dashboard_account/overview.md), [`stock_account`](../stock_account/overview.md), [`test_main_flows`](../test_main_flows/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md)
- Impact graph: [`module:account`](../../impact-graph.json)

## Purpose

Invoices & Payments

## Model relationships

- `account.account` — extended by [`l10n_de`](../l10n_de/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_mx`](../l10n_mx/overview.md), [`l10n_pt`](../l10n_pt/overview.md), [`spreadsheet_account`](../spreadsheet_account/overview.md)
- `account.account.tag`
- `account.accrued.orders.wizard`
- `account.automatic.entry.wizard` — extended by [`account_fleet`](../account_fleet/overview.md)
- `account.bank.statement`
- `account.bank.statement.line` — extended by [`account_audit_trail`](../account_audit_trail/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- `account.cash.rounding` — extended by [`point_of_sale`](../point_of_sale/overview.md)
- `account.financial.year.op`
- `account.fiscal.position` — extended by [`base_vat`](../base_vat/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- `account.fiscal.position.account`
- `account.fiscal.position.tax`
- `account.full.reconcile`
- `account.group`
- `account.incoterms`
- `account.invoice.report` — extended by [`l10n_ar`](../l10n_ar/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`sale`](../sale/overview.md)
- `account.journal` — extended by [`account_check_printing`](../account_check_printing/overview.md), [`account_debit_note_sequence`](../account_debit_note_sequence/overview.md), [`account_edi`](../account_edi/overview.md), [`account_payment`](../account_payment/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_selfbilling`](../account_peppol_selfbilling/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_at`](../l10n_at/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_fik`](../l10n_dk_fik/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_fi`](../l10n_fi/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_latam_check`](../l10n_latam_check/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_nl`](../l10n_nl/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- `account.journal.group`
- `account.move` — extended by [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_debit_note`](../account_debit_note/overview.md), [`account_debit_note_sequence`](../account_debit_note_sequence/overview.md), [`account_edi`](../account_edi/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_fleet`](../account_fleet/overview.md), [`account_payment`](../account_payment/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`account_peppol_selfbilling`](../account_peppol_selfbilling/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_au`](../l10n_au/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_cn`](../l10n_cn/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md), [`l10n_dk_bookkeeping`](../l10n_dk_bookkeeping/overview.md), [`l10n_dk_fik`](../l10n_dk_fik/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_facturae_invoice_period`](../l10n_es_edi_facturae_invoice_period/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_tbai_multi_refund`](../l10n_es_edi_tbai_multi_refund/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_fi`](../l10n_fi/overview.md), [`l10n_fr_facturx_chorus_pro`](../l10n_fr_facturx_chorus_pro/overview.md), [`l10n_fr_invoice_addr`](../l10n_fr_invoice_addr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_fr_pdp_pos`](../l10n_fr_pdp_pos/overview.md), [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id`](../l10n_id/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_ewaybill_port`](../l10n_in_ewaybill_port/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_in_purchase`](../l10n_in_purchase/overview.md), [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md), [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_it_edi_ndd`](../l10n_it_edi_ndd/overview.md), [`l10n_it_edi_ndd_account_dn`](../l10n_it_edi_ndd_account_dn/overview.md), [`l10n_it_edi_withholding`](../l10n_it_edi_withholding/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_mu_account`](../l10n_mu_account/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_nz`](../l10n_nz/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs`](../l10n_rs/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa`](../l10n_sa/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_sa_edi_pos`](../l10n_sa_edi_pos/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`l10n_zm_account`](../l10n_zm_account/overview.md), [`membership`](../membership/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`product_email_template`](../product_email_template/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`website_sale`](../website_sale/overview.md)
- `account.move.line` — extended by [`account_fleet`](../account_fleet/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_ae`](../l10n_ae/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`membership`](../membership/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`purchase`](../purchase/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_expense_margin`](../sale_expense_margin/overview.md), [`sale_mrp`](../sale_mrp/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md)
- `account.move.reversal` — extended by [`l10n_br`](../l10n_br/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md)
- `account.move.send` — extended by [`account_edi`](../account_edi/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_selfbilling`](../account_peppol_selfbilling/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`snailmail_account`](../snailmail_account/overview.md)
- `account.partial.reconcile`
- `account.payment` — extended by [`account_check_printing`](../account_check_printing/overview.md), [`account_payment`](../account_payment/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_latam_check`](../l10n_latam_check/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`website_payment`](../website_payment/overview.md)
- `account.payment.method` — extended by [`account_check_printing`](../account_check_printing/overview.md), [`account_payment`](../account_payment/overview.md), [`l10n_latam_check`](../l10n_latam_check/overview.md)
- `account.payment.method.line` — extended by [`account_payment`](../account_payment/overview.md), [`l10n_it_edi_ndd`](../l10n_it_edi_ndd/overview.md)
- `account.payment.register` — extended by [`account_check_printing`](../account_check_printing/overview.md), [`account_payment`](../account_payment/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_latam_check`](../l10n_latam_check/overview.md), [`sale`](../sale/overview.md)
- `account.payment.term`
- `account.payment.term.line` — extended by [`account_payment_term`](../account_payment_term/overview.md)
- `account.reconcile.model`
- `account.reconcile.model.line`
- `account.reconcile.model.partner.mapping`
- `account.report`
- `account.report.column`
- `account.report.expression` — extended by [`l10n_it`](../l10n_it/overview.md)
- `account.report.external.value`
- `account.report.line`
- `account.resequence.wizard` — extended by [`account_edi`](../account_edi/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md)
- `account.root`
- `account.setup.bank.manual.config` — extended by [`l10n_ch`](../l10n_ch/overview.md)
- `account.tax` — extended by [`account_edi_ubl_cii_tax_extension`](../account_edi_ubl_cii_tax_extension/overview.md), [`account_tax_python`](../account_tax_python/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_ee`](../l10n_ee/overview.md), [`l10n_eg`](../l10n_eg/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it`](../l10n_it/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_ke`](../l10n_ke/overview.md), [`l10n_mx`](../l10n_mx/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`purchase`](../purchase/overview.md)
- `account.tax.group` — extended by [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ec`](../l10n_ec/overview.md)
- `account.tax.repartition.line`
- `account.tour.upload.bill`
- `account.tour.upload.bill.email.confirm`
- `account.unreconcile`
- `report.account.report_hash_integrity`
- `report.account.report_invoice`
- `report.account.report_invoice_with_payments`
- `res.company` — extended by [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_proxy_client`](../account_edi_proxy_client/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_lock`](../account_lock/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`auth_ldap`](../auth_ldap/overview.md), [`barcodes`](../barcodes/overview.md), [`base`](../base/overview.md), [`base_vat`](../base_vat/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_presence`](../hr_presence/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_eu_oss`](../l10n_eu_oss/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_hr_holidays`](../l10n_fr_hr_holidays/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_fr_pdp_pos`](../l10n_fr_pdp_pos/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_ke`](../l10n_ke/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`lunch`](../lunch/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`onboarding`](../onboarding/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`product`](../product/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`resource`](../resource/overview.md), [`sale`](../sale/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sms`](../sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md), [`snailmail`](../snailmail/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`social_media`](../social_media/overview.md), [`spreadsheet_account`](../spreadsheet_account/overview.md), [`stock`](../stock/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`stock_sms`](../stock_sms/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md), [`website_mass_mailing`](../website_mass_mailing/overview.md), [`website_sale`](../website_sale/overview.md)
- `res.partner` — extended by [`account_add_gln`](../account_add_gln/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`auth_signup`](../auth_signup/overview.md), [`base`](../base/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_vat`](../base_vat/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event`](../event/overview.md), [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`loyalty`](../loyalty/overview.md), [`mail`](../mail/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`membership`](../membership/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`snailmail`](../snailmail/overview.md), [`stock`](../stock/overview.md), [`survey`](../survey/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_inherit`](../test_inherit/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md)
- `res.partner.bank` — extended by [`account_qr_code_emv`](../account_qr_code_emv/overview.md), [`account_qr_code_sepa`](../account_qr_code_sepa/overview.md), [`base_iban`](../base_iban/overview.md), [`hr`](../hr/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_au`](../l10n_au/overview.md), [`l10n_br_pix`](../l10n_br_pix/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_hk`](../l10n_hk/overview.md), [`l10n_mx`](../l10n_mx/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_us`](../l10n_us/overview.md), [`l10n_vn`](../l10n_vn/overview.md)
- `sequence.mixin`
- `validate.account.move`
- Extends `account.analytic.account` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.analytic.applicability` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.analytic.distribution.model` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.analytic.line` — defined by [`analytic`](../analytic/overview.md)
- Extends `account.bank.statement` — framework/dynamic owner
- Extends `account.bank.statement.line` — framework/dynamic owner
- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.journal` — framework/dynamic owner
- Extends `account.move` — defined by [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — framework/dynamic owner
- Extends `account.payment` — framework/dynamic owner
- Extends `account.reconcile.model` — framework/dynamic owner
- Extends `account.reconcile.model.line` — framework/dynamic owner
- Extends `analytic.mixin` — defined by [`analytic`](../analytic/overview.md)
- Extends `base.document.layout` — defined by [`web`](../web/overview.md)
- Extends `base.partner.merge.automatic.wizard` — defined by [`base`](../base/overview.md)
- Extends `decimal.precision` — defined by [`base`](../base/overview.md)
- Extends `digest.digest` — defined by [`digest`](../digest/overview.md)
- Extends `ir.actions.report` — defined by [`base`](../base/overview.md)
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `ir.module.module` — defined by [`base`](../base/overview.md), [`website`](../website/overview.md)
- Extends `kpi.provider` — defined by [`base_setup`](../base_setup/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.alias.mixin.optional` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.main.attachment` — defined by [`mail`](../mail/overview.md)
- Extends `onboarding.onboarding` — defined by [`onboarding`](../onboarding/overview.md)
- Extends `onboarding.onboarding.step` — defined by [`onboarding`](../onboarding/overview.md)
- Extends `portal.mixin` — defined by [`portal`](../portal/overview.md)
- Extends `product.category` — defined by [`product`](../product/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `report.account.report_invoice` — framework/dynamic owner
- Extends `res.company` — defined by [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.currency` — defined by [`base`](../base/overview.md), [`l10n_cl`](../l10n_cl/overview.md)
- Extends `res.groups` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.partner.bank` — defined by [`base`](../base/overview.md)
- Extends `sequence.mixin` — framework/dynamic owner
- Extends `uom.uom` — defined by [`uom`](../uom/overview.md)

## Related SME agents

- [`module.account_add_gln`](../../../agents/modules/generated/account_add_gln.yaml) — model_extended_by, required_by
- [`module.account_audit_trail`](../../../agents/modules/generated/account_audit_trail.yaml) — model_extended_by, required_by
- [`module.account_check_printing`](../../../agents/modules/generated/account_check_printing.yaml) — model_extended_by, required_by
- [`module.account_debit_note`](../../../agents/modules/generated/account_debit_note.yaml) — model_extended_by, required_by
- [`module.account_debit_note_sequence`](../../../agents/modules/generated/account_debit_note_sequence.yaml) — model_extended_by
- [`module.account_edi`](../../../agents/modules/generated/account_edi.yaml) — model_extended_by, required_by
- [`module.account_edi_proxy_client`](../../../agents/modules/generated/account_edi_proxy_client.yaml) — model_extended_by, required_by
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — model_extended_by, required_by
- [`module.account_edi_ubl_cii_tax_extension`](../../../agents/modules/generated/account_edi_ubl_cii_tax_extension.yaml) — model_extended_by
- [`module.account_fleet`](../../../agents/modules/generated/account_fleet.yaml) — model_extended_by, required_by
- [`module.account_lock`](../../../agents/modules/generated/account_lock.yaml) — model_extended_by, required_by
- [`module.account_payment`](../../../agents/modules/generated/account_payment.yaml) — model_extended_by, required_by
- [`module.account_payment_term`](../../../agents/modules/generated/account_payment_term.yaml) — model_extended_by, required_by
- [`module.account_peppol`](../../../agents/modules/generated/account_peppol.yaml) — model_extended_by
- [`module.account_peppol_response`](../../../agents/modules/generated/account_peppol_response.yaml) — model_extended_by
- [`module.account_peppol_selfbilling`](../../../agents/modules/generated/account_peppol_selfbilling.yaml) — model_extended_by
- [`module.account_qr_code_emv`](../../../agents/modules/generated/account_qr_code_emv.yaml) — model_extended_by, required_by
- [`module.account_qr_code_sepa`](../../../agents/modules/generated/account_qr_code_sepa.yaml) — model_extended_by, required_by
- [`module.account_tax_python`](../../../agents/modules/generated/account_tax_python.yaml) — model_extended_by, required_by
- [`module.account_test`](../../../agents/modules/generated/account_test.yaml) — required_by
- [`module.account_update_tax_tags`](../../../agents/modules/generated/account_update_tax_tags.yaml) — required_by
- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — depends_on, extends_model_from
- [`module.auth_ldap`](../../../agents/modules/generated/auth_ldap.yaml) — model_extended_by
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — model_extended_by
- [`module.barcodes`](../../../agents/modules/generated/barcodes.yaml) — model_extended_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from, model_extended_by
- [`module.base_address_extended`](../../../agents/modules/generated/base_address_extended.yaml) — model_extended_by
- [`module.base_geolocalize`](../../../agents/modules/generated/base_geolocalize.yaml) — model_extended_by
- [`module.base_iban`](../../../agents/modules/generated/base_iban.yaml) — model_extended_by, required_by
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on, extends_model_from
- [`module.base_vat`](../../../agents/modules/generated/base_vat.yaml) — model_extended_by, required_by
- [`module.bus`](../../../agents/modules/generated/bus.yaml) — model_extended_by
- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — model_extended_by
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from, model_extended_by
- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — model_extended_by
- [`module.delivery_mondialrelay`](../../../agents/modules/generated/delivery_mondialrelay.yaml) — model_extended_by
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — depends_on, extends_model_from
- [`module.event`](../../../agents/modules/generated/event.yaml) — model_extended_by
- [`module.event_booth_sale`](../../../agents/modules/generated/event_booth_sale.yaml) — model_extended_by
- [`module.fleet`](../../../agents/modules/generated/fleet.yaml) — model_extended_by
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — model_extended_by
- [`module.hr_attendance`](../../../agents/modules/generated/hr_attendance.yaml) — model_extended_by
- [`module.hr_contract`](../../../agents/modules/generated/hr_contract.yaml) — model_extended_by
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — model_extended_by, required_by
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — model_extended_by
- [`module.hr_holidays_attendance`](../../../agents/modules/generated/hr_holidays_attendance.yaml) — model_extended_by
- [`module.hr_homeworking`](../../../agents/modules/generated/hr_homeworking.yaml) — model_extended_by
- [`module.hr_presence`](../../../agents/modules/generated/hr_presence.yaml) — model_extended_by
- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — model_extended_by
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — model_extended_by
- [`module.l10n_ae`](../../../agents/modules/generated/l10n_ae.yaml) — model_extended_by, required_by
- [`module.l10n_anz_ubl_pint`](../../../agents/modules/generated/l10n_anz_ubl_pint.yaml) — model_extended_by
- [`module.l10n_ar`](../../../agents/modules/generated/l10n_ar.yaml) — model_extended_by
- [`module.l10n_ar_pos`](../../../agents/modules/generated/l10n_ar_pos.yaml) — model_extended_by
- [`module.l10n_ar_withholding`](../../../agents/modules/generated/l10n_ar_withholding.yaml) — model_extended_by
- [`module.l10n_at`](../../../agents/modules/generated/l10n_at.yaml) — model_extended_by, required_by
- [`module.l10n_au`](../../../agents/modules/generated/l10n_au.yaml) — model_extended_by, required_by
- [`module.l10n_bd`](../../../agents/modules/generated/l10n_bd.yaml) — required_by
- [`module.l10n_be`](../../../agents/modules/generated/l10n_be.yaml) — model_extended_by, required_by
- [`module.l10n_bg`](../../../agents/modules/generated/l10n_bg.yaml) — required_by
- [`module.l10n_bh`](../../../agents/modules/generated/l10n_bh.yaml) — required_by
- [`module.l10n_bo`](../../../agents/modules/generated/l10n_bo.yaml) — required_by
- [`module.l10n_br`](../../../agents/modules/generated/l10n_br.yaml) — model_extended_by, required_by
- [`module.l10n_br_pix`](../../../agents/modules/generated/l10n_br_pix.yaml) — model_extended_by
- [`module.l10n_ca`](../../../agents/modules/generated/l10n_ca.yaml) — model_extended_by, required_by
- [`module.l10n_ch`](../../../agents/modules/generated/l10n_ch.yaml) — model_extended_by, required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from, model_extended_by, required_by
- [`module.l10n_cn`](../../../agents/modules/generated/l10n_cn.yaml) — model_extended_by, required_by
- [`module.l10n_co`](../../../agents/modules/generated/l10n_co.yaml) — model_extended_by, required_by
- [`module.l10n_cr`](../../../agents/modules/generated/l10n_cr.yaml) — required_by
- [`module.l10n_cy`](../../../agents/modules/generated/l10n_cy.yaml) — required_by
- [`module.l10n_cz`](../../../agents/modules/generated/l10n_cz.yaml) — model_extended_by, required_by
- [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml) — model_extended_by
- [`module.l10n_din5008`](../../../agents/modules/generated/l10n_din5008.yaml) — model_extended_by, required_by
- [`module.l10n_dk`](../../../agents/modules/generated/l10n_dk.yaml) — model_extended_by, required_by
- [`module.l10n_dk_bookkeeping`](../../../agents/modules/generated/l10n_dk_bookkeeping.yaml) — model_extended_by
- [`module.l10n_dk_fik`](../../../agents/modules/generated/l10n_dk_fik.yaml) — model_extended_by
- [`module.l10n_dk_oioubl`](../../../agents/modules/generated/l10n_dk_oioubl.yaml) — model_extended_by
- [`module.l10n_do`](../../../agents/modules/generated/l10n_do.yaml) — required_by
- [`module.l10n_dz`](../../../agents/modules/generated/l10n_dz.yaml) — required_by
- [`module.l10n_ec`](../../../agents/modules/generated/l10n_ec.yaml) — model_extended_by, required_by
- [`module.l10n_ee`](../../../agents/modules/generated/l10n_ee.yaml) — model_extended_by, required_by
- [`module.l10n_eg`](../../../agents/modules/generated/l10n_eg.yaml) — model_extended_by, required_by
- [`module.l10n_eg_edi_eta`](../../../agents/modules/generated/l10n_eg_edi_eta.yaml) — model_extended_by
- [`module.l10n_es`](../../../agents/modules/generated/l10n_es.yaml) — model_extended_by, required_by
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
- [`module.l10n_et`](../../../agents/modules/generated/l10n_et.yaml) — required_by
- [`module.l10n_eu_oss`](../../../agents/modules/generated/l10n_eu_oss.yaml) — model_extended_by, required_by
- [`module.l10n_fi`](../../../agents/modules/generated/l10n_fi.yaml) — model_extended_by, required_by
- [`module.l10n_fr`](../../../agents/modules/generated/l10n_fr.yaml) — model_extended_by, required_by
- [`module.l10n_fr_facturx_chorus_pro`](../../../agents/modules/generated/l10n_fr_facturx_chorus_pro.yaml) — model_extended_by, required_by
- [`module.l10n_fr_fec`](../../../agents/modules/generated/l10n_fr_fec.yaml) — required_by
- [`module.l10n_fr_hr_holidays`](../../../agents/modules/generated/l10n_fr_hr_holidays.yaml) — model_extended_by
- [`module.l10n_fr_invoice_addr`](../../../agents/modules/generated/l10n_fr_invoice_addr.yaml) — model_extended_by
- [`module.l10n_fr_pdp`](../../../agents/modules/generated/l10n_fr_pdp.yaml) — model_extended_by
- [`module.l10n_fr_pdp_pos`](../../../agents/modules/generated/l10n_fr_pdp_pos.yaml) — model_extended_by
- [`module.l10n_fr_pos_cert`](../../../agents/modules/generated/l10n_fr_pos_cert.yaml) — model_extended_by
- [`module.l10n_gcc_invoice`](../../../agents/modules/generated/l10n_gcc_invoice.yaml) — model_extended_by, required_by
- [`module.l10n_gr`](../../../agents/modules/generated/l10n_gr.yaml) — required_by
- [`module.l10n_gt`](../../../agents/modules/generated/l10n_gt.yaml) — required_by
- [`module.l10n_hk`](../../../agents/modules/generated/l10n_hk.yaml) — model_extended_by
- [`module.l10n_hn`](../../../agents/modules/generated/l10n_hn.yaml) — required_by
- [`module.l10n_hr`](../../../agents/modules/generated/l10n_hr.yaml) — required_by
- [`module.l10n_hr_kuna`](../../../agents/modules/generated/l10n_hr_kuna.yaml) — required_by
- [`module.l10n_hu`](../../../agents/modules/generated/l10n_hu.yaml) — model_extended_by, required_by
- [`module.l10n_hu_edi`](../../../agents/modules/generated/l10n_hu_edi.yaml) — model_extended_by
- [`module.l10n_id`](../../../agents/modules/generated/l10n_id.yaml) — model_extended_by, required_by
- [`module.l10n_id_efaktur`](../../../agents/modules/generated/l10n_id_efaktur.yaml) — model_extended_by
- [`module.l10n_id_efaktur_coretax`](../../../agents/modules/generated/l10n_id_efaktur_coretax.yaml) — model_extended_by
- [`module.l10n_ie`](../../../agents/modules/generated/l10n_ie.yaml) — required_by
- [`module.l10n_il`](../../../agents/modules/generated/l10n_il.yaml) — required_by
- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — model_extended_by
- [`module.l10n_in_edi`](../../../agents/modules/generated/l10n_in_edi.yaml) — model_extended_by
- [`module.l10n_in_edi_ewaybill`](../../../agents/modules/generated/l10n_in_edi_ewaybill.yaml) — model_extended_by
- [`module.l10n_in_ewaybill_port`](../../../agents/modules/generated/l10n_in_ewaybill_port.yaml) — model_extended_by
- [`module.l10n_in_pos`](../../../agents/modules/generated/l10n_in_pos.yaml) — model_extended_by
- [`module.l10n_in_purchase`](../../../agents/modules/generated/l10n_in_purchase.yaml) — model_extended_by
- [`module.l10n_in_purchase_stock`](../../../agents/modules/generated/l10n_in_purchase_stock.yaml) — model_extended_by
- [`module.l10n_in_sale_stock`](../../../agents/modules/generated/l10n_in_sale_stock.yaml) — model_extended_by
- [`module.l10n_in_withholding`](../../../agents/modules/generated/l10n_in_withholding.yaml) — model_extended_by
- [`module.l10n_iq`](../../../agents/modules/generated/l10n_iq.yaml) — required_by
- [`module.l10n_it`](../../../agents/modules/generated/l10n_it.yaml) — model_extended_by, required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from, model_extended_by
- [`module.l10n_it_edi_doi`](../../../agents/modules/generated/l10n_it_edi_doi.yaml) — model_extended_by
- [`module.l10n_it_edi_ndd`](../../../agents/modules/generated/l10n_it_edi_ndd.yaml) — model_extended_by
- [`module.l10n_it_edi_ndd_account_dn`](../../../agents/modules/generated/l10n_it_edi_ndd_account_dn.yaml) — model_extended_by
- [`module.l10n_it_edi_withholding`](../../../agents/modules/generated/l10n_it_edi_withholding.yaml) — model_extended_by
- [`module.l10n_it_stock_ddt`](../../../agents/modules/generated/l10n_it_stock_ddt.yaml) — model_extended_by
- [`module.l10n_jo`](../../../agents/modules/generated/l10n_jo.yaml) — required_by
- [`module.l10n_jo_edi`](../../../agents/modules/generated/l10n_jo_edi.yaml) — model_extended_by
- [`module.l10n_jo_edi_extended`](../../../agents/modules/generated/l10n_jo_edi_extended.yaml) — model_extended_by
- [`module.l10n_jp`](../../../agents/modules/generated/l10n_jp.yaml) — required_by
- [`module.l10n_jp_ubl_pint`](../../../agents/modules/generated/l10n_jp_ubl_pint.yaml) — model_extended_by
- [`module.l10n_ke`](../../../agents/modules/generated/l10n_ke.yaml) — model_extended_by, required_by
- [`module.l10n_ke_edi_tremol`](../../../agents/modules/generated/l10n_ke_edi_tremol.yaml) — model_extended_by
- [`module.l10n_kw`](../../../agents/modules/generated/l10n_kw.yaml) — required_by
- [`module.l10n_kz`](../../../agents/modules/generated/l10n_kz.yaml) — required_by
- [`module.l10n_latam_base`](../../../agents/modules/generated/l10n_latam_base.yaml) — model_extended_by
- [`module.l10n_latam_check`](../../../agents/modules/generated/l10n_latam_check.yaml) — model_extended_by
- [`module.l10n_latam_invoice_document`](../../../agents/modules/generated/l10n_latam_invoice_document.yaml) — model_extended_by, required_by
- [`module.l10n_lb_account`](../../../agents/modules/generated/l10n_lb_account.yaml) — required_by
- [`module.l10n_lt`](../../../agents/modules/generated/l10n_lt.yaml) — required_by
- [`module.l10n_lu`](../../../agents/modules/generated/l10n_lu.yaml) — required_by
- [`module.l10n_lv`](../../../agents/modules/generated/l10n_lv.yaml) — required_by
- [`module.l10n_ma`](../../../agents/modules/generated/l10n_ma.yaml) — model_extended_by, required_by
- [`module.l10n_mn`](../../../agents/modules/generated/l10n_mn.yaml) — required_by
- [`module.l10n_mr`](../../../agents/modules/generated/l10n_mr.yaml) — required_by
- [`module.l10n_mt`](../../../agents/modules/generated/l10n_mt.yaml) — required_by
- [`module.l10n_mu_account`](../../../agents/modules/generated/l10n_mu_account.yaml) — model_extended_by, required_by
- [`module.l10n_mx`](../../../agents/modules/generated/l10n_mx.yaml) — model_extended_by, required_by
- [`module.l10n_my`](../../../agents/modules/generated/l10n_my.yaml) — required_by
- [`module.l10n_my_edi`](../../../agents/modules/generated/l10n_my_edi.yaml) — model_extended_by
- [`module.l10n_my_edi_extended`](../../../agents/modules/generated/l10n_my_edi_extended.yaml) — model_extended_by
- [`module.l10n_my_ubl_pint`](../../../agents/modules/generated/l10n_my_ubl_pint.yaml) — model_extended_by
- [`module.l10n_mz`](../../../agents/modules/generated/l10n_mz.yaml) — required_by
- [`module.l10n_nl`](../../../agents/modules/generated/l10n_nl.yaml) — model_extended_by, required_by
- [`module.l10n_no`](../../../agents/modules/generated/l10n_no.yaml) — model_extended_by, required_by
- [`module.l10n_nz`](../../../agents/modules/generated/l10n_nz.yaml) — model_extended_by, required_by
- [`module.l10n_pa`](../../../agents/modules/generated/l10n_pa.yaml) — required_by
- [`module.l10n_pe`](../../../agents/modules/generated/l10n_pe.yaml) — model_extended_by, required_by
- [`module.l10n_pe_pos`](../../../agents/modules/generated/l10n_pe_pos.yaml) — model_extended_by
- [`module.l10n_ph`](../../../agents/modules/generated/l10n_ph.yaml) — model_extended_by, required_by
- [`module.l10n_pk`](../../../agents/modules/generated/l10n_pk.yaml) — required_by
- [`module.l10n_pl`](../../../agents/modules/generated/l10n_pl.yaml) — model_extended_by, required_by
- [`module.l10n_pt`](../../../agents/modules/generated/l10n_pt.yaml) — model_extended_by, required_by
- [`module.l10n_qa`](../../../agents/modules/generated/l10n_qa.yaml) — required_by
- [`module.l10n_ro`](../../../agents/modules/generated/l10n_ro.yaml) — model_extended_by, required_by
- [`module.l10n_ro_edi`](../../../agents/modules/generated/l10n_ro_edi.yaml) — model_extended_by
- [`module.l10n_ro_efactura`](../../../agents/modules/generated/l10n_ro_efactura.yaml) — model_extended_by
- [`module.l10n_ro_efactura_synchronize`](../../../agents/modules/generated/l10n_ro_efactura_synchronize.yaml) — model_extended_by
- [`module.l10n_rs`](../../../agents/modules/generated/l10n_rs.yaml) — model_extended_by, required_by
- [`module.l10n_rs_edi`](../../../agents/modules/generated/l10n_rs_edi.yaml) — model_extended_by
- [`module.l10n_rw`](../../../agents/modules/generated/l10n_rw.yaml) — required_by
- [`module.l10n_sa`](../../../agents/modules/generated/l10n_sa.yaml) — model_extended_by, required_by
- [`module.l10n_sa_edi`](../../../agents/modules/generated/l10n_sa_edi.yaml) — model_extended_by
- [`module.l10n_sa_edi_pos`](../../../agents/modules/generated/l10n_sa_edi_pos.yaml) — model_extended_by
- [`module.l10n_se`](../../../agents/modules/generated/l10n_se.yaml) — model_extended_by, required_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from, model_extended_by
- [`module.l10n_sg_ubl_pint`](../../../agents/modules/generated/l10n_sg_ubl_pint.yaml) — model_extended_by
- [`module.l10n_si`](../../../agents/modules/generated/l10n_si.yaml) — required_by
- [`module.l10n_sk`](../../../agents/modules/generated/l10n_sk.yaml) — model_extended_by, required_by
- [`module.l10n_syscohada`](../../../agents/modules/generated/l10n_syscohada.yaml) — required_by
- [`module.l10n_th`](../../../agents/modules/generated/l10n_th.yaml) — model_extended_by
- [`module.l10n_tn`](../../../agents/modules/generated/l10n_tn.yaml) — required_by
- [`module.l10n_tr`](../../../agents/modules/generated/l10n_tr.yaml) — required_by
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from, model_extended_by
- [`module.l10n_tr_nilvera_edispatch`](../../../agents/modules/generated/l10n_tr_nilvera_edispatch.yaml) — model_extended_by
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from, model_extended_by
- [`module.l10n_tw`](../../../agents/modules/generated/l10n_tw.yaml) — required_by
- [`module.l10n_tz_account`](../../../agents/modules/generated/l10n_tz_account.yaml) — required_by
- [`module.l10n_ua`](../../../agents/modules/generated/l10n_ua.yaml) — required_by
- [`module.l10n_ug`](../../../agents/modules/generated/l10n_ug.yaml) — required_by
- [`module.l10n_uk`](../../../agents/modules/generated/l10n_uk.yaml) — required_by
- [`module.l10n_us`](../../../agents/modules/generated/l10n_us.yaml) — model_extended_by, required_by
- [`module.l10n_uy`](../../../agents/modules/generated/l10n_uy.yaml) — model_extended_by, required_by
- [`module.l10n_ve`](../../../agents/modules/generated/l10n_ve.yaml) — required_by
- [`module.l10n_vn`](../../../agents/modules/generated/l10n_vn.yaml) — model_extended_by
- [`module.l10n_vn_edi_viettel`](../../../agents/modules/generated/l10n_vn_edi_viettel.yaml) — model_extended_by
- [`module.l10n_za`](../../../agents/modules/generated/l10n_za.yaml) — required_by
- [`module.l10n_zm_account`](../../../agents/modules/generated/l10n_zm_account.yaml) — model_extended_by, required_by
- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — model_extended_by
- [`module.lunch`](../../../agents/modules/generated/lunch.yaml) — model_extended_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from, model_extended_by
- [`module.mail_plugin`](../../../agents/modules/generated/mail_plugin.yaml) — model_extended_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — model_extended_by
- [`module.membership`](../../../agents/modules/generated/membership.yaml) — model_extended_by, required_by
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — model_extended_by
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from, model_extended_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — model_extended_by
- [`module.mrp_subcontracting_dropshipping`](../../../agents/modules/generated/mrp_subcontracting_dropshipping.yaml) — model_extended_by
- [`module.mrp_subcontracting_purchase`](../../../agents/modules/generated/mrp_subcontracting_purchase.yaml) — model_extended_by
- [`module.onboarding`](../../../agents/modules/generated/onboarding.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from, model_extended_by
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — model_extended_by
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from, model_extended_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.pos_online_payment`](../../../agents/modules/generated/pos_online_payment.yaml) — model_extended_by
- [`module.privacy_lookup`](../../../agents/modules/generated/privacy_lookup.yaml) — model_extended_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.product_email_template`](../../../agents/modules/generated/product_email_template.yaml) — model_extended_by, required_by
- [`module.product_margin`](../../../agents/modules/generated/product_margin.yaml) — required_by
- [`module.product_matrix`](../../../agents/modules/generated/product_matrix.yaml) — required_by
- [`module.project`](../../../agents/modules/generated/project.yaml) — model_extended_by
- [`module.project_account`](../../../agents/modules/generated/project_account.yaml) — required_by
- [`module.project_timesheet_holidays`](../../../agents/modules/generated/project_timesheet_holidays.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from, model_extended_by, required_by
- [`module.purchase_mrp`](../../../agents/modules/generated/purchase_mrp.yaml) — model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from, model_extended_by
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from, model_extended_by
- [`module.sale_expense`](../../../agents/modules/generated/sale_expense.yaml) — model_extended_by
- [`module.sale_expense_margin`](../../../agents/modules/generated/sale_expense_margin.yaml) — model_extended_by
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — model_extended_by
- [`module.sale_mrp`](../../../agents/modules/generated/sale_mrp.yaml) — model_extended_by
- [`module.sale_pdf_quote_builder`](../../../agents/modules/generated/sale_pdf_quote_builder.yaml) — model_extended_by
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — model_extended_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — model_extended_by
- [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml) — model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from, model_extended_by
- [`module.sms_twilio`](../../../agents/modules/generated/sms_twilio.yaml) — model_extended_by
- [`module.snailmail`](../../../agents/modules/generated/snailmail.yaml) — model_extended_by
- [`module.snailmail_account`](../../../agents/modules/generated/snailmail_account.yaml) — model_extended_by, required_by
- [`module.social_media`](../../../agents/modules/generated/social_media.yaml) — model_extended_by
- [`module.spreadsheet_account`](../../../agents/modules/generated/spreadsheet_account.yaml) — model_extended_by, required_by
- [`module.spreadsheet_dashboard_account`](../../../agents/modules/generated/spreadsheet_dashboard_account.yaml) — required_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — model_extended_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from, model_extended_by, required_by
- [`module.stock_dropshipping`](../../../agents/modules/generated/stock_dropshipping.yaml) — model_extended_by
- [`module.stock_landed_costs`](../../../agents/modules/generated/stock_landed_costs.yaml) — model_extended_by
- [`module.stock_sms`](../../../agents/modules/generated/stock_sms.yaml) — model_extended_by
- [`module.survey`](../../../agents/modules/generated/survey.yaml) — model_extended_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from, model_extended_by
- [`module.test_inherit`](../../../agents/modules/generated/test_inherit.yaml) — model_extended_by
- [`module.test_main_flows`](../../../agents/modules/generated/test_main_flows.yaml) — required_by
- [`module.uom`](../../../agents/modules/generated/uom.yaml) — extends_model_from
- [`module.web`](../../../agents/modules/generated/web.yaml) — extends_model_from, model_extended_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from, model_extended_by
- [`module.website_crm_partner_assign`](../../../agents/modules/generated/website_crm_partner_assign.yaml) — model_extended_by, required_by
- [`module.website_customer`](../../../agents/modules/generated/website_customer.yaml) — model_extended_by
- [`module.website_mass_mailing`](../../../agents/modules/generated/website_mass_mailing.yaml) — model_extended_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from, model_extended_by
- [`module.website_payment`](../../../agents/modules/generated/website_payment.yaml) — model_extended_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from, model_extended_by
- [`module.website_sale_mondialrelay`](../../../agents/modules/generated/website_sale_mondialrelay.yaml) — model_extended_by
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — model_extended_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — model_extended_by

## Regression impact checklist

- Review 122 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account_add_gln`](../account_add_gln/overview.md), [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_debit_note`](../account_debit_note/overview.md), [`account_debit_note_sequence`](../account_debit_note_sequence/overview.md), [`account_edi`](../account_edi/overview.md), [`account_edi_proxy_client`](../account_edi_proxy_client/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_edi_ubl_cii_tax_extension`](../account_edi_ubl_cii_tax_extension/overview.md), [`account_fleet`](../account_fleet/overview.md), [`account_lock`](../account_lock/overview.md), [`account_payment`](../account_payment/overview.md), [`account_payment_term`](../account_payment_term/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`account_peppol_selfbilling`](../account_peppol_selfbilling/overview.md), [`account_qr_code_emv`](../account_qr_code_emv/overview.md), [`account_qr_code_sepa`](../account_qr_code_sepa/overview.md), [`account_tax_python`](../account_tax_python/overview.md), [`auth_ldap`](../auth_ldap/overview.md), [`auth_signup`](../auth_signup/overview.md), [`barcodes`](../barcodes/overview.md), [`base`](../base/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_iban`](../base_iban/overview.md), [`base_vat`](../base_vat/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event`](../event/overview.md), [`event_booth_sale`](../event_booth_sale/overview.md), [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_presence`](../hr_presence/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_ae`](../l10n_ae/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_at`](../l10n_at/overview.md), [`l10n_au`](../l10n_au/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_br_pix`](../l10n_br_pix/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_cn`](../l10n_cn/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_bookkeeping`](../l10n_dk_bookkeeping/overview.md), [`l10n_dk_fik`](../l10n_dk_fik/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_ee`](../l10n_ee/overview.md), [`l10n_eg`](../l10n_eg/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_facturae_invoice_period`](../l10n_es_edi_facturae_invoice_period/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_tbai_multi_refund`](../l10n_es_edi_tbai_multi_refund/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_eu_oss`](../l10n_eu_oss/overview.md), [`l10n_fi`](../l10n_fi/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_facturx_chorus_pro`](../l10n_fr_facturx_chorus_pro/overview.md), [`l10n_fr_hr_holidays`](../l10n_fr_hr_holidays/overview.md), [`l10n_fr_invoice_addr`](../l10n_fr_invoice_addr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_fr_pdp_pos`](../l10n_fr_pdp_pos/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`l10n_hk`](../l10n_hk/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id`](../l10n_id/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_ewaybill_port`](../l10n_in_ewaybill_port/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_in_purchase`](../l10n_in_purchase/overview.md), [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md), [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it`](../l10n_it/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_it_edi_ndd`](../l10n_it_edi_ndd/overview.md), [`l10n_it_edi_ndd_account_dn`](../l10n_it_edi_ndd_account_dn/overview.md), [`l10n_it_edi_withholding`](../l10n_it_edi_withholding/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_ke`](../l10n_ke/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_latam_check`](../l10n_latam_check/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_mu_account`](../l10n_mu_account/overview.md), [`l10n_mx`](../l10n_mx/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_nl`](../l10n_nl/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_nz`](../l10n_nz/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_pt`](../l10n_pt/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs`](../l10n_rs/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa`](../l10n_sa/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_sa_edi_pos`](../l10n_sa_edi_pos/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`l10n_us`](../l10n_us/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn`](../l10n_vn/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`l10n_zm_account`](../l10n_zm_account/overview.md), [`loyalty`](../loyalty/overview.md), [`lunch`](../lunch/overview.md), [`mail`](../mail/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`membership`](../membership/overview.md), [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`onboarding`](../onboarding/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`product_email_template`](../product_email_template/overview.md), [`project`](../project/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`purchase`](../purchase/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`resource`](../resource/overview.md), [`sale`](../sale/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_expense_margin`](../sale_expense_margin/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_mrp`](../sale_mrp/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md), [`snailmail`](../snailmail/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`social_media`](../social_media/overview.md), [`spreadsheet_account`](../spreadsheet_account/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`stock_sms`](../stock_sms/overview.md), [`survey`](../survey/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_inherit`](../test_inherit/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_mass_mailing`](../website_mass_mailing/overview.md), [`website_partner`](../website_partner/overview.md), [`website_payment`](../website_payment/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md).
- Review model owners used by this module: [`analytic`](../analytic/overview.md), [`base`](../base/overview.md), [`base_setup`](../base_setup/overview.md), [`crm`](../crm/overview.md), [`digest`](../digest/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`mrp_account`](../mrp_account/overview.md), [`onboarding`](../onboarding/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`portal`](../portal/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sms`](../sms/overview.md), [`stock_account`](../stock_account/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`uom`](../uom/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-12-cmr-endpoint-bootstrap-enterprise-gate`](../../conversations/2026-08-12-cmr-endpoint-bootstrap-enterprise-gate.json)
- [`2026-08-12-cmr-ho-store-isolation`](../../conversations/2026-08-12-cmr-ho-store-isolation.json)
