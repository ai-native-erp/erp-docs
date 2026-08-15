---
layout: page
title: "CRM (crm)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/crm/
nav_order: 0
---
# CRM — `crm`

**Source:** [`agents/modules/generated/crm.yaml`](../../agents/modules/generated/crm.yaml) · **Wiki:** [`knowledge/modules/crm/overview.md`](../../knowledge/modules/crm/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>crm</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">CRM</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/crm</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/crm"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Track leads and close opportunities

## Direct dependencies

[`base_setup`](base_setup.md), [`calendar`](calendar.md), [`contacts`](contacts.md), [`digest`](digest.md), [`mail`](mail.md), [`phone_validation`](phone_validation.md), [`resource`](resource.md), [`sales_team`](sales_team.md), [`utm`](utm.md), [`web_tour`](web_tour.md)

## Reverse dependencies (modules that depend on this)

[`crm_livechat`](crm_livechat.md), [`crm_mail_plugin`](crm_mail_plugin.md), [`crm_sms`](crm_sms.md), [`event_crm`](event_crm.md), [`iap_crm`](iap_crm.md), [`mass_mailing_crm`](mass_mailing_crm.md), [`sale_crm`](sale_crm.md), [`test_crm_full`](test_crm_full.md), [`test_discuss_full`](test_discuss_full.md), [`test_main_flows`](test_main_flows.md), [`website_crm`](website_crm.md), [`website_crm_partner_assign`](website_crm_partner_assign.md), [`website_crm_sms`](website_crm_sms.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.activity.report</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.lead</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.lead.lost</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.lead.pls.update</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.lead.scoring.frequency</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.lead.scoring.frequency.field</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.lead2opportunity.partner</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.lead2opportunity.partner.mass</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.lost.reason</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.merge.opportunity</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.recurring.plan</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.stage</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.team</code></div><div class="role">defined by <code>crm</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">defined by <code>crm</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>calendar.event</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.lead</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.lead2opportunity.partner</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.team</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>crm.team.member</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>digest.digest</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>format.address.mixin</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>ir.config_parameter</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>mail.activity</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>mail.alias.mixin</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>mail.thread.blacklist</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>mail.thread.cc</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>mail.thread.phone</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>mail.tracking.duration.mixin</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>utm.campaign</code></div><div class="role">extended by <code>crm</code></div></div>
<div class="model"><div class="name"><code>utm.mixin</code></div><div class="role">extended by <code>crm</code></div></div>
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
| `module.base` | extends_model_from, model_extended_by | `agents/modules/generated/base.yaml` |
| `module.base_address_extended` | model_extended_by | `agents/modules/generated/base_address_extended.yaml` |
| `module.base_geolocalize` | model_extended_by | `agents/modules/generated/base_geolocalize.yaml` |

## Full wiki excerpt

- SME owner: [`module.crm`](../../../agents/modules/generated/crm.yaml)
- Domain: `sales_crm`
- Category: Sales/CRM
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/crm)
- Direct dependencies: [`base_setup`](../base_setup/overview.md), [`calendar`](../calendar/overview.md), [`contacts`](../contacts/overview.md), [`digest`](../digest/overview.md), [`mail`](../mail/overview.md), [`phone_validation`](../phone_validation/overview.md), [`resource`](../resource/overview.md), [`sales_team`](../sales_team/overview.md), [`utm`](../utm/overview.md), [`web_tour`](../web_tour/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`crm_livechat`](../crm_livechat/overview.md), [`crm_mail_plugin`](../crm_mail_plugin/overview.md), [`crm_sms`](../crm_sms/overview.md), [`event_crm`](../event_crm/overview.md), [`iap_crm`](../iap_crm/overview.md), [`mass_mailing_crm`](../mass_mailing_crm/overview.md), [`sale_crm`](../sale_crm/overview.md), [`test_crm_full`](../test_crm_full/overview.md), [`test_discuss_full`](../test_discuss_full/overview.md), [`test_main_flows`](../test_main_flows/overview.md), [`website_crm`](../website_crm/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_crm_sms`](../website_crm_sms/overview.md)
- Impact graph: [`module:crm`](../../impact-graph.json)

## Purpose

Track leads and close opportunities

## Model relationships

- `crm.activity.report`
- `crm.lead` — extended by [`crm_iap_enrich`](../crm_iap_enrich/overview.md), [`crm_iap_mine`](../crm_iap_mine/overview.md), [`crm_mail_plugin`](../crm_mail_plugin/overview.md), [`event_crm`](../event_crm/overview.md), [`iap_crm`](../iap_crm/overview.md), [`mass_mailing_crm`](../mass_mailing_crm/overview.md), [`sale_crm`](../sale_crm/overview.md), [`website_crm`](../website_crm/overview.md), [`website_crm_iap_reveal`](../website_crm_iap_reveal/overview.md), [`website_crm_livechat`](../website_crm_livechat/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md)
- `crm.lead.lost`
- `crm.lead.pls.update`
- `crm.lead.scoring.frequency`
- `crm.lead.scoring.frequency.field`
- `crm.lead2opportunity.partner`
- `crm.lead2opportunity.partner.mass`
- `crm.lost.reason`
- `crm.merge.opportunity`
- `crm.recurring.plan`
- `crm.stage`
- `crm.team` — extended by [`pos_sale`](../pos_sale/overview.md), [`sale`](../sale/overview.md), [`sale_crm`](../sale_crm/overview.md), [`website_sale`](../website_sale/overview.md)
- `res.partner` — extended by [`account`](../account/overview.md), [`account_add_gln`](../account_add_gln/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`auth_signup`](../auth_signup/overview.md), [`base`](../base/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_vat`](../base_vat/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event`](../event/overview.md), [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`loyalty`](../loyalty/overview.md), [`mail`](../mail/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`membership`](../membership/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`snailmail`](../snailmail/overview.md), [`stock`](../stock/overview.md), [`survey`](../survey/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_inherit`](../test_inherit/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md)
- Extends `calendar.event` — defined by [`calendar`](../calendar/overview.md), [`google_calendar`](../google_calendar/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md)
- Extends `crm.lead` — framework/dynamic owner
- Extends `crm.lead2opportunity.partner` — framework/dynamic owner
- Extends `crm.team` — defined by [`sales_team`](../sales_team/overview.md)
- Extends `crm.team.member` — defined by [`sales_team`](../sales_team/overview.md)
- Extends `digest.digest` — defined by [`digest`](../digest/overview.md)
- Extends `format.address.mixin` — defined by [`base`](../base/overview.md)
- Extends `ir.config_parameter` — defined by [`base`](../base/overview.md)
- Extends `mail.activity` — defined by [`mail`](../mail/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.alias.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.blacklist` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.cc` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.phone` — defined by [`phone_validation`](../phone_validation/overview.md)
- Extends `mail.tracking.duration.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `utm.campaign` — defined by [`utm`](../utm/overview.md)
- Extends `utm.mixin` — defined by [`utm`](../utm/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from, model_extended_by
- [`module.account_add_gln`](../../../agents/modules/generated/account_add_gln.yaml) — model_extended_by
- [`module.account_check_printing`](../../../agents/modules/generated/account_check_printing.yaml) — model_extended_by
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — model_extended_by
- [`module.account_peppol`](../../../agents/modules/generated/account_peppol.yaml) — model_extended_by
- [`module.account_peppol_response`](../../../agents/modules/generated/account_peppol_response.yaml) — model_extended_by
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — model_extended_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from, model_extended_by
- [`module.base_address_extended`](../../../agents/modules/generated/base_address_extended.yaml) — model_extended_by
- [`module.base_geolocalize`](../../../agents/modules/generated/base_geolocalize.yaml) — model_extended_by
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on
- [`module.base_vat`](../../../agents/modules/generated/base_vat.yaml) — model_extended_by
- [`module.bus`](../../../agents/modules/generated/bus.yaml) — model_extended_by
- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — depends_on, extends_model_from
- [`module.crm_iap_enrich`](../../../agents/modules/generated/crm_iap_enrich.yaml) — model_extended_by
- [`module.crm_iap_mine`](../../../agents/modules/generated/crm_iap_mine.yaml) — model_extended_by
- [`module.crm_livechat`](../../../agents/modules/generated/crm_livechat.yaml) — required_by
- [`module.crm_mail_plugin`](../../../agents/modules/generated/crm_mail_plugin.yaml) — model_extended_by, required_by
- [`module.crm_sms`](../../../agents/modules/generated/crm_sms.yaml) — required_by
- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — model_extended_by
- [`module.delivery_mondialrelay`](../../../agents/modules/generated/delivery_mondialrelay.yaml) — model_extended_by
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — depends_on, extends_model_from
- [`module.event`](../../../agents/modules/generated/event.yaml) — model_extended_by
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — model_extended_by, required_by
- [`module.fleet`](../../../agents/modules/generated/fleet.yaml) — model_extended_by
- [`module.google_calendar`](../../../agents/modules/generated/google_calendar.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — model_extended_by
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — model_extended_by
- [`module.hr_homeworking`](../../../agents/modules/generated/hr_homeworking.yaml) — model_extended_by
- [`module.iap_crm`](../../../agents/modules/generated/iap_crm.yaml) — model_extended_by, required_by
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
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from, model_extended_by
- [`module.mass_mailing_crm`](../../../agents/modules/generated/mass_mailing_crm.yaml) — model_extended_by, required_by
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.membership`](../../../agents/modules/generated/membership.yaml) — model_extended_by
- [`module.microsoft_calendar`](../../../agents/modules/generated/microsoft_calendar.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — model_extended_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from, model_extended_by
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — model_extended_by
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — model_extended_by
- [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml) — model_extended_by
- [`module.privacy_lookup`](../../../agents/modules/generated/privacy_lookup.yaml) — model_extended_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — model_extended_by
- [`module.project`](../../../agents/modules/generated/project.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from, model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — model_extended_by
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — depends_on
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — model_extended_by
- [`module.sale_crm`](../../../agents/modules/generated/sale_crm.yaml) — model_extended_by, required_by
- [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from, model_extended_by
- [`module.snailmail`](../../../agents/modules/generated/snailmail.yaml) — model_extended_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — model_extended_by
- [`module.survey`](../../../agents/modules/generated/survey.yaml) — model_extended_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from, model_extended_by
- [`module.test_crm_full`](../../../agents/modules/generated/test_crm_full.yaml) — required_by
- [`module.test_discuss_full`](../../../agents/modules/generated/test_discuss_full.yaml) — required_by
- [`module.test_inherit`](../../../agents/modules/generated/test_inherit.yaml) — model_extended_by
- [`module.test_main_flows`](../../../agents/modules/generated/test_main_flows.yaml) — required_by
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — depends_on, extends_model_from
- [`module.web`](../../../agents/modules/generated/web.yaml) — model_extended_by
- [`module.web_tour`](../../../agents/modules/generated/web_tour.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from, model_extended_by
- [`module.website_crm`](../../../agents/modules/generated/website_crm.yaml) — model_extended_by, required_by
- [`module.website_crm_iap_reveal`](../../../agents/modules/generated/website_crm_iap_reveal.yaml) — model_extended_by
- [`module.website_crm_livechat`](../../../agents/modules/generated/website_crm_livechat.yaml) — model_extended_by
- [`module.website_crm_partner_assign`](../../../agents/modules/generated/website_crm_partner_assign.yaml) — model_extended_by, required_by
- [`module.website_crm_sms`](../../../agents/modules/generated/website_crm_sms.yaml) — required_by
- [`module.website_customer`](../../../agents/modules/generated/website_customer.yaml) — model_extended_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from, model_extended_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by
- [`module.website_sale_mondialrelay`](../../../agents/modules/generated/website_sale_mondialrelay.yaml) — model_extended_by
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — model_extended_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — model_extended_by

## Regression impact checklist

- Review 13 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`account_add_gln`](../account_add_gln/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`auth_signup`](../auth_signup/overview.md), [`base`](../base/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_vat`](../base_vat/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`crm_iap_enrich`](../crm_iap_enrich/overview.md), [`crm_iap_mine`](../crm_iap_mine/overview.md), [`crm_mail_plugin`](../crm_mail_plugin/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`iap_crm`](../iap_crm/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`loyalty`](../loyalty/overview.md), [`mail`](../mail/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_crm`](../mass_mailing_crm/overview.md), [`membership`](../membership/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`pos_sale`](../pos_sale/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sale_crm`](../sale_crm/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`snailmail`](../snailmail/overview.md), [`stock`](../stock/overview.md), [`survey`](../survey/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_inherit`](../test_inherit/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md), [`website_crm`](../website_crm/overview.md), [`website_crm_iap_reveal`](../website_crm_iap_reveal/overview.md), [`website_crm_livechat`](../website_crm_livechat/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`calendar`](../calendar/overview.md), [`contacts`](../contacts/overview.md), [`digest`](../digest/overview.md), [`google_calendar`](../google_calendar/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`utm`](../utm/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
