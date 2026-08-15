---
layout: page
title: "Discuss (mail)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mail/
nav_order: 0
---
# Discuss — `mail`

**Source:** [`agents/modules/generated/mail.yaml`](../../agents/modules/generated/mail.yaml) · **Wiki:** [`knowledge/modules/mail/overview.md`](../../knowledge/modules/mail/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mail</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Discuss</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mail</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mail"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Chat, mail gateway and private channels

## Direct dependencies

[`base`](base.md), [`base_setup`](base_setup.md), [`bus`](bus.md), [`web_tour`](web_tour.md)

## Reverse dependencies (modules that depend on this)

[`analytic`](analytic.md), [`auth_signup`](auth_signup.md), [`auth_totp_mail`](auth_totp_mail.md), [`auth_totp_mail_enforce`](auth_totp_mail_enforce.md), [`base_automation`](base_automation.md), [`base_install_request`](base_install_request.md), [`calendar`](calendar.md), [`contacts`](contacts.md), [`crm`](crm.md), [`data_recycle`](data_recycle.md), [`digest`](digest.md), [`event`](event.md), [`fleet`](fleet.md), [`gamification`](gamification.md), [`google_gmail`](google_gmail.md), [`hr`](hr.md), [`iap_mail`](iap_mail.md), [`im_livechat`](im_livechat.md), [`link_tracker`](link_tracker.md), [`lunch`](lunch.md), [`mail_bot`](mail_bot.md), [`mail_group`](mail_group.md), [`maintenance`](maintenance.md), [`mass_mailing`](mass_mailing.md), [`microsoft_outlook`](microsoft_outlook.md), [`phone_validation`](phone_validation.md), [`portal`](portal.md), [`privacy_lookup`](privacy_lookup.md), [`product`](product.md), [`project`](project.md), [`rating`](rating.md), [`sale_order_extension`](sale_order_extension.md), [`sales_team`](sales_team.md), [`sms`](sms.md), [`snailmail`](snailmail.md), [`survey`](survey.md), [`test_discuss_full`](test_discuss_full.md), [`test_mail`](test_mail.md), [`test_mail_full`](test_mail_full.md), [`test_mail_sms`](test_mail_sms.md), [`website`](website.md), [`website_mail`](website_mail.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>discuss.channel</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>discuss.channel.member</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>discuss.channel.rtc.session</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>discuss.gif.favorite</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>discuss.voice.metadata</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>fetchmail.server</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.actions.server</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.mail_server</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.activity</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.activity.plan</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.activity.plan.template</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.activity.schedule</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.activity.type</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.alias</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.alias.domain</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.alias.mixin</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.alias.mixin.optional</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.blacklist</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.blacklist.remove</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.compose.message</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.composer.mixin</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.followers</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.gateway.allowed</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.guest</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.ice.server</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.link.preview</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.mail</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.message</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.message.reaction</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.message.schedule</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.message.subtype</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.message.translation</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.notification</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.notification.web.push</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.partner.device</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.render.mixin</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.resend.message</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.resend.partner</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.shortcode</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.template</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.template.preview</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.template.reset</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.thread.blacklist</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.thread.cc</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.thread.main.attachment</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.tracking.duration.mixin</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.tracking.value</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.wizard.invite</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>publisher_warranty.contract</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>res.users.settings.volumes</code></div><div class="role">defined by <code>mail</code></div></div>
<div class="model"><div class="name"><code>template.reset.mixin</code></div><div class="role">defined by <code>mail</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>avatar.mixin</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>base</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>base.module.uninstall</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>base.partner.merge.automatic.wizard</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>bus.presence</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>discuss.channel</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>discuss.channel.member</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.actions.act_window.view</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.actions.server</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.config_parameter</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.mail_server</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.model</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.model.fields</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.qweb</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.ui.view</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>ir.websocket</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.alias</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.alias.mixin.optional</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.composer.mixin</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.message</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.notification</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.render.mixin</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>mail.thread.blacklist</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>res.groups</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>res.users.settings</code></div><div class="role">extended by <code>mail</code></div></div>
<div class="model"><div class="name"><code>template.reset.mixin</code></div><div class="role">extended by <code>mail</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from, model_extended_by | `agents/modules/generated/account.yaml` |
| `module.account_add_gln` | model_extended_by | `agents/modules/generated/account_add_gln.yaml` |
| `module.account_audit_trail` | model_extended_by | `agents/modules/generated/account_audit_trail.yaml` |
| `module.account_check_printing` | model_extended_by | `agents/modules/generated/account_check_printing.yaml` |
| `module.account_edi_proxy_client` | model_extended_by | `agents/modules/generated/account_edi_proxy_client.yaml` |
| `module.account_edi_ubl_cii` | model_extended_by | `agents/modules/generated/account_edi_ubl_cii.yaml` |
| `module.account_lock` | model_extended_by | `agents/modules/generated/account_lock.yaml` |
| `module.account_peppol` | model_extended_by | `agents/modules/generated/account_peppol.yaml` |
| `module.account_peppol_response` | model_extended_by | `agents/modules/generated/account_peppol_response.yaml` |
| `module.analytic` | model_extended_by, required_by | `agents/modules/generated/analytic.yaml` |

## Conversation learnings

- [`2026-08-10-sale-servicenow-patterns`](../../knowledge/conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-13-ho-partial-registry-landing-repair`](../../knowledge/conversations/2026-08-13-ho-partial-registry-landing-repair.json)

## Full wiki excerpt

- SME owner: [`module.mail`](../../../agents/modules/generated/mail.yaml)
- Domain: `platform_core`
- Category: Productivity/Discuss
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mail)
- Direct dependencies: [`base`](../base/overview.md), [`base_setup`](../base_setup/overview.md), [`bus`](../bus/overview.md), [`web_tour`](../web_tour/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`analytic`](../analytic/overview.md), [`auth_signup`](../auth_signup/overview.md), [`auth_totp_mail`](../auth_totp_mail/overview.md), [`auth_totp_mail_enforce`](../auth_totp_mail_enforce/overview.md), [`base_automation`](../base_automation/overview.md), [`base_install_request`](../base_install_request/overview.md), [`calendar`](../calendar/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`data_recycle`](../data_recycle/overview.md), [`digest`](../digest/overview.md), [`event`](../event/overview.md), [`fleet`](../fleet/overview.md), [`gamification`](../gamification/overview.md), [`google_gmail`](../google_gmail/overview.md), [`hr`](../hr/overview.md), [`iap_mail`](../iap_mail/overview.md), [`im_livechat`](../im_livechat/overview.md), [`link_tracker`](../link_tracker/overview.md), [`lunch`](../lunch/overview.md), [`mail_bot`](../mail_bot/overview.md), [`mail_group`](../mail_group/overview.md), [`maintenance`](../maintenance/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md), [`phone_validation`](../phone_validation/overview.md), [`portal`](../portal/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`rating`](../rating/overview.md), [`sale_order_extension`](../sale_order_extension/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`snailmail`](../snailmail/overview.md), [`survey`](../survey/overview.md), [`test_discuss_full`](../test_discuss_full/overview.md), [`test_mail`](../test_mail/overview.md), [`test_mail_full`](../test_mail_full/overview.md), [`test_mail_sms`](../test_mail_sms/overview.md), [`website`](../website/overview.md), [`website_mail`](../website_mail/overview.md)
- Impact graph: [`module:mail`](../../impact-graph.json)

## Purpose

Chat, mail gateway and private channels

## Model relationships

- `discuss.channel` — extended by [`crm_livechat`](../crm_livechat/overview.md), [`hr`](../hr/overview.md), [`im_livechat`](../im_livechat/overview.md), [`mail_bot`](../mail_bot/overview.md), [`website_crm_livechat`](../website_crm_livechat/overview.md), [`website_livechat`](../website_livechat/overview.md)
- `discuss.channel.member` — extended by [`im_livechat`](../im_livechat/overview.md)
- `discuss.channel.rtc.session`
- `discuss.gif.favorite`
- `discuss.voice.metadata`
- `fetchmail.server` — extended by [`google_gmail`](../google_gmail/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md)
- `ir.actions.server` — extended by [`sms`](../sms/overview.md), [`website`](../website/overview.md)
- `ir.mail_server` — extended by [`google_gmail`](../google_gmail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md)
- `mail.activity` — extended by [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md)
- `mail.activity.mixin` — extended by [`account`](../account/overview.md), [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md), [`event`](../event/overview.md), [`event_booth`](../event_booth/overview.md), [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in_ewaybill_stock`](../l10n_in_ewaybill_stock/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`lunch`](../lunch/overview.md), [`maintenance`](../maintenance/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mrp`](../mrp/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_requisition`](../purchase_requisition/overview.md), [`repair`](../repair/overview.md), [`sale`](../sale/overview.md), [`stock`](../stock/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md), [`survey`](../survey/overview.md), [`test_mail`](../test_mail/overview.md), [`test_mail_full`](../test_mail_full/overview.md), [`test_mail_sms`](../test_mail_sms/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_slides`](../website_slides/overview.md)
- `mail.activity.plan` — extended by [`hr`](../hr/overview.md)
- `mail.activity.plan.template` — extended by [`hr`](../hr/overview.md), [`hr_fleet`](../hr_fleet/overview.md)
- `mail.activity.schedule` — extended by [`calendar`](../calendar/overview.md), [`hr`](../hr/overview.md), [`hr_contract`](../hr_contract/overview.md)
- `mail.activity.type` — extended by [`calendar`](../calendar/overview.md), [`fleet`](../fleet/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`project_todo`](../project_todo/overview.md)
- `mail.alias` — extended by [`hr`](../hr/overview.md)
- `mail.alias.domain`
- `mail.alias.mixin` — extended by [`crm`](../crm/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`mail_group`](../mail_group/overview.md), [`maintenance`](../maintenance/overview.md), [`project`](../project/overview.md), [`test_mail`](../test_mail/overview.md)
- `mail.alias.mixin.optional` — extended by [`account`](../account/overview.md), [`test_mail`](../test_mail/overview.md)
- `mail.blacklist` — extended by [`mass_mailing`](../mass_mailing/overview.md)
- `mail.blacklist.remove`
- `mail.compose.message` — extended by [`mass_mailing`](../mass_mailing/overview.md), [`repair`](../repair/overview.md)
- `mail.composer.mixin` — extended by [`hr_recruitment`](../hr_recruitment/overview.md), [`sale`](../sale/overview.md), [`survey`](../survey/overview.md), [`test_mail`](../test_mail/overview.md), [`website_slides`](../website_slides/overview.md)
- `mail.followers` — extended by [`sms`](../sms/overview.md)
- `mail.gateway.allowed`
- `mail.guest`
- `mail.ice.server`
- `mail.link.preview`
- `mail.mail` — extended by [`mass_mailing`](../mass_mailing/overview.md)
- `mail.message` — extended by [`account_audit_trail`](../account_audit_trail/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_in`](../l10n_in/overview.md), [`portal`](../portal/overview.md), [`portal_rating`](../portal_rating/overview.md), [`project`](../project/overview.md), [`rating`](../rating/overview.md), [`sms`](../sms/overview.md), [`snailmail`](../snailmail/overview.md), [`website_forum`](../website_forum/overview.md)
- `mail.message.reaction`
- `mail.message.schedule`
- `mail.message.subtype` — extended by [`hr_holidays`](../hr_holidays/overview.md)
- `mail.message.translation`
- `mail.notification` — extended by [`sms`](../sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md), [`snailmail`](../snailmail/overview.md)
- `mail.notification.web.push`
- `mail.partner.device`
- `mail.render.mixin` — extended by [`link_tracker`](../link_tracker/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`sms`](../sms/overview.md)
- `mail.resend.message`
- `mail.resend.partner`
- `mail.shortcode`
- `mail.template` — extended by [`event`](../event/overview.md)
- `mail.template.preview`
- `mail.template.reset`
- `mail.thread` — extended by [`account`](../account/overview.md), [`analytic`](../analytic/overview.md), [`calendar`](../calendar/overview.md), [`event`](../event/overview.md), [`event_booth`](../event_booth/overview.md), [`fleet`](../fleet/overview.md), [`gamification`](../gamification/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_in_ewaybill_stock`](../l10n_in_ewaybill_stock/overview.md), [`loyalty`](../loyalty/overview.md), [`lunch`](../lunch/overview.md), [`mail_bot`](../mail_bot/overview.md), [`maintenance`](../maintenance/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mrp`](../mrp/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_requisition`](../purchase_requisition/overview.md), [`rating`](../rating/overview.md), [`repair`](../repair/overview.md), [`sale`](../sale/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`snailmail`](../snailmail/overview.md), [`stock`](../stock/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md), [`survey`](../survey/overview.md), [`test_base_automation`](../test_base_automation/overview.md), [`test_mail`](../test_mail/overview.md), [`test_mail_full`](../test_mail_full/overview.md), [`test_mail_sms`](../test_mail_sms/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md), [`website_blog`](../website_blog/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_forum`](../website_forum/overview.md), [`website_slides`](../website_slides/overview.md)
- `mail.thread.blacklist` — extended by [`crm`](../crm/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`test_mail`](../test_mail/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md)
- `mail.thread.cc` — extended by [`crm`](../crm/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`maintenance`](../maintenance/overview.md), [`project`](../project/overview.md), [`test_mail`](../test_mail/overview.md)
- `mail.thread.main.attachment` — extended by [`account`](../account/overview.md), [`hr`](../hr/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`test_mail`](../test_mail/overview.md)
- `mail.tracking.duration.mixin` — extended by [`crm`](../crm/overview.md), [`project`](../project/overview.md), [`test_mail`](../test_mail/overview.md)
- `mail.tracking.value` — extended by [`account_audit_trail`](../account_audit_trail/overview.md)
- `mail.wizard.invite`
- `publisher_warranty.contract` — extended by [`website_mail`](../website_mail/overview.md)
- `res.company` — extended by [`account`](../account/overview.md), [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_proxy_client`](../account_edi_proxy_client/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_lock`](../account_lock/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`auth_ldap`](../auth_ldap/overview.md), [`barcodes`](../barcodes/overview.md), [`base`](../base/overview.md), [`base_vat`](../base_vat/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_presence`](../hr_presence/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_eu_oss`](../l10n_eu_oss/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_hr_holidays`](../l10n_fr_hr_holidays/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_fr_pdp_pos`](../l10n_fr_pdp_pos/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_ke`](../l10n_ke/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`lunch`](../lunch/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`onboarding`](../onboarding/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`product`](../product/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`resource`](../resource/overview.md), [`sale`](../sale/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sms`](../sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md), [`snailmail`](../snailmail/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`social_media`](../social_media/overview.md), [`spreadsheet_account`](../spreadsheet_account/overview.md), [`stock`](../stock/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`stock_sms`](../stock_sms/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md), [`website_mass_mailing`](../website_mass_mailing/overview.md), [`website_sale`](../website_sale/overview.md)
- `res.partner` — extended by [`account`](../account/overview.md), [`account_add_gln`](../account_add_gln/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`auth_signup`](../auth_signup/overview.md), [`base`](../base/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_vat`](../base_vat/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event`](../event/overview.md), [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`loyalty`](../loyalty/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`membership`](../membership/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`snailmail`](../snailmail/overview.md), [`stock`](../stock/overview.md), [`survey`](../survey/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_inherit`](../test_inherit/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md)
- `res.users` — extended by [`auth_ldap`](../auth_ldap/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`auth_password_policy`](../auth_password_policy/overview.md), [`auth_signup`](../auth_signup/overview.md), [`auth_totp`](../auth_totp/overview.md), [`auth_totp_mail`](../auth_totp_mail/overview.md), [`auth_totp_mail_enforce`](../auth_totp_mail_enforce/overview.md), [`auth_totp_portal`](../auth_totp_portal/overview.md), [`base`](../base/overview.md), [`base_import`](../base_import/overview.md), [`base_setup`](../base_setup/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`digest`](../digest/overview.md), [`gamification`](../gamification/overview.md), [`google_calendar`](../google_calendar/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_gamification`](../hr_gamification/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_maintenance`](../hr_maintenance/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_skills`](../hr_skills/overview.md), [`im_livechat`](../im_livechat/overview.md), [`im_livechat_mail_bot`](../im_livechat_mail_bot/overview.md), [`lunch`](../lunch/overview.md), [`mail_bot`](../mail_bot/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`microsoft_account`](../microsoft_account/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md), [`phone_validation`](../phone_validation/overview.md), [`resource`](../resource/overview.md), [`sale_crm`](../sale_crm/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sales_team`](../sales_team/overview.md), [`stock`](../stock/overview.md), [`test_uninstall`](../test_uninstall/overview.md), [`web`](../web/overview.md), [`web_unsplash`](../web_unsplash/overview.md), [`website`](../website/overview.md), [`website_forum`](../website_forum/overview.md), [`website_profile`](../website_profile/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md)
- `res.users.settings.volumes`
- `template.reset.mixin` — extended by [`sms`](../sms/overview.md)
- Extends `avatar.mixin` — defined by [`base`](../base/overview.md)
- Extends `base` — defined by [`base`](../base/overview.md)
- Extends `base.module.uninstall` — defined by [`base`](../base/overview.md)
- Extends `base.partner.merge.automatic.wizard` — defined by [`base`](../base/overview.md)
- Extends `bus.presence` — defined by [`bus`](../bus/overview.md)
- Extends `discuss.channel` — defined by [`im_livechat`](../im_livechat/overview.md)
- Extends `discuss.channel.member` — framework/dynamic owner
- Extends `ir.actions.act_window.view` — defined by [`base`](../base/overview.md)
- Extends `ir.actions.server` — defined by [`base`](../base/overview.md), [`sms`](../sms/overview.md), [`website`](../website/overview.md)
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)
- Extends `ir.config_parameter` — defined by [`base`](../base/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `ir.mail_server` — defined by [`base`](../base/overview.md), [`google_gmail`](../google_gmail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md)
- Extends `ir.model` — defined by [`base`](../base/overview.md), [`website`](../website/overview.md)
- Extends `ir.model.fields` — defined by [`base`](../base/overview.md), [`website`](../website/overview.md)
- Extends `ir.qweb` — defined by [`base`](../base/overview.md)
- Extends `ir.ui.view` — defined by [`website`](../website/overview.md)
- Extends `ir.websocket` — defined by [`bus`](../bus/overview.md)
- Extends `mail.activity.mixin` — framework/dynamic owner
- Extends `mail.alias` — framework/dynamic owner
- Extends `mail.alias.mixin.optional` — framework/dynamic owner
- Extends `mail.composer.mixin` — framework/dynamic owner
- Extends `mail.message` — framework/dynamic owner
- Extends `mail.notification` — framework/dynamic owner
- Extends `mail.render.mixin` — framework/dynamic owner
- Extends `mail.thread` — framework/dynamic owner
- Extends `mail.thread.blacklist` — framework/dynamic owner
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.groups` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `res.users.settings` — defined by [`base`](../base/overview.md)
- Extends `template.reset.mixin` — framework/dynamic owner

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from, model_extended_by
- [`module.account_add_gln`](../../../agents/modules/generated/account_add_gln.yaml) — model_extended_by
- [`module.account_audit_trail`](../../../agents/modules/generated/account_audit_trail.yaml) — model_extended_by
- [`module.account_check_printing`](../../../agents/modules/generated/account_check_printing.yaml) — model_extended_by
- [`module.account_edi_proxy_client`](../../../agents/modules/generated/account_edi_proxy_client.yaml) — model_extended_by
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — model_extended_by
- [`module.account_lock`](../../../agents/modules/generated/account_lock.yaml) — model_extended_by
- [`module.account_peppol`](../../../agents/modules/generated/account_peppol.yaml) — model_extended_by
- [`module.account_peppol_response`](../../../agents/modules/generated/account_peppol_response.yaml) — model_extended_by
- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — model_extended_by, required_by
- [`module.auth_ldap`](../../../agents/modules/generated/auth_ldap.yaml) — model_extended_by
- [`module.auth_oauth`](../../../agents/modules/generated/auth_oauth.yaml) — model_extended_by
- [`module.auth_password_policy`](../../../agents/modules/generated/auth_password_policy.yaml) — model_extended_by
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — model_extended_by, required_by
- [`module.auth_totp`](../../../agents/modules/generated/auth_totp.yaml) — model_extended_by
- [`module.auth_totp_mail`](../../../agents/modules/generated/auth_totp_mail.yaml) — model_extended_by, required_by
- [`module.auth_totp_mail_enforce`](../../../agents/modules/generated/auth_totp_mail_enforce.yaml) — model_extended_by, required_by
- [`module.auth_totp_portal`](../../../agents/modules/generated/auth_totp_portal.yaml) — model_extended_by
- [`module.barcodes`](../../../agents/modules/generated/barcodes.yaml) — model_extended_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.base_address_extended`](../../../agents/modules/generated/base_address_extended.yaml) — model_extended_by
- [`module.base_automation`](../../../agents/modules/generated/base_automation.yaml) — required_by
- [`module.base_geolocalize`](../../../agents/modules/generated/base_geolocalize.yaml) — model_extended_by
- [`module.base_import`](../../../agents/modules/generated/base_import.yaml) — model_extended_by
- [`module.base_install_request`](../../../agents/modules/generated/base_install_request.yaml) — required_by
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on, model_extended_by
- [`module.base_vat`](../../../agents/modules/generated/base_vat.yaml) — model_extended_by
- [`module.bus`](../../../agents/modules/generated/bus.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — model_extended_by, required_by
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from, model_extended_by, required_by
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from, model_extended_by, required_by
- [`module.crm_livechat`](../../../agents/modules/generated/crm_livechat.yaml) — model_extended_by
- [`module.data_recycle`](../../../agents/modules/generated/data_recycle.yaml) — required_by
- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — model_extended_by
- [`module.delivery_mondialrelay`](../../../agents/modules/generated/delivery_mondialrelay.yaml) — model_extended_by
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — model_extended_by, required_by
- [`module.event`](../../../agents/modules/generated/event.yaml) — model_extended_by, required_by
- [`module.event_booth`](../../../agents/modules/generated/event_booth.yaml) — model_extended_by
- [`module.fleet`](../../../agents/modules/generated/fleet.yaml) — model_extended_by, required_by
- [`module.gamification`](../../../agents/modules/generated/gamification.yaml) — model_extended_by, required_by
- [`module.google_calendar`](../../../agents/modules/generated/google_calendar.yaml) — model_extended_by
- [`module.google_gmail`](../../../agents/modules/generated/google_gmail.yaml) — extends_model_from, model_extended_by, required_by
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — model_extended_by, required_by
- [`module.hr_attendance`](../../../agents/modules/generated/hr_attendance.yaml) — model_extended_by
- [`module.hr_contract`](../../../agents/modules/generated/hr_contract.yaml) — model_extended_by
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — model_extended_by
- [`module.hr_fleet`](../../../agents/modules/generated/hr_fleet.yaml) — model_extended_by
- [`module.hr_gamification`](../../../agents/modules/generated/hr_gamification.yaml) — model_extended_by
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — model_extended_by
- [`module.hr_holidays_attendance`](../../../agents/modules/generated/hr_holidays_attendance.yaml) — model_extended_by
- [`module.hr_homeworking`](../../../agents/modules/generated/hr_homeworking.yaml) — model_extended_by
- [`module.hr_maintenance`](../../../agents/modules/generated/hr_maintenance.yaml) — model_extended_by
- [`module.hr_presence`](../../../agents/modules/generated/hr_presence.yaml) — model_extended_by
- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — model_extended_by
- [`module.hr_skills`](../../../agents/modules/generated/hr_skills.yaml) — model_extended_by
- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — model_extended_by
- [`module.iap_mail`](../../../agents/modules/generated/iap_mail.yaml) — required_by
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — extends_model_from, model_extended_by, required_by
- [`module.im_livechat_mail_bot`](../../../agents/modules/generated/im_livechat_mail_bot.yaml) — model_extended_by
- [`module.l10n_anz_ubl_pint`](../../../agents/modules/generated/l10n_anz_ubl_pint.yaml) — model_extended_by
- [`module.l10n_ar`](../../../agents/modules/generated/l10n_ar.yaml) — model_extended_by
- [`module.l10n_ar_pos`](../../../agents/modules/generated/l10n_ar_pos.yaml) — model_extended_by
- [`module.l10n_ar_withholding`](../../../agents/modules/generated/l10n_ar_withholding.yaml) — model_extended_by
- [`module.l10n_be`](../../../agents/modules/generated/l10n_be.yaml) — model_extended_by
- [`module.l10n_br`](../../../agents/modules/generated/l10n_br.yaml) — model_extended_by
- [`module.l10n_ca`](../../../agents/modules/generated/l10n_ca.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from, model_extended_by
- [`module.l10n_co`](../../../agents/modules/generated/l10n_co.yaml) — model_extended_by
- [`module.l10n_cz`](../../../agents/modules/generated/l10n_cz.yaml) — model_extended_by
- [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml) — model_extended_by
- [`module.l10n_dk`](../../../agents/modules/generated/l10n_dk.yaml) — model_extended_by
- [`module.l10n_dk_oioubl`](../../../agents/modules/generated/l10n_dk_oioubl.yaml) — model_extended_by
- [`module.l10n_ec`](../../../agents/modules/generated/l10n_ec.yaml) — model_extended_by
- [`module.l10n_eg_edi_eta`](../../../agents/modules/generated/l10n_eg_edi_eta.yaml) — model_extended_by
- [`module.l10n_es`](../../../agents/modules/generated/l10n_es.yaml) — model_extended_by
- [`module.l10n_es_edi_facturae`](../../../agents/modules/generated/l10n_es_edi_facturae.yaml) — model_extended_by
- [`module.l10n_es_edi_facturae_adm_centers`](../../../agents/modules/generated/l10n_es_edi_facturae_adm_centers.yaml) — model_extended_by
- [`module.l10n_es_edi_sii`](../../../agents/modules/generated/l10n_es_edi_sii.yaml) — model_extended_by
- [`module.l10n_es_edi_tbai`](../../../agents/modules/generated/l10n_es_edi_tbai.yaml) — model_extended_by
- [`module.l10n_es_edi_verifactu`](../../../agents/modules/generated/l10n_es_edi_verifactu.yaml) — model_extended_by
- [`module.l10n_es_edi_verifactu_pos`](../../../agents/modules/generated/l10n_es_edi_verifactu_pos.yaml) — model_extended_by
- [`module.l10n_es_pos_tbai`](../../../agents/modules/generated/l10n_es_pos_tbai.yaml) — model_extended_by
- [`module.l10n_eu_oss`](../../../agents/modules/generated/l10n_eu_oss.yaml) — model_extended_by
- [`module.l10n_fr`](../../../agents/modules/generated/l10n_fr.yaml) — model_extended_by
- [`module.l10n_fr_hr_holidays`](../../../agents/modules/generated/l10n_fr_hr_holidays.yaml) — model_extended_by
- [`module.l10n_fr_pdp`](../../../agents/modules/generated/l10n_fr_pdp.yaml) — model_extended_by
- [`module.l10n_fr_pdp_pos`](../../../agents/modules/generated/l10n_fr_pdp_pos.yaml) — model_extended_by
- [`module.l10n_fr_pos_cert`](../../../agents/modules/generated/l10n_fr_pos_cert.yaml) — model_extended_by
- [`module.l10n_hu`](../../../agents/modules/generated/l10n_hu.yaml) — model_extended_by
- [`module.l10n_hu_edi`](../../../agents/modules/generated/l10n_hu_edi.yaml) — model_extended_by
- [`module.l10n_id_efaktur`](../../../agents/modules/generated/l10n_id_efaktur.yaml) — model_extended_by
- [`module.l10n_id_efaktur_coretax`](../../../agents/modules/generated/l10n_id_efaktur_coretax.yaml) — model_extended_by
- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — model_extended_by
- [`module.l10n_in_edi`](../../../agents/modules/generated/l10n_in_edi.yaml) — model_extended_by
- [`module.l10n_in_edi_ewaybill`](../../../agents/modules/generated/l10n_in_edi_ewaybill.yaml) — model_extended_by
- [`module.l10n_in_ewaybill_stock`](../../../agents/modules/generated/l10n_in_ewaybill_stock.yaml) — model_extended_by
- [`module.l10n_in_withholding`](../../../agents/modules/generated/l10n_in_withholding.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from, model_extended_by
- [`module.l10n_it_edi_doi`](../../../agents/modules/generated/l10n_it_edi_doi.yaml) — model_extended_by
- [`module.l10n_jo_edi`](../../../agents/modules/generated/l10n_jo_edi.yaml) — model_extended_by
- [`module.l10n_jo_edi_extended`](../../../agents/modules/generated/l10n_jo_edi_extended.yaml) — model_extended_by
- [`module.l10n_jp_ubl_pint`](../../../agents/modules/generated/l10n_jp_ubl_pint.yaml) — model_extended_by
- [`module.l10n_ke`](../../../agents/modules/generated/l10n_ke.yaml) — model_extended_by
- [`module.l10n_ke_edi_tremol`](../../../agents/modules/generated/l10n_ke_edi_tremol.yaml) — model_extended_by
- [`module.l10n_latam_base`](../../../agents/modules/generated/l10n_latam_base.yaml) — model_extended_by
- [`module.l10n_latam_invoice_document`](../../../agents/modules/generated/l10n_latam_invoice_document.yaml) — model_extended_by
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
- [`module.l10n_ro_efactura`](../../../agents/modules/generated/l10n_ro_efactura.yaml) — model_extended_by
- [`module.l10n_ro_efactura_synchronize`](../../../agents/modules/generated/l10n_ro_efactura_synchronize.yaml) — model_extended_by
- [`module.l10n_rs_edi`](../../../agents/modules/generated/l10n_rs_edi.yaml) — model_extended_by
- [`module.l10n_sa_edi`](../../../agents/modules/generated/l10n_sa_edi.yaml) — model_extended_by
- [`module.l10n_se`](../../../agents/modules/generated/l10n_se.yaml) — model_extended_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from, model_extended_by
- [`module.l10n_sg_ubl_pint`](../../../agents/modules/generated/l10n_sg_ubl_pint.yaml) — model_extended_by
- [`module.l10n_sk`](../../../agents/modules/generated/l10n_sk.yaml) — model_extended_by
- [`module.l10n_th`](../../../agents/modules/generated/l10n_th.yaml) — model_extended_by
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from, model_extended_by
- [`module.l10n_tr_nilvera_edispatch`](../../../agents/modules/generated/l10n_tr_nilvera_edispatch.yaml) — model_extended_by
- [`module.l10n_uy`](../../../agents/modules/generated/l10n_uy.yaml) — model_extended_by
- [`module.l10n_vn_edi_viettel`](../../../agents/modules/generated/l10n_vn_edi_viettel.yaml) — model_extended_by
- [`module.link_tracker`](../../../agents/modules/generated/link_tracker.yaml) — model_extended_by, required_by
- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — model_extended_by
- [`module.lunch`](../../../agents/modules/generated/lunch.yaml) — model_extended_by, required_by
- [`module.mail_bot`](../../../agents/modules/generated/mail_bot.yaml) — model_extended_by, required_by
- [`module.mail_group`](../../../agents/modules/generated/mail_group.yaml) — model_extended_by, required_by
- [`module.mail_plugin`](../../../agents/modules/generated/mail_plugin.yaml) — model_extended_by
- [`module.maintenance`](../../../agents/modules/generated/maintenance.yaml) — model_extended_by, required_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from, model_extended_by, required_by
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from, model_extended_by
- [`module.membership`](../../../agents/modules/generated/membership.yaml) — model_extended_by
- [`module.microsoft_account`](../../../agents/modules/generated/microsoft_account.yaml) — model_extended_by
- [`module.microsoft_calendar`](../../../agents/modules/generated/microsoft_calendar.yaml) — model_extended_by
- [`module.microsoft_outlook`](../../../agents/modules/generated/microsoft_outlook.yaml) — extends_model_from, model_extended_by, required_by
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — model_extended_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — model_extended_by
- [`module.mrp_subcontracting_dropshipping`](../../../agents/modules/generated/mrp_subcontracting_dropshipping.yaml) — model_extended_by
- [`module.onboarding`](../../../agents/modules/generated/onboarding.yaml) — model_extended_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from, model_extended_by
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — model_extended_by
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from, model_extended_by, required_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — model_extended_by, required_by
- [`module.portal_rating`](../../../agents/modules/generated/portal_rating.yaml) — model_extended_by
- [`module.privacy_lookup`](../../../agents/modules/generated/privacy_lookup.yaml) — model_extended_by, required_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — model_extended_by, required_by
- [`module.project`](../../../agents/modules/generated/project.yaml) — model_extended_by, required_by
- [`module.project_timesheet_holidays`](../../../agents/modules/generated/project_timesheet_holidays.yaml) — model_extended_by
- [`module.project_todo`](../../../agents/modules/generated/project_todo.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from, model_extended_by
- [`module.purchase_requisition`](../../../agents/modules/generated/purchase_requisition.yaml) — model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — model_extended_by
- [`module.rating`](../../../agents/modules/generated/rating.yaml) — model_extended_by, required_by
- [`module.repair`](../../../agents/modules/generated/repair.yaml) — model_extended_by
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — model_extended_by
- [`module.sale_crm`](../../../agents/modules/generated/sale_crm.yaml) — model_extended_by
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — model_extended_by
- [`module.sale_order_extension`](../../../agents/modules/generated/sale_order_extension.yaml) — required_by
- [`module.sale_pdf_quote_builder`](../../../agents/modules/generated/sale_pdf_quote_builder.yaml) — model_extended_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by
- [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml) — model_extended_by, required_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from, model_extended_by, required_by
- [`module.sms_twilio`](../../../agents/modules/generated/sms_twilio.yaml) — model_extended_by
- [`module.snailmail`](../../../agents/modules/generated/snailmail.yaml) — model_extended_by, required_by
- [`module.snailmail_account`](../../../agents/modules/generated/snailmail_account.yaml) — model_extended_by
- [`module.social_media`](../../../agents/modules/generated/social_media.yaml) — model_extended_by
- [`module.spreadsheet_account`](../../../agents/modules/generated/spreadsheet_account.yaml) — model_extended_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — model_extended_by
- [`module.stock_dropshipping`](../../../agents/modules/generated/stock_dropshipping.yaml) — model_extended_by
- [`module.stock_landed_costs`](../../../agents/modules/generated/stock_landed_costs.yaml) — model_extended_by
- [`module.stock_picking_batch`](../../../agents/modules/generated/stock_picking_batch.yaml) — model_extended_by
- [`module.stock_sms`](../../../agents/modules/generated/stock_sms.yaml) — model_extended_by
- [`module.survey`](../../../agents/modules/generated/survey.yaml) — model_extended_by, required_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from, model_extended_by
- [`module.test_base_automation`](../../../agents/modules/generated/test_base_automation.yaml) — model_extended_by
- [`module.test_discuss_full`](../../../agents/modules/generated/test_discuss_full.yaml) — required_by
- [`module.test_inherit`](../../../agents/modules/generated/test_inherit.yaml) — model_extended_by
- [`module.test_mail`](../../../agents/modules/generated/test_mail.yaml) — model_extended_by, required_by
- [`module.test_mail_full`](../../../agents/modules/generated/test_mail_full.yaml) — model_extended_by, required_by
- [`module.test_mail_sms`](../../../agents/modules/generated/test_mail_sms.yaml) — model_extended_by, required_by
- [`module.test_mass_mailing`](../../../agents/modules/generated/test_mass_mailing.yaml) — model_extended_by
- [`module.test_uninstall`](../../../agents/modules/generated/test_uninstall.yaml) — model_extended_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — model_extended_by
- [`module.web_tour`](../../../agents/modules/generated/web_tour.yaml) — depends_on
- [`module.web_unsplash`](../../../agents/modules/generated/web_unsplash.yaml) — model_extended_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from, model_extended_by, required_by
- [`module.website_blog`](../../../agents/modules/generated/website_blog.yaml) — model_extended_by
- [`module.website_crm_livechat`](../../../agents/modules/generated/website_crm_livechat.yaml) — model_extended_by
- [`module.website_crm_partner_assign`](../../../agents/modules/generated/website_crm_partner_assign.yaml) — model_extended_by
- [`module.website_customer`](../../../agents/modules/generated/website_customer.yaml) — model_extended_by
- [`module.website_event_exhibitor`](../../../agents/modules/generated/website_event_exhibitor.yaml) — model_extended_by
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — model_extended_by
- [`module.website_forum`](../../../agents/modules/generated/website_forum.yaml) — model_extended_by
- [`module.website_livechat`](../../../agents/modules/generated/website_livechat.yaml) — model_extended_by
- [`module.website_mail`](../../../agents/modules/generated/website_mail.yaml) — model_extended_by, required_by
- [`module.website_mass_mailing`](../../../agents/modules/generated/website_mass_mailing.yaml) — model_extended_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from, model_extended_by
- [`module.website_profile`](../../../agents/modules/generated/website_profile.yaml) — model_extended_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by
- [`module.website_sale_mondialrelay`](../../../agents/modules/generated/website_sale_mondialrelay.yaml) — model_extended_by
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — model_extended_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — model_extended_by

## Regression impact checklist

- Review 42 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`account_add_gln`](../account_add_gln/overview.md), [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_proxy_client`](../account_edi_proxy_client/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_lock`](../account_lock/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`analytic`](../analytic/overview.md), [`auth_ldap`](../auth_ldap/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`auth_password_policy`](../auth_password_policy/overview.md), [`auth_signup`](../auth_signup/overview.md), [`auth_totp`](../auth_totp/overview.md), [`auth_totp_mail`](../auth_totp_mail/overview.md), [`auth_totp_mail_enforce`](../auth_totp_mail_enforce/overview.md), [`auth_totp_portal`](../auth_totp_portal/overview.md), [`barcodes`](../barcodes/overview.md), [`base`](../base/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_import`](../base_import/overview.md), [`base_setup`](../base_setup/overview.md), [`base_vat`](../base_vat/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`crm_livechat`](../crm_livechat/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`digest`](../digest/overview.md), [`event`](../event/overview.md), [`event_booth`](../event_booth/overview.md), [`fleet`](../fleet/overview.md), [`gamification`](../gamification/overview.md), [`google_calendar`](../google_calendar/overview.md), [`google_gmail`](../google_gmail/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_gamification`](../hr_gamification/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_maintenance`](../hr_maintenance/overview.md), [`hr_presence`](../hr_presence/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_skills`](../hr_skills/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`im_livechat`](../im_livechat/overview.md), [`im_livechat_mail_bot`](../im_livechat_mail_bot/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_eu_oss`](../l10n_eu_oss/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_hr_holidays`](../l10n_fr_hr_holidays/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_fr_pdp_pos`](../l10n_fr_pdp_pos/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_ewaybill_stock`](../l10n_in_ewaybill_stock/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_ke`](../l10n_ke/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`link_tracker`](../link_tracker/overview.md), [`loyalty`](../loyalty/overview.md), [`lunch`](../lunch/overview.md), [`mail_bot`](../mail_bot/overview.md), [`mail_group`](../mail_group/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`maintenance`](../maintenance/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`membership`](../membership/overview.md), [`microsoft_account`](../microsoft_account/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md), [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`onboarding`](../onboarding/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`portal_rating`](../portal_rating/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`project_todo`](../project_todo/overview.md), [`purchase`](../purchase/overview.md), [`purchase_requisition`](../purchase_requisition/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`rating`](../rating/overview.md), [`repair`](../repair/overview.md), [`resource`](../resource/overview.md), [`sale`](../sale/overview.md), [`sale_crm`](../sale_crm/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md), [`snailmail`](../snailmail/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`social_media`](../social_media/overview.md), [`spreadsheet_account`](../spreadsheet_account/overview.md), [`stock`](../stock/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md), [`stock_sms`](../stock_sms/overview.md), [`survey`](../survey/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_base_automation`](../test_base_automation/overview.md), [`test_inherit`](../test_inherit/overview.md), [`test_mail`](../test_mail/overview.md), [`test_mail_full`](../test_mail_full/overview.md), [`test_mail_sms`](../test_mail_sms/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md), [`test_uninstall`](../test_uninstall/overview.md), [`web`](../web/overview.md), [`web_unsplash`](../web_unsplash/overview.md), [`website`](../website/overview.md), [`website_blog`](../website_blog/overview.md), [`website_crm_livechat`](../website_crm_livechat/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_forum`](../website_forum/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_mail`](../website_mail/overview.md), [`website_mass_mailing`](../website_mass_mailing/overview.md), [`website_partner`](../website_partner/overview.md), [`website_profile`](../website_profile/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`bus`](../bus/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`google_gmail`](../google_gmail/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-10-sale-servicenow-patterns`](../../conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-13-ho-partial-registry-landing-repair`](../../conversations/2026-08-13-ho-partial-registry-landing-repair.json)
