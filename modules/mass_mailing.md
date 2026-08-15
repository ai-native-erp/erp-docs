---
layout: page
title: "Email Marketing (mass_mailing)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mass_mailing/
nav_order: 0
---
# Email Marketing — `mass_mailing`

**Source:** [`agents/modules/generated/mass_mailing.yaml`](../../agents/modules/generated/mass_mailing.yaml) · **Wiki:** [`knowledge/modules/mass_mailing/overview.md`](../../knowledge/modules/mass_mailing/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mass_mailing</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Email Marketing</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mass_mailing</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mass_mailing"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Design, send and track emails

## Direct dependencies

[`contacts`](contacts.md), [`digest`](digest.md), [`link_tracker`](link_tracker.md), [`mail`](mail.md), [`social_media`](social_media.md), [`utm`](utm.md), [`web_editor`](web_editor.md), [`web_tour`](web_tour.md)

## Reverse dependencies (modules that depend on this)

[`mass_mailing_crm`](mass_mailing_crm.md), [`mass_mailing_event`](mass_mailing_event.md), [`mass_mailing_event_sms`](mass_mailing_event_sms.md), [`mass_mailing_event_track`](mass_mailing_event_track.md), [`mass_mailing_event_track_sms`](mass_mailing_event_track_sms.md), [`mass_mailing_sale`](mass_mailing_sale.md), [`mass_mailing_slides`](mass_mailing_slides.md), [`mass_mailing_sms`](mass_mailing_sms.md), [`mass_mailing_themes`](mass_mailing_themes.md), [`test_mail_full`](test_mail_full.md), [`test_mass_mailing`](test_mass_mailing.md), [`website_mass_mailing`](website_mass_mailing.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.mail_server</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.contact</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.contact.import</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.contact.to.list</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.filter</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.list</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.list.merge</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.mailing</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.mailing.schedule.date</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.mailing.test</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.subscription</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.subscription.optout</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.trace</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.trace.report</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">defined by <code>mass_mailing</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>ir.mail_server</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>ir.model</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>link.tracker</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>link.tracker.click</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mail.blacklist</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mail.compose.message</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mail.mail</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mail.render.mixin</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mail.thread.blacklist</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>utm.campaign</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>utm.medium</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>utm.source</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
<div class="model"><div class="name"><code>utm.source.mixin</code></div><div class="role">extended by <code>mass_mailing</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.auth_ldap` | model_extended_by | `agents/modules/generated/auth_ldap.yaml` |
| `module.auth_oauth` | model_extended_by | `agents/modules/generated/auth_oauth.yaml` |
| `module.auth_password_policy` | model_extended_by | `agents/modules/generated/auth_password_policy.yaml` |
| `module.auth_signup` | model_extended_by | `agents/modules/generated/auth_signup.yaml` |
| `module.auth_totp` | model_extended_by | `agents/modules/generated/auth_totp.yaml` |
| `module.auth_totp_mail` | model_extended_by | `agents/modules/generated/auth_totp_mail.yaml` |
| `module.auth_totp_mail_enforce` | model_extended_by | `agents/modules/generated/auth_totp_mail_enforce.yaml` |
| `module.auth_totp_portal` | model_extended_by | `agents/modules/generated/auth_totp_portal.yaml` |
| `module.base` | extends_model_from, model_extended_by | `agents/modules/generated/base.yaml` |

## Full wiki excerpt

- SME owner: [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml)
- Domain: `marketing_events`
- Category: Marketing/Email Marketing
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mass_mailing)
- Direct dependencies: [`contacts`](../contacts/overview.md), [`digest`](../digest/overview.md), [`link_tracker`](../link_tracker/overview.md), [`mail`](../mail/overview.md), [`social_media`](../social_media/overview.md), [`utm`](../utm/overview.md), [`web_editor`](../web_editor/overview.md), [`web_tour`](../web_tour/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`mass_mailing_crm`](../mass_mailing_crm/overview.md), [`mass_mailing_event`](../mass_mailing_event/overview.md), [`mass_mailing_event_sms`](../mass_mailing_event_sms/overview.md), [`mass_mailing_event_track`](../mass_mailing_event_track/overview.md), [`mass_mailing_event_track_sms`](../mass_mailing_event_track_sms/overview.md), [`mass_mailing_sale`](../mass_mailing_sale/overview.md), [`mass_mailing_slides`](../mass_mailing_slides/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`mass_mailing_themes`](../mass_mailing_themes/overview.md), [`test_mail_full`](../test_mail_full/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md), [`website_mass_mailing`](../website_mass_mailing/overview.md)
- Impact graph: [`module:mass_mailing`](../../impact-graph.json)

## Purpose

Design, send and track emails

## Model relationships

- `ir.mail_server` — extended by [`google_gmail`](../google_gmail/overview.md), [`mail`](../mail/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md)
- `mailing.contact` — extended by [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- `mailing.contact.import`
- `mailing.contact.to.list`
- `mailing.filter`
- `mailing.list` — extended by [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- `mailing.list.merge`
- `mailing.mailing` — extended by [`mass_mailing_crm`](../mass_mailing_crm/overview.md), [`mass_mailing_sale`](../mass_mailing_sale/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- `mailing.mailing.schedule.date`
- `mailing.mailing.test`
- `mailing.subscription`
- `mailing.subscription.optout`
- `mailing.trace` — extended by [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- `mailing.trace.report`
- `res.users` — extended by [`auth_ldap`](../auth_ldap/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`auth_password_policy`](../auth_password_policy/overview.md), [`auth_signup`](../auth_signup/overview.md), [`auth_totp`](../auth_totp/overview.md), [`auth_totp_mail`](../auth_totp_mail/overview.md), [`auth_totp_mail_enforce`](../auth_totp_mail_enforce/overview.md), [`auth_totp_portal`](../auth_totp_portal/overview.md), [`base`](../base/overview.md), [`base_import`](../base_import/overview.md), [`base_setup`](../base_setup/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`digest`](../digest/overview.md), [`gamification`](../gamification/overview.md), [`google_calendar`](../google_calendar/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_gamification`](../hr_gamification/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_maintenance`](../hr_maintenance/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_skills`](../hr_skills/overview.md), [`im_livechat`](../im_livechat/overview.md), [`im_livechat_mail_bot`](../im_livechat_mail_bot/overview.md), [`lunch`](../lunch/overview.md), [`mail`](../mail/overview.md), [`mail_bot`](../mail_bot/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`microsoft_account`](../microsoft_account/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md), [`phone_validation`](../phone_validation/overview.md), [`resource`](../resource/overview.md), [`sale_crm`](../sale_crm/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sales_team`](../sales_team/overview.md), [`stock`](../stock/overview.md), [`test_uninstall`](../test_uninstall/overview.md), [`web`](../web/overview.md), [`web_unsplash`](../web_unsplash/overview.md), [`website`](../website/overview.md), [`website_forum`](../website_forum/overview.md), [`website_profile`](../website_profile/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `ir.mail_server` — defined by [`base`](../base/overview.md), [`google_gmail`](../google_gmail/overview.md), [`mail`](../mail/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md)
- Extends `ir.model` — defined by [`base`](../base/overview.md), [`website`](../website/overview.md)
- Extends `link.tracker` — defined by [`link_tracker`](../link_tracker/overview.md)
- Extends `link.tracker.click` — defined by [`link_tracker`](../link_tracker/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.blacklist` — defined by [`mail`](../mail/overview.md)
- Extends `mail.compose.message` — defined by [`mail`](../mail/overview.md)
- Extends `mail.mail` — defined by [`mail`](../mail/overview.md)
- Extends `mail.render.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.blacklist` — defined by [`mail`](../mail/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `utm.campaign` — defined by [`utm`](../utm/overview.md)
- Extends `utm.medium` — defined by [`utm`](../utm/overview.md)
- Extends `utm.source` — defined by [`utm`](../utm/overview.md)
- Extends `utm.source.mixin` — defined by [`utm`](../utm/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.auth_ldap`](../../../agents/modules/generated/auth_ldap.yaml) — model_extended_by
- [`module.auth_oauth`](../../../agents/modules/generated/auth_oauth.yaml) — model_extended_by
- [`module.auth_password_policy`](../../../agents/modules/generated/auth_password_policy.yaml) — model_extended_by
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — model_extended_by
- [`module.auth_totp`](../../../agents/modules/generated/auth_totp.yaml) — model_extended_by
- [`module.auth_totp_mail`](../../../agents/modules/generated/auth_totp_mail.yaml) — model_extended_by
- [`module.auth_totp_mail_enforce`](../../../agents/modules/generated/auth_totp_mail_enforce.yaml) — model_extended_by
- [`module.auth_totp_portal`](../../../agents/modules/generated/auth_totp_portal.yaml) — model_extended_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from, model_extended_by
- [`module.base_import`](../../../agents/modules/generated/base_import.yaml) — model_extended_by
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — model_extended_by
- [`module.bus`](../../../agents/modules/generated/bus.yaml) — model_extended_by
- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — model_extended_by
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from, model_extended_by
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — depends_on, model_extended_by
- [`module.gamification`](../../../agents/modules/generated/gamification.yaml) — model_extended_by
- [`module.google_calendar`](../../../agents/modules/generated/google_calendar.yaml) — model_extended_by
- [`module.google_gmail`](../../../agents/modules/generated/google_gmail.yaml) — extends_model_from, model_extended_by
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — model_extended_by
- [`module.hr_attendance`](../../../agents/modules/generated/hr_attendance.yaml) — model_extended_by
- [`module.hr_contract`](../../../agents/modules/generated/hr_contract.yaml) — model_extended_by
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — model_extended_by
- [`module.hr_fleet`](../../../agents/modules/generated/hr_fleet.yaml) — model_extended_by
- [`module.hr_gamification`](../../../agents/modules/generated/hr_gamification.yaml) — model_extended_by
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — model_extended_by
- [`module.hr_holidays_attendance`](../../../agents/modules/generated/hr_holidays_attendance.yaml) — model_extended_by
- [`module.hr_homeworking`](../../../agents/modules/generated/hr_homeworking.yaml) — model_extended_by
- [`module.hr_maintenance`](../../../agents/modules/generated/hr_maintenance.yaml) — model_extended_by
- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — model_extended_by
- [`module.hr_skills`](../../../agents/modules/generated/hr_skills.yaml) — model_extended_by
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — model_extended_by
- [`module.im_livechat_mail_bot`](../../../agents/modules/generated/im_livechat_mail_bot.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.link_tracker`](../../../agents/modules/generated/link_tracker.yaml) — depends_on, extends_model_from
- [`module.lunch`](../../../agents/modules/generated/lunch.yaml) — model_extended_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.mail_bot`](../../../agents/modules/generated/mail_bot.yaml) — model_extended_by
- [`module.mass_mailing_crm`](../../../agents/modules/generated/mass_mailing_crm.yaml) — model_extended_by, required_by
- [`module.mass_mailing_event`](../../../agents/modules/generated/mass_mailing_event.yaml) — required_by
- [`module.mass_mailing_event_sms`](../../../agents/modules/generated/mass_mailing_event_sms.yaml) — required_by
- [`module.mass_mailing_event_track`](../../../agents/modules/generated/mass_mailing_event_track.yaml) — required_by
- [`module.mass_mailing_event_track_sms`](../../../agents/modules/generated/mass_mailing_event_track_sms.yaml) — required_by
- [`module.mass_mailing_sale`](../../../agents/modules/generated/mass_mailing_sale.yaml) — model_extended_by, required_by
- [`module.mass_mailing_slides`](../../../agents/modules/generated/mass_mailing_slides.yaml) — required_by
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from, model_extended_by, required_by
- [`module.mass_mailing_themes`](../../../agents/modules/generated/mass_mailing_themes.yaml) — required_by
- [`module.microsoft_account`](../../../agents/modules/generated/microsoft_account.yaml) — model_extended_by
- [`module.microsoft_calendar`](../../../agents/modules/generated/microsoft_calendar.yaml) — model_extended_by
- [`module.microsoft_outlook`](../../../agents/modules/generated/microsoft_outlook.yaml) — extends_model_from, model_extended_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from, model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — model_extended_by
- [`module.sale_crm`](../../../agents/modules/generated/sale_crm.yaml) — model_extended_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by
- [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml) — model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.social_media`](../../../agents/modules/generated/social_media.yaml) — depends_on
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — model_extended_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.test_mail_full`](../../../agents/modules/generated/test_mail_full.yaml) — required_by
- [`module.test_mass_mailing`](../../../agents/modules/generated/test_mass_mailing.yaml) — required_by
- [`module.test_uninstall`](../../../agents/modules/generated/test_uninstall.yaml) — model_extended_by
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — depends_on, extends_model_from
- [`module.web`](../../../agents/modules/generated/web.yaml) — model_extended_by
- [`module.web_editor`](../../../agents/modules/generated/web_editor.yaml) — depends_on
- [`module.web_tour`](../../../agents/modules/generated/web_tour.yaml) — depends_on
- [`module.web_unsplash`](../../../agents/modules/generated/web_unsplash.yaml) — model_extended_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from, model_extended_by
- [`module.website_forum`](../../../agents/modules/generated/website_forum.yaml) — model_extended_by
- [`module.website_mass_mailing`](../../../agents/modules/generated/website_mass_mailing.yaml) — required_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_profile`](../../../agents/modules/generated/website_profile.yaml) — model_extended_by
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — model_extended_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — model_extended_by

## Regression impact checklist

- Review 12 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`auth_ldap`](../auth_ldap/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`auth_password_policy`](../auth_password_policy/overview.md), [`auth_signup`](../auth_signup/overview.md), [`auth_totp`](../auth_totp/overview.md), [`auth_totp_mail`](../auth_totp_mail/overview.md), [`auth_totp_mail_enforce`](../auth_totp_mail_enforce/overview.md), [`auth_totp_portal`](../auth_totp_portal/overview.md), [`base`](../base/overview.md), [`base_import`](../base_import/overview.md), [`base_setup`](../base_setup/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`digest`](../digest/overview.md), [`gamification`](../gamification/overview.md), [`google_calendar`](../google_calendar/overview.md), [`google_gmail`](../google_gmail/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_gamification`](../hr_gamification/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_maintenance`](../hr_maintenance/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_skills`](../hr_skills/overview.md), [`im_livechat`](../im_livechat/overview.md), [`im_livechat_mail_bot`](../im_livechat_mail_bot/overview.md), [`lunch`](../lunch/overview.md), [`mail`](../mail/overview.md), [`mail_bot`](../mail_bot/overview.md), [`mass_mailing_crm`](../mass_mailing_crm/overview.md), [`mass_mailing_sale`](../mass_mailing_sale/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`microsoft_account`](../microsoft_account/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md), [`phone_validation`](../phone_validation/overview.md), [`resource`](../resource/overview.md), [`sale_crm`](../sale_crm/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sales_team`](../sales_team/overview.md), [`stock`](../stock/overview.md), [`test_uninstall`](../test_uninstall/overview.md), [`web`](../web/overview.md), [`web_unsplash`](../web_unsplash/overview.md), [`website`](../website/overview.md), [`website_forum`](../website_forum/overview.md), [`website_profile`](../website_profile/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`google_gmail`](../google_gmail/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`link_tracker`](../link_tracker/overview.md), [`mail`](../mail/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`utm`](../utm/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
