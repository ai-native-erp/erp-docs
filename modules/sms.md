---
layout: page
title: "SMS gateway (sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sms/
nav_order: 0
---
# SMS gateway — `sms`

**Source:** [`agents/modules/generated/sms.yaml`](../../agents/modules/generated/sms.yaml) · **Wiki:** [`knowledge/modules/sms/overview.md`](../../knowledge/modules/sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">SMS gateway</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">integrations</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

SMS Text Messaging

## Direct dependencies

[`base`](base.md), [`iap_mail`](iap_mail.md), [`mail`](mail.md), [`phone_validation`](phone_validation.md)

## Reverse dependencies (modules that depend on this)

[`base_automation`](base_automation.md), [`calendar_sms`](calendar_sms.md), [`crm_sms`](crm_sms.md), [`event_sms`](event_sms.md), [`hr_presence`](hr_presence.md), [`hr_recruitment_sms`](hr_recruitment_sms.md), [`mass_mailing_event_sms`](mass_mailing_event_sms.md), [`mass_mailing_event_track_sms`](mass_mailing_event_track_sms.md), [`mass_mailing_sms`](mass_mailing_sms.md), [`project_sms`](project_sms.md), [`sale_sms`](sale_sms.md), [`sms_twilio`](sms_twilio.md), [`stock_sms`](stock_sms.md), [`test_mail_full`](test_mail_full.md), [`test_mail_sms`](test_mail_sms.md), [`website_sms`](website_sms.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.actions.server</code></div><div class="role">defined by <code>sms</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">defined by <code>sms</code></div></div>
<div class="model"><div class="name"><code>sms.composer</code></div><div class="role">defined by <code>sms</code></div></div>
<div class="model"><div class="name"><code>sms.resend</code></div><div class="role">defined by <code>sms</code></div></div>
<div class="model"><div class="name"><code>sms.resend.recipient</code></div><div class="role">defined by <code>sms</code></div></div>
<div class="model"><div class="name"><code>sms.sms</code></div><div class="role">defined by <code>sms</code></div></div>
<div class="model"><div class="name"><code>sms.template</code></div><div class="role">defined by <code>sms</code></div></div>
<div class="model"><div class="name"><code>sms.template.preview</code></div><div class="role">defined by <code>sms</code></div></div>
<div class="model"><div class="name"><code>sms.template.reset</code></div><div class="role">defined by <code>sms</code></div></div>
<div class="model"><div class="name"><code>sms.tracker</code></div><div class="role">defined by <code>sms</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>base</code></div><div class="role">extended by <code>sms</code></div></div>
<div class="model"><div class="name"><code>ir.actions.server</code></div><div class="role">extended by <code>sms</code></div></div>
<div class="model"><div class="name"><code>ir.model</code></div><div class="role">extended by <code>sms</code></div></div>
<div class="model"><div class="name"><code>mail.followers</code></div><div class="role">extended by <code>sms</code></div></div>
<div class="model"><div class="name"><code>mail.message</code></div><div class="role">extended by <code>sms</code></div></div>
<div class="model"><div class="name"><code>mail.notification</code></div><div class="role">extended by <code>sms</code></div></div>
<div class="model"><div class="name"><code>mail.render.mixin</code></div><div class="role">extended by <code>sms</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>sms</code></div></div>
<div class="model"><div class="name"><code>mail.thread.phone</code></div><div class="role">extended by <code>sms</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>sms</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>sms</code></div></div>
<div class="model"><div class="name"><code>template.reset.mixin</code></div><div class="role">extended by <code>sms</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from, model_extended_by | `agents/modules/generated/account.yaml` |
| `module.account_add_gln` | model_extended_by | `agents/modules/generated/account_add_gln.yaml` |
| `module.account_check_printing` | model_extended_by | `agents/modules/generated/account_check_printing.yaml` |
| `module.account_edi_ubl_cii` | model_extended_by | `agents/modules/generated/account_edi_ubl_cii.yaml` |
| `module.account_peppol` | model_extended_by | `agents/modules/generated/account_peppol.yaml` |
| `module.account_peppol_response` | model_extended_by | `agents/modules/generated/account_peppol_response.yaml` |
| `module.auth_signup` | model_extended_by | `agents/modules/generated/auth_signup.yaml` |
| `module.base` | depends_on, extends_model_from, model_extended_by | `agents/modules/generated/base.yaml` |
| `module.base_address_extended` | model_extended_by | `agents/modules/generated/base_address_extended.yaml` |
| `module.base_automation` | required_by | `agents/modules/generated/base_automation.yaml` |

## Full wiki excerpt

- SME owner: [`module.sms`](../../../agents/modules/generated/sms.yaml)
- Domain: `integrations`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sms)
- Direct dependencies: [`base`](../base/overview.md), [`iap_mail`](../iap_mail/overview.md), [`mail`](../mail/overview.md), [`phone_validation`](../phone_validation/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`base_automation`](../base_automation/overview.md), [`calendar_sms`](../calendar_sms/overview.md), [`crm_sms`](../crm_sms/overview.md), [`event_sms`](../event_sms/overview.md), [`hr_presence`](../hr_presence/overview.md), [`hr_recruitment_sms`](../hr_recruitment_sms/overview.md), [`mass_mailing_event_sms`](../mass_mailing_event_sms/overview.md), [`mass_mailing_event_track_sms`](../mass_mailing_event_track_sms/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`project_sms`](../project_sms/overview.md), [`sale_sms`](../sale_sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md), [`stock_sms`](../stock_sms/overview.md), [`test_mail_full`](../test_mail_full/overview.md), [`test_mail_sms`](../test_mail_sms/overview.md), [`website_sms`](../website_sms/overview.md)
- Impact graph: [`module:sms`](../../impact-graph.json)

## Purpose

SMS Text Messaging

## Model relationships

- `ir.actions.server` — extended by [`mail`](../mail/overview.md), [`website`](../website/overview.md)
- `res.partner` — extended by [`account`](../account/overview.md), [`account_add_gln`](../account_add_gln/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`auth_signup`](../auth_signup/overview.md), [`base`](../base/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_vat`](../base_vat/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event`](../event/overview.md), [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`loyalty`](../loyalty/overview.md), [`mail`](../mail/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`membership`](../membership/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sales_team`](../sales_team/overview.md), [`snailmail`](../snailmail/overview.md), [`stock`](../stock/overview.md), [`survey`](../survey/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_inherit`](../test_inherit/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md)
- `sms.composer` — extended by [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md)
- `sms.resend`
- `sms.resend.recipient`
- `sms.sms` — extended by [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md)
- `sms.template` — extended by [`event_sms`](../event_sms/overview.md)
- `sms.template.preview`
- `sms.template.reset`
- `sms.tracker` — extended by [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md)
- Extends `base` — defined by [`base`](../base/overview.md)
- Extends `ir.actions.server` — defined by [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`website`](../website/overview.md)
- Extends `ir.model` — defined by [`base`](../base/overview.md), [`website`](../website/overview.md)
- Extends `mail.followers` — defined by [`mail`](../mail/overview.md)
- Extends `mail.message` — defined by [`mail`](../mail/overview.md)
- Extends `mail.notification` — defined by [`mail`](../mail/overview.md)
- Extends `mail.render.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.phone` — defined by [`phone_validation`](../phone_validation/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `template.reset.mixin` — defined by [`mail`](../mail/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from, model_extended_by
- [`module.account_add_gln`](../../../agents/modules/generated/account_add_gln.yaml) — model_extended_by
- [`module.account_check_printing`](../../../agents/modules/generated/account_check_printing.yaml) — model_extended_by
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — model_extended_by
- [`module.account_peppol`](../../../agents/modules/generated/account_peppol.yaml) — model_extended_by
- [`module.account_peppol_response`](../../../agents/modules/generated/account_peppol_response.yaml) — model_extended_by
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — model_extended_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.base_address_extended`](../../../agents/modules/generated/base_address_extended.yaml) — model_extended_by
- [`module.base_automation`](../../../agents/modules/generated/base_automation.yaml) — required_by
- [`module.base_geolocalize`](../../../agents/modules/generated/base_geolocalize.yaml) — model_extended_by
- [`module.base_vat`](../../../agents/modules/generated/base_vat.yaml) — model_extended_by
- [`module.bus`](../../../agents/modules/generated/bus.yaml) — model_extended_by
- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — model_extended_by
- [`module.calendar_sms`](../../../agents/modules/generated/calendar_sms.yaml) — required_by
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from, model_extended_by
- [`module.crm_sms`](../../../agents/modules/generated/crm_sms.yaml) — required_by
- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — model_extended_by
- [`module.delivery_mondialrelay`](../../../agents/modules/generated/delivery_mondialrelay.yaml) — model_extended_by
- [`module.event`](../../../agents/modules/generated/event.yaml) — model_extended_by
- [`module.event_sms`](../../../agents/modules/generated/event_sms.yaml) — model_extended_by, required_by
- [`module.fleet`](../../../agents/modules/generated/fleet.yaml) — model_extended_by
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — model_extended_by
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — model_extended_by
- [`module.hr_homeworking`](../../../agents/modules/generated/hr_homeworking.yaml) — model_extended_by
- [`module.hr_presence`](../../../agents/modules/generated/hr_presence.yaml) — required_by
- [`module.hr_recruitment_sms`](../../../agents/modules/generated/hr_recruitment_sms.yaml) — required_by
- [`module.iap_mail`](../../../agents/modules/generated/iap_mail.yaml) — depends_on
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — model_extended_by
- [`module.l10n_anz_ubl_pint`](../../../agents/modules/generated/l10n_anz_ubl_pint.yaml) — model_extended_by
- [`module.l10n_ar`](../../../agents/modules/generated/l10n_ar.yaml) — model_extended_by
- [`module.l10n_ar_pos`](../../../agents/modules/generated/l10n_ar_pos.yaml) — model_extended_by
- [`module.l10n_be`](../../../agents/modules/generated/l10n_be.yaml) — model_extended_by
- [`module.l10n_br`](../../../agents/modules/generated/l10n_br.yaml) — model_extended_by
- [`module.l10n_ca`](../../../agents/modules/generated/l10n_ca.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from, model_extended_by
- [`module.l10n_co`](../../../agents/modules/generated/l10n_co.yaml) — model_extended_by
- [`module.l10n_dk`](../../../agents/modules/generated/l10n_dk.yaml) — model_extended_by
- [`module.l10n_dk_oioubl`](../../../agents/modules/generated/l10n_dk_oioubl.yaml) — model_extended_by
- [`module.l10n_ec`](../../../agents/modules/generated/l10n_ec.yaml) — model_extended_by
- [`module.l10n_eg_edi_eta`](../../../agents/modules/generated/l10n_eg_edi_eta.yaml) — model_extended_by
- [`module.l10n_es`](../../../agents/modules/generated/l10n_es.yaml) — model_extended_by
- [`module.l10n_es_edi_facturae`](../../../agents/modules/generated/l10n_es_edi_facturae.yaml) — model_extended_by
- [`module.l10n_es_edi_facturae_adm_centers`](../../../agents/modules/generated/l10n_es_edi_facturae_adm_centers.yaml) — model_extended_by
- [`module.l10n_es_edi_verifactu`](../../../agents/modules/generated/l10n_es_edi_verifactu.yaml) — model_extended_by
- [`module.l10n_fr`](../../../agents/modules/generated/l10n_fr.yaml) — model_extended_by
- [`module.l10n_fr_pdp`](../../../agents/modules/generated/l10n_fr_pdp.yaml) — model_extended_by
- [`module.l10n_hu`](../../../agents/modules/generated/l10n_hu.yaml) — model_extended_by
- [`module.l10n_hu_edi`](../../../agents/modules/generated/l10n_hu_edi.yaml) — model_extended_by
- [`module.l10n_id_efaktur`](../../../agents/modules/generated/l10n_id_efaktur.yaml) — model_extended_by
- [`module.l10n_id_efaktur_coretax`](../../../agents/modules/generated/l10n_id_efaktur_coretax.yaml) — model_extended_by
- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from, model_extended_by
- [`module.l10n_it_edi_doi`](../../../agents/modules/generated/l10n_it_edi_doi.yaml) — model_extended_by
- [`module.l10n_jp_ubl_pint`](../../../agents/modules/generated/l10n_jp_ubl_pint.yaml) — model_extended_by
- [`module.l10n_ke_edi_tremol`](../../../agents/modules/generated/l10n_ke_edi_tremol.yaml) — model_extended_by
- [`module.l10n_latam_base`](../../../agents/modules/generated/l10n_latam_base.yaml) — model_extended_by
- [`module.l10n_ma`](../../../agents/modules/generated/l10n_ma.yaml) — model_extended_by
- [`module.l10n_my_edi`](../../../agents/modules/generated/l10n_my_edi.yaml) — model_extended_by
- [`module.l10n_my_edi_extended`](../../../agents/modules/generated/l10n_my_edi_extended.yaml) — model_extended_by
- [`module.l10n_my_ubl_pint`](../../../agents/modules/generated/l10n_my_ubl_pint.yaml) — model_extended_by
- [`module.l10n_no`](../../../agents/modules/generated/l10n_no.yaml) — model_extended_by
- [`module.l10n_pe`](../../../agents/modules/generated/l10n_pe.yaml) — model_extended_by
- [`module.l10n_pe_pos`](../../../agents/modules/generated/l10n_pe_pos.yaml) — model_extended_by
- [`module.l10n_ph`](../../../agents/modules/generated/l10n_ph.yaml) — model_extended_by
- [`module.l10n_pl`](../../../agents/modules/generated/l10n_pl.yaml) — model_extended_by
- [`module.l10n_ro`](../../../agents/modules/generated/l10n_ro.yaml) — model_extended_by
- [`module.l10n_ro_edi`](../../../agents/modules/generated/l10n_ro_edi.yaml) — model_extended_by
- [`module.l10n_rs_edi`](../../../agents/modules/generated/l10n_rs_edi.yaml) — model_extended_by
- [`module.l10n_sa_edi`](../../../agents/modules/generated/l10n_sa_edi.yaml) — model_extended_by
- [`module.l10n_se`](../../../agents/modules/generated/l10n_se.yaml) — model_extended_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from, model_extended_by
- [`module.l10n_sg_ubl_pint`](../../../agents/modules/generated/l10n_sg_ubl_pint.yaml) — model_extended_by
- [`module.l10n_th`](../../../agents/modules/generated/l10n_th.yaml) — model_extended_by
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from, model_extended_by
- [`module.l10n_tr_nilvera_edispatch`](../../../agents/modules/generated/l10n_tr_nilvera_edispatch.yaml) — model_extended_by
- [`module.l10n_uy`](../../../agents/modules/generated/l10n_uy.yaml) — model_extended_by
- [`module.l10n_vn_edi_viettel`](../../../agents/modules/generated/l10n_vn_edi_viettel.yaml) — model_extended_by
- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — model_extended_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.mail_plugin`](../../../agents/modules/generated/mail_plugin.yaml) — model_extended_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — model_extended_by
- [`module.mass_mailing_event_sms`](../../../agents/modules/generated/mass_mailing_event_sms.yaml) — required_by
- [`module.mass_mailing_event_track_sms`](../../../agents/modules/generated/mass_mailing_event_track_sms.yaml) — required_by
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — model_extended_by, required_by
- [`module.membership`](../../../agents/modules/generated/membership.yaml) — model_extended_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — model_extended_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from, model_extended_by
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — model_extended_by
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — model_extended_by
- [`module.privacy_lookup`](../../../agents/modules/generated/privacy_lookup.yaml) — model_extended_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — model_extended_by
- [`module.project`](../../../agents/modules/generated/project.yaml) — model_extended_by
- [`module.project_sms`](../../../agents/modules/generated/project_sms.yaml) — required_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from, model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — model_extended_by
- [`module.sale_sms`](../../../agents/modules/generated/sale_sms.yaml) — required_by
- [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml) — model_extended_by
- [`module.sms_twilio`](../../../agents/modules/generated/sms_twilio.yaml) — model_extended_by, required_by
- [`module.snailmail`](../../../agents/modules/generated/snailmail.yaml) — model_extended_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — model_extended_by
- [`module.stock_sms`](../../../agents/modules/generated/stock_sms.yaml) — required_by
- [`module.survey`](../../../agents/modules/generated/survey.yaml) — model_extended_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from, model_extended_by
- [`module.test_inherit`](../../../agents/modules/generated/test_inherit.yaml) — model_extended_by
- [`module.test_mail_full`](../../../agents/modules/generated/test_mail_full.yaml) — required_by
- [`module.test_mail_sms`](../../../agents/modules/generated/test_mail_sms.yaml) — required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — model_extended_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from, model_extended_by
- [`module.website_crm_partner_assign`](../../../agents/modules/generated/website_crm_partner_assign.yaml) — model_extended_by
- [`module.website_customer`](../../../agents/modules/generated/website_customer.yaml) — model_extended_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from, model_extended_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by
- [`module.website_sale_mondialrelay`](../../../agents/modules/generated/website_sale_mondialrelay.yaml) — model_extended_by
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — model_extended_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — model_extended_by
- [`module.website_sms`](../../../agents/modules/generated/website_sms.yaml) — required_by

## Regression impact checklist

- Review 16 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`account_add_gln`](../account_add_gln/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`auth_signup`](../auth_signup/overview.md), [`base`](../base/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_vat`](../base_vat/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event`](../event/overview.md), [`event_sms`](../event_sms/overview.md), [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`loyalty`](../loyalty/overview.md), [`mail`](../mail/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`membership`](../membership/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sales_team`](../sales_team/overview.md), [`sms_twilio`](../sms_twilio/overview.md), [`snailmail`](../snailmail/overview.md), [`stock`](../stock/overview.md), [`survey`](../survey/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_inherit`](../test_inherit/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
