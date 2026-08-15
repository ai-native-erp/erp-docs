---
layout: page
title: "Website (website)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website/
nav_order: 0
---
# Website — `website`

**Source:** [`agents/modules/generated/website.yaml`](../../agents/modules/generated/website.yaml) · **Wiki:** [`knowledge/modules/website/overview.md`](../../knowledge/modules/website/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Website</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Enterprise website builder

## Direct dependencies

[`auth_signup`](auth_signup.md), [`digest`](digest.md), [`google_recaptcha`](google_recaptcha.md), [`http_routing`](http_routing.md), [`mail`](mail.md), [`portal`](portal.md), [`social_media`](social_media.md), [`utm`](utm.md), [`web`](web.md), [`web_editor`](web_editor.md)

## Reverse dependencies (modules that depend on this)

[`test_website`](test_website.md), [`test_website_modules`](test_website_modules.md), [`theme_default`](theme_default.md), [`website_cf_turnstile`](website_cf_turnstile.md), [`website_crm`](website_crm.md), [`website_event`](website_event.md), [`website_form_project`](website_form_project.md), [`website_jitsi`](website_jitsi.md), [`website_links`](website_links.md), [`website_livechat`](website_livechat.md), [`website_mail`](website_mail.md), [`website_mail_group`](website_mail_group.md), [`website_mass_mailing`](website_mass_mailing.md), [`website_partner`](website_partner.md), [`website_payment`](website_payment.md), [`website_sale`](website_sale.md), [`website_slides`](website_slides.md), [`website_sms`](website_sms.md), [`website_twitter`](website_twitter.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.actions.server</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.model</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.model.fields</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.module.module</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.ui.view</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>theme.ir.asset</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>theme.ir.attachment</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>theme.ir.ui.view</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>theme.utils</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>theme.website.menu</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>theme.website.page</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.configurator.feature</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.controller.page</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.cover_properties.mixin</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.menu</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.multi.mixin</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.page</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.published.mixin</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.published.multi.mixin</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.rewrite</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.robots</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.route</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.searchable.mixin</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.seo.metadata</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.snippet.filter</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.track</code></div><div class="role">defined by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.visitor</code></div><div class="role">defined by <code>website</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>base</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>base.language.install</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>base.partner.merge.automatic.wizard</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.actions.server</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.asset</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.binary</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.model</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.model.data</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.model.fields</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.qweb</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.contact</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.html</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.rule</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.ui.menu</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>ir.ui.view</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>portal.wizard.user</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>res.lang</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>web_editor.assets</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.menu</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.multi.mixin</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.page</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.published.mixin</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.published.multi.mixin</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.searchable.mixin</code></div><div class="role">extended by <code>website</code></div></div>
<div class="model"><div class="name"><code>website.seo.metadata</code></div><div class="role">extended by <code>website</code></div></div>
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
| `module.auth_signup` | depends_on, model_extended_by | `agents/modules/generated/auth_signup.yaml` |
| `module.base` | extends_model_from, model_extended_by | `agents/modules/generated/base.yaml` |
| `module.base_address_extended` | model_extended_by | `agents/modules/generated/base_address_extended.yaml` |
| `module.base_geolocalize` | model_extended_by | `agents/modules/generated/base_geolocalize.yaml` |

## Full wiki excerpt

- SME owner: [`module.website`](../../../agents/modules/generated/website.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website)
- Direct dependencies: [`auth_signup`](../auth_signup/overview.md), [`digest`](../digest/overview.md), [`google_recaptcha`](../google_recaptcha/overview.md), [`http_routing`](../http_routing/overview.md), [`mail`](../mail/overview.md), [`portal`](../portal/overview.md), [`social_media`](../social_media/overview.md), [`utm`](../utm/overview.md), [`web`](../web/overview.md), [`web_editor`](../web_editor/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_website`](../test_website/overview.md), [`test_website_modules`](../test_website_modules/overview.md), [`theme_default`](../theme_default/overview.md), [`website_cf_turnstile`](../website_cf_turnstile/overview.md), [`website_crm`](../website_crm/overview.md), [`website_event`](../website_event/overview.md), [`website_form_project`](../website_form_project/overview.md), [`website_jitsi`](../website_jitsi/overview.md), [`website_links`](../website_links/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_mail`](../website_mail/overview.md), [`website_mail_group`](../website_mail_group/overview.md), [`website_mass_mailing`](../website_mass_mailing/overview.md), [`website_partner`](../website_partner/overview.md), [`website_payment`](../website_payment/overview.md), [`website_sale`](../website_sale/overview.md), [`website_slides`](../website_slides/overview.md), [`website_sms`](../website_sms/overview.md), [`website_twitter`](../website_twitter/overview.md)
- Impact graph: [`module:website`](../../impact-graph.json)

## Purpose

Enterprise website builder

## Model relationships

- `ir.actions.server` — extended by [`mail`](../mail/overview.md), [`sms`](../sms/overview.md)
- `ir.model` — extended by [`bus`](../bus/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`sms`](../sms/overview.md), [`web`](../web/overview.md)
- `ir.model.fields` — extended by [`base_sparse_field`](../base_sparse_field/overview.md), [`mail`](../mail/overview.md)
- `ir.module.module` — extended by [`account`](../account/overview.md), [`base_import_module`](../base_import_module/overview.md), [`base_install_request`](../base_install_request/overview.md)
- `ir.ui.view` — extended by [`base_import_module`](../base_import_module/overview.md), [`mail`](../mail/overview.md), [`portal`](../portal/overview.md), [`web_editor`](../web_editor/overview.md), [`web_hierarchy`](../web_hierarchy/overview.md)
- `res.partner` — extended by [`account`](../account/overview.md), [`account_add_gln`](../account_add_gln/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`auth_signup`](../auth_signup/overview.md), [`base`](../base/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_vat`](../base_vat/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event`](../event/overview.md), [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`loyalty`](../loyalty/overview.md), [`mail`](../mail/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`membership`](../membership/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`snailmail`](../snailmail/overview.md), [`stock`](../stock/overview.md), [`survey`](../survey/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_inherit`](../test_inherit/overview.md), [`web`](../web/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md)
- `theme.ir.asset`
- `theme.ir.attachment`
- `theme.ir.ui.view`
- `theme.utils`
- `theme.website.menu`
- `theme.website.page`
- `website` — extended by [`l10n_ar_website_sale`](../l10n_ar_website_sale/overview.md), [`l10n_br_website_sale`](../l10n_br_website_sale/overview.md), [`l10n_ec_website_sale`](../l10n_ec_website_sale/overview.md), [`l10n_pe_website_sale`](../l10n_pe_website_sale/overview.md), [`l10n_uy_website_sale`](../l10n_uy_website_sale/overview.md), [`test_website`](../test_website/overview.md), [`website_blog`](../website_blog/overview.md), [`website_crm`](../website_crm/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_event`](../website_event/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_forum`](../website_forum/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_membership`](../website_membership/overview.md), [`website_profile`](../website_profile/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_autocomplete`](../website_sale_autocomplete/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md), [`website_sale_product_configurator`](../website_sale_product_configurator/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_slides`](../website_slides/overview.md), [`website_twitter`](../website_twitter/overview.md)
- `website.configurator.feature`
- `website.controller.page`
- `website.cover_properties.mixin` — extended by [`website_blog`](../website_blog/overview.md), [`website_event`](../website_event/overview.md), [`website_slides`](../website_slides/overview.md)
- `website.menu` — extended by [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md)
- `website.multi.mixin` — extended by [`website_blog`](../website_blog/overview.md), [`website_forum`](../website_forum/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md)
- `website.page`
- `website.published.mixin` — extended by [`test_website`](../test_website/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_profile`](../website_profile/overview.md), [`website_slides`](../website_slides/overview.md)
- `website.published.multi.mixin` — extended by [`test_website`](../test_website/overview.md), [`website_blog`](../website_blog/overview.md), [`website_event`](../website_event/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md), [`website_sale`](../website_sale/overview.md), [`website_slides`](../website_slides/overview.md)
- `website.rewrite`
- `website.robots`
- `website.route`
- `website.searchable.mixin` — extended by [`test_website`](../test_website/overview.md), [`website_blog`](../website_blog/overview.md), [`website_event`](../website_event/overview.md), [`website_forum`](../website_forum/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md), [`website_sale`](../website_sale/overview.md), [`website_slides`](../website_slides/overview.md)
- `website.seo.metadata` — extended by [`test_website`](../test_website/overview.md), [`website_blog`](../website_blog/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_forum`](../website_forum/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md), [`website_slides`](../website_slides/overview.md)
- `website.snippet.filter` — extended by [`website_blog`](../website_blog/overview.md), [`website_event`](../website_event/overview.md), [`website_sale`](../website_sale/overview.md)
- `website.track` — extended by [`website_sale`](../website_sale/overview.md)
- `website.visitor` — extended by [`website_crm`](../website_crm/overview.md), [`website_crm_sms`](../website_crm_sms/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sms`](../website_sms/overview.md)
- Extends `base` — defined by [`base`](../base/overview.md)
- Extends `base.language.install` — defined by [`base`](../base/overview.md)
- Extends `base.partner.merge.automatic.wizard` — defined by [`base`](../base/overview.md)
- Extends `ir.actions.server` — defined by [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`sms`](../sms/overview.md)
- Extends `ir.asset` — defined by [`base`](../base/overview.md)
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)
- Extends `ir.binary` — defined by [`base`](../base/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `ir.model` — defined by [`base`](../base/overview.md)
- Extends `ir.model.data` — defined by [`base`](../base/overview.md)
- Extends `ir.model.fields` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.contact` — defined by [`base`](../base/overview.md), [`web_editor`](../web_editor/overview.md)
- Extends `ir.qweb.field.html` — defined by [`base`](../base/overview.md), [`web_editor`](../web_editor/overview.md)
- Extends `ir.rule` — defined by [`base`](../base/overview.md)
- Extends `ir.ui.menu` — defined by [`base`](../base/overview.md)
- Extends `ir.ui.view` — framework/dynamic owner
- Extends `portal.wizard.user` — defined by [`portal`](../portal/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.lang` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `web_editor.assets` — defined by [`web_editor`](../web_editor/overview.md)
- Extends `website` — framework/dynamic owner
- Extends `website.menu` — framework/dynamic owner
- Extends `website.multi.mixin` — framework/dynamic owner
- Extends `website.page` — framework/dynamic owner
- Extends `website.published.mixin` — framework/dynamic owner
- Extends `website.published.multi.mixin` — framework/dynamic owner
- Extends `website.searchable.mixin` — framework/dynamic owner
- Extends `website.seo.metadata` — framework/dynamic owner

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from, model_extended_by
- [`module.account_add_gln`](../../../agents/modules/generated/account_add_gln.yaml) — model_extended_by
- [`module.account_check_printing`](../../../agents/modules/generated/account_check_printing.yaml) — model_extended_by
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — model_extended_by
- [`module.account_peppol`](../../../agents/modules/generated/account_peppol.yaml) — model_extended_by
- [`module.account_peppol_response`](../../../agents/modules/generated/account_peppol_response.yaml) — model_extended_by
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — depends_on, model_extended_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from, model_extended_by
- [`module.base_address_extended`](../../../agents/modules/generated/base_address_extended.yaml) — model_extended_by
- [`module.base_geolocalize`](../../../agents/modules/generated/base_geolocalize.yaml) — model_extended_by
- [`module.base_import_module`](../../../agents/modules/generated/base_import_module.yaml) — model_extended_by
- [`module.base_install_request`](../../../agents/modules/generated/base_install_request.yaml) — model_extended_by
- [`module.base_sparse_field`](../../../agents/modules/generated/base_sparse_field.yaml) — model_extended_by
- [`module.base_vat`](../../../agents/modules/generated/base_vat.yaml) — model_extended_by
- [`module.bus`](../../../agents/modules/generated/bus.yaml) — model_extended_by
- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — model_extended_by
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from, model_extended_by
- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — model_extended_by
- [`module.delivery_mondialrelay`](../../../agents/modules/generated/delivery_mondialrelay.yaml) — model_extended_by
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — depends_on
- [`module.event`](../../../agents/modules/generated/event.yaml) — model_extended_by
- [`module.fleet`](../../../agents/modules/generated/fleet.yaml) — model_extended_by
- [`module.google_recaptcha`](../../../agents/modules/generated/google_recaptcha.yaml) — depends_on
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — model_extended_by
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — model_extended_by
- [`module.hr_homeworking`](../../../agents/modules/generated/hr_homeworking.yaml) — model_extended_by
- [`module.http_routing`](../../../agents/modules/generated/http_routing.yaml) — depends_on
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — model_extended_by
- [`module.l10n_anz_ubl_pint`](../../../agents/modules/generated/l10n_anz_ubl_pint.yaml) — model_extended_by
- [`module.l10n_ar`](../../../agents/modules/generated/l10n_ar.yaml) — model_extended_by
- [`module.l10n_ar_pos`](../../../agents/modules/generated/l10n_ar_pos.yaml) — model_extended_by
- [`module.l10n_ar_website_sale`](../../../agents/modules/generated/l10n_ar_website_sale.yaml) — model_extended_by
- [`module.l10n_be`](../../../agents/modules/generated/l10n_be.yaml) — model_extended_by
- [`module.l10n_br`](../../../agents/modules/generated/l10n_br.yaml) — model_extended_by
- [`module.l10n_br_website_sale`](../../../agents/modules/generated/l10n_br_website_sale.yaml) — model_extended_by
- [`module.l10n_ca`](../../../agents/modules/generated/l10n_ca.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from, model_extended_by
- [`module.l10n_co`](../../../agents/modules/generated/l10n_co.yaml) — model_extended_by
- [`module.l10n_dk`](../../../agents/modules/generated/l10n_dk.yaml) — model_extended_by
- [`module.l10n_dk_oioubl`](../../../agents/modules/generated/l10n_dk_oioubl.yaml) — model_extended_by
- [`module.l10n_ec`](../../../agents/modules/generated/l10n_ec.yaml) — model_extended_by
- [`module.l10n_ec_website_sale`](../../../agents/modules/generated/l10n_ec_website_sale.yaml) — model_extended_by
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
- [`module.l10n_pe_website_sale`](../../../agents/modules/generated/l10n_pe_website_sale.yaml) — model_extended_by
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
- [`module.l10n_uy_website_sale`](../../../agents/modules/generated/l10n_uy_website_sale.yaml) — model_extended_by
- [`module.l10n_vn_edi_viettel`](../../../agents/modules/generated/l10n_vn_edi_viettel.yaml) — model_extended_by
- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — model_extended_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.mail_plugin`](../../../agents/modules/generated/mail_plugin.yaml) — model_extended_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from, model_extended_by
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.membership`](../../../agents/modules/generated/membership.yaml) — model_extended_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — model_extended_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from, model_extended_by
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — model_extended_by
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from, model_extended_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.privacy_lookup`](../../../agents/modules/generated/privacy_lookup.yaml) — model_extended_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — model_extended_by
- [`module.project`](../../../agents/modules/generated/project.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from, model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — model_extended_by
- [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml) — model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from, model_extended_by
- [`module.snailmail`](../../../agents/modules/generated/snailmail.yaml) — model_extended_by
- [`module.social_media`](../../../agents/modules/generated/social_media.yaml) — depends_on
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — model_extended_by
- [`module.survey`](../../../agents/modules/generated/survey.yaml) — model_extended_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from, model_extended_by
- [`module.test_inherit`](../../../agents/modules/generated/test_inherit.yaml) — model_extended_by
- [`module.test_website`](../../../agents/modules/generated/test_website.yaml) — model_extended_by, required_by
- [`module.test_website_modules`](../../../agents/modules/generated/test_website_modules.yaml) — required_by
- [`module.theme_default`](../../../agents/modules/generated/theme_default.yaml) — required_by
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — depends_on
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on, model_extended_by
- [`module.web_editor`](../../../agents/modules/generated/web_editor.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.web_hierarchy`](../../../agents/modules/generated/web_hierarchy.yaml) — model_extended_by
- [`module.website_blog`](../../../agents/modules/generated/website_blog.yaml) — model_extended_by
- [`module.website_cf_turnstile`](../../../agents/modules/generated/website_cf_turnstile.yaml) — required_by
- [`module.website_crm`](../../../agents/modules/generated/website_crm.yaml) — model_extended_by, required_by
- [`module.website_crm_partner_assign`](../../../agents/modules/generated/website_crm_partner_assign.yaml) — model_extended_by
- [`module.website_crm_sms`](../../../agents/modules/generated/website_crm_sms.yaml) — model_extended_by
- [`module.website_customer`](../../../agents/modules/generated/website_customer.yaml) — model_extended_by
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — model_extended_by, required_by
- [`module.website_event_booth_sale`](../../../agents/modules/generated/website_event_booth_sale.yaml) — model_extended_by
- [`module.website_event_exhibitor`](../../../agents/modules/generated/website_event_exhibitor.yaml) — model_extended_by
- [`module.website_event_meet`](../../../agents/modules/generated/website_event_meet.yaml) — model_extended_by
- [`module.website_event_sale`](../../../agents/modules/generated/website_event_sale.yaml) — model_extended_by
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — model_extended_by
- [`module.website_form_project`](../../../agents/modules/generated/website_form_project.yaml) — required_by
- [`module.website_forum`](../../../agents/modules/generated/website_forum.yaml) — model_extended_by
- [`module.website_hr_recruitment`](../../../agents/modules/generated/website_hr_recruitment.yaml) — model_extended_by
- [`module.website_jitsi`](../../../agents/modules/generated/website_jitsi.yaml) — required_by
- [`module.website_links`](../../../agents/modules/generated/website_links.yaml) — required_by
- [`module.website_livechat`](../../../agents/modules/generated/website_livechat.yaml) — model_extended_by, required_by
- [`module.website_mail`](../../../agents/modules/generated/website_mail.yaml) — required_by
- [`module.website_mail_group`](../../../agents/modules/generated/website_mail_group.yaml) — required_by
- [`module.website_mass_mailing`](../../../agents/modules/generated/website_mass_mailing.yaml) — required_by
- [`module.website_membership`](../../../agents/modules/generated/website_membership.yaml) — model_extended_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from, model_extended_by, required_by
- [`module.website_payment`](../../../agents/modules/generated/website_payment.yaml) — required_by
- [`module.website_profile`](../../../agents/modules/generated/website_profile.yaml) — model_extended_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by, required_by
- [`module.website_sale_autocomplete`](../../../agents/modules/generated/website_sale_autocomplete.yaml) — model_extended_by
- [`module.website_sale_loyalty`](../../../agents/modules/generated/website_sale_loyalty.yaml) — model_extended_by
- [`module.website_sale_mondialrelay`](../../../agents/modules/generated/website_sale_mondialrelay.yaml) — model_extended_by
- [`module.website_sale_picking`](../../../agents/modules/generated/website_sale_picking.yaml) — model_extended_by
- [`module.website_sale_product_configurator`](../../../agents/modules/generated/website_sale_product_configurator.yaml) — model_extended_by
- [`module.website_sale_slides`](../../../agents/modules/generated/website_sale_slides.yaml) — model_extended_by
- [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml) — model_extended_by
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — model_extended_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — model_extended_by, required_by
- [`module.website_sms`](../../../agents/modules/generated/website_sms.yaml) — model_extended_by, required_by
- [`module.website_twitter`](../../../agents/modules/generated/website_twitter.yaml) — model_extended_by, required_by

## Regression impact checklist

- Review 19 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`account_add_gln`](../account_add_gln/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`auth_signup`](../auth_signup/overview.md), [`base`](../base/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_import_module`](../base_import_module/overview.md), [`base_install_request`](../base_install_request/overview.md), [`base_sparse_field`](../base_sparse_field/overview.md), [`base_vat`](../base_vat/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event`](../event/overview.md), [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_ar_website_sale`](../l10n_ar_website_sale/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_br_website_sale`](../l10n_br_website_sale/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_ec_website_sale`](../l10n_ec_website_sale/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_pe_website_sale`](../l10n_pe_website_sale/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_uy_website_sale`](../l10n_uy_website_sale/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`loyalty`](../loyalty/overview.md), [`mail`](../mail/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`membership`](../membership/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`snailmail`](../snailmail/overview.md), [`stock`](../stock/overview.md), [`survey`](../survey/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_inherit`](../test_inherit/overview.md), [`test_website`](../test_website/overview.md), [`web`](../web/overview.md), [`web_editor`](../web_editor/overview.md), [`web_hierarchy`](../web_hierarchy/overview.md), [`website_blog`](../website_blog/overview.md), [`website_crm`](../website_crm/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_crm_sms`](../website_crm_sms/overview.md), [`website_customer`](../website_customer/overview.md), [`website_event`](../website_event/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_forum`](../website_forum/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_membership`](../website_membership/overview.md), [`website_partner`](../website_partner/overview.md), [`website_profile`](../website_profile/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_autocomplete`](../website_sale_autocomplete/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md), [`website_sale_product_configurator`](../website_sale_product_configurator/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md), [`website_sms`](../website_sms/overview.md), [`website_twitter`](../website_twitter/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`portal`](../portal/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`web_editor`](../web_editor/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
