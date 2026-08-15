---
layout: page
title: "Contacts (contacts)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/contacts/
nav_order: 0
---
# Contacts — `contacts`

**Source:** [`agents/modules/generated/contacts.yaml`](../../agents/modules/generated/contacts.yaml) · **Wiki:** [`knowledge/modules/contacts/overview.md`](../../knowledge/modules/contacts/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>contacts</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Contacts</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/contacts</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/contacts"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Centralize your address book

## Direct dependencies

[`base`](base.md), [`mail`](mail.md)

## Reverse dependencies (modules that depend on this)

[`base_address_extended`](base_address_extended.md), [`crm`](crm.md), [`l10n_cl`](l10n_cl.md), [`l10n_latam_base`](l10n_latam_base.md), [`mail_plugin`](mail_plugin.md), [`mass_mailing`](mass_mailing.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.users</code></div><div class="role">defined by <code>contacts</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>contacts</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.auth_ldap` | model_extended_by | `agents/modules/generated/auth_ldap.yaml` |
| `module.auth_oauth` | model_extended_by | `agents/modules/generated/auth_oauth.yaml` |
| `module.auth_password_policy` | model_extended_by | `agents/modules/generated/auth_password_policy.yaml` |
| `module.auth_signup` | model_extended_by | `agents/modules/generated/auth_signup.yaml` |
| `module.auth_totp` | model_extended_by | `agents/modules/generated/auth_totp.yaml` |
| `module.auth_totp_mail` | model_extended_by | `agents/modules/generated/auth_totp_mail.yaml` |
| `module.auth_totp_mail_enforce` | model_extended_by | `agents/modules/generated/auth_totp_mail_enforce.yaml` |
| `module.auth_totp_portal` | model_extended_by | `agents/modules/generated/auth_totp_portal.yaml` |
| `module.base` | depends_on, extends_model_from, model_extended_by | `agents/modules/generated/base.yaml` |
| `module.base_address_extended` | required_by | `agents/modules/generated/base_address_extended.yaml` |

## Full wiki excerpt

- SME owner: [`module.contacts`](../../../agents/modules/generated/contacts.yaml)
- Domain: `sales_crm`
- Category: Sales/CRM
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/contacts)
- Direct dependencies: [`base`](../base/overview.md), [`mail`](../mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`base_address_extended`](../base_address_extended/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`mass_mailing`](../mass_mailing/overview.md)
- Impact graph: [`module:contacts`](../../impact-graph.json)

## Purpose

Centralize your address book

## Model relationships

- `res.users` — extended by [`auth_ldap`](../auth_ldap/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`auth_password_policy`](../auth_password_policy/overview.md), [`auth_signup`](../auth_signup/overview.md), [`auth_totp`](../auth_totp/overview.md), [`auth_totp_mail`](../auth_totp_mail/overview.md), [`auth_totp_mail_enforce`](../auth_totp_mail_enforce/overview.md), [`auth_totp_portal`](../auth_totp_portal/overview.md), [`base`](../base/overview.md), [`base_import`](../base_import/overview.md), [`base_setup`](../base_setup/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md), [`digest`](../digest/overview.md), [`gamification`](../gamification/overview.md), [`google_calendar`](../google_calendar/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_gamification`](../hr_gamification/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_maintenance`](../hr_maintenance/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_skills`](../hr_skills/overview.md), [`im_livechat`](../im_livechat/overview.md), [`im_livechat_mail_bot`](../im_livechat_mail_bot/overview.md), [`lunch`](../lunch/overview.md), [`mail`](../mail/overview.md), [`mail_bot`](../mail_bot/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`microsoft_account`](../microsoft_account/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md), [`phone_validation`](../phone_validation/overview.md), [`resource`](../resource/overview.md), [`sale_crm`](../sale_crm/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sales_team`](../sales_team/overview.md), [`stock`](../stock/overview.md), [`test_uninstall`](../test_uninstall/overview.md), [`web`](../web/overview.md), [`web_unsplash`](../web_unsplash/overview.md), [`website`](../website/overview.md), [`website_forum`](../website_forum/overview.md), [`website_profile`](../website_profile/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.auth_ldap`](../../../agents/modules/generated/auth_ldap.yaml) — model_extended_by
- [`module.auth_oauth`](../../../agents/modules/generated/auth_oauth.yaml) — model_extended_by
- [`module.auth_password_policy`](../../../agents/modules/generated/auth_password_policy.yaml) — model_extended_by
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — model_extended_by
- [`module.auth_totp`](../../../agents/modules/generated/auth_totp.yaml) — model_extended_by
- [`module.auth_totp_mail`](../../../agents/modules/generated/auth_totp_mail.yaml) — model_extended_by
- [`module.auth_totp_mail_enforce`](../../../agents/modules/generated/auth_totp_mail_enforce.yaml) — model_extended_by
- [`module.auth_totp_portal`](../../../agents/modules/generated/auth_totp_portal.yaml) — model_extended_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.base_address_extended`](../../../agents/modules/generated/base_address_extended.yaml) — required_by
- [`module.base_import`](../../../agents/modules/generated/base_import.yaml) — model_extended_by
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — model_extended_by
- [`module.bus`](../../../agents/modules/generated/bus.yaml) — model_extended_by
- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — model_extended_by
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — model_extended_by, required_by
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — model_extended_by
- [`module.gamification`](../../../agents/modules/generated/gamification.yaml) — model_extended_by
- [`module.google_calendar`](../../../agents/modules/generated/google_calendar.yaml) — model_extended_by
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
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — required_by
- [`module.l10n_latam_base`](../../../agents/modules/generated/l10n_latam_base.yaml) — required_by
- [`module.lunch`](../../../agents/modules/generated/lunch.yaml) — model_extended_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.mail_bot`](../../../agents/modules/generated/mail_bot.yaml) — model_extended_by
- [`module.mail_plugin`](../../../agents/modules/generated/mail_plugin.yaml) — required_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from, model_extended_by, required_by
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from, model_extended_by
- [`module.microsoft_account`](../../../agents/modules/generated/microsoft_account.yaml) — model_extended_by
- [`module.microsoft_calendar`](../../../agents/modules/generated/microsoft_calendar.yaml) — model_extended_by
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — model_extended_by
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — model_extended_by
- [`module.sale_crm`](../../../agents/modules/generated/sale_crm.yaml) — model_extended_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by
- [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml) — model_extended_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — model_extended_by
- [`module.test_uninstall`](../../../agents/modules/generated/test_uninstall.yaml) — model_extended_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — model_extended_by
- [`module.web_unsplash`](../../../agents/modules/generated/web_unsplash.yaml) — model_extended_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — model_extended_by
- [`module.website_forum`](../../../agents/modules/generated/website_forum.yaml) — model_extended_by
- [`module.website_profile`](../../../agents/modules/generated/website_profile.yaml) — model_extended_by
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — model_extended_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — model_extended_by

## Regression impact checklist

- Review 6 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`auth_ldap`](../auth_ldap/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`auth_password_policy`](../auth_password_policy/overview.md), [`auth_signup`](../auth_signup/overview.md), [`auth_totp`](../auth_totp/overview.md), [`auth_totp_mail`](../auth_totp_mail/overview.md), [`auth_totp_mail_enforce`](../auth_totp_mail_enforce/overview.md), [`auth_totp_portal`](../auth_totp_portal/overview.md), [`base`](../base/overview.md), [`base_import`](../base_import/overview.md), [`base_setup`](../base_setup/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md), [`digest`](../digest/overview.md), [`gamification`](../gamification/overview.md), [`google_calendar`](../google_calendar/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_gamification`](../hr_gamification/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_maintenance`](../hr_maintenance/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_skills`](../hr_skills/overview.md), [`im_livechat`](../im_livechat/overview.md), [`im_livechat_mail_bot`](../im_livechat_mail_bot/overview.md), [`lunch`](../lunch/overview.md), [`mail`](../mail/overview.md), [`mail_bot`](../mail_bot/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`microsoft_account`](../microsoft_account/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md), [`phone_validation`](../phone_validation/overview.md), [`resource`](../resource/overview.md), [`sale_crm`](../sale_crm/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sales_team`](../sales_team/overview.md), [`stock`](../stock/overview.md), [`test_uninstall`](../test_uninstall/overview.md), [`web`](../web/overview.md), [`web_unsplash`](../web_unsplash/overview.md), [`website`](../website/overview.md), [`website_forum`](../website_forum/overview.md), [`website_profile`](../website_profile/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
