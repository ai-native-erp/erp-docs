---
layout: page
title: "Live Chat (im_livechat)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/im_livechat/
nav_order: 0
---
# Live Chat — `im_livechat`

**Source:** [`agents/modules/generated/im_livechat.yaml`](../../agents/modules/generated/im_livechat.yaml) · **Wiki:** [`knowledge/modules/im_livechat/overview.md`](../../knowledge/modules/im_livechat/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>im_livechat</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Live Chat</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/im_livechat</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/im_livechat"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Chat with your website visitors

## Direct dependencies

[`digest`](digest.md), [`mail`](mail.md), [`rating`](rating.md), [`utm`](utm.md)

## Reverse dependencies (modules that depend on this)

[`crm_livechat`](crm_livechat.md), [`hr_livechat`](hr_livechat.md), [`im_livechat_mail_bot`](im_livechat_mail_bot.md), [`spreadsheet_dashboard_im_livechat`](spreadsheet_dashboard_im_livechat.md), [`test_discuss_full`](test_discuss_full.md), [`website_livechat`](website_livechat.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>chatbot.message</code></div><div class="role">defined by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>chatbot.script</code></div><div class="role">defined by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>chatbot.script.answer</code></div><div class="role">defined by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>chatbot.script.step</code></div><div class="role">defined by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>discuss.channel</code></div><div class="role">defined by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>im_livechat.channel</code></div><div class="role">defined by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>im_livechat.channel.rule</code></div><div class="role">defined by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>im_livechat.report.channel</code></div><div class="role">defined by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>im_livechat.report.operator</code></div><div class="role">defined by <code>im_livechat</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>digest.digest</code></div><div class="role">extended by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>discuss.channel</code></div><div class="role">extended by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>discuss.channel.member</code></div><div class="role">extended by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>image.mixin</code></div><div class="role">extended by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>ir.qweb</code></div><div class="role">extended by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>mail.message</code></div><div class="role">extended by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>rating.mixin</code></div><div class="role">extended by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>rating.parent.mixin</code></div><div class="role">extended by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>rating.rating</code></div><div class="role">extended by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>res.users.settings</code></div><div class="role">extended by <code>im_livechat</code></div></div>
<div class="model"><div class="name"><code>utm.source.mixin</code></div><div class="role">extended by <code>im_livechat</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.crm_livechat` | model_extended_by, required_by | `agents/modules/generated/crm_livechat.yaml` |
| `module.digest` | depends_on, extends_model_from | `agents/modules/generated/digest.yaml` |
| `module.hr` | model_extended_by | `agents/modules/generated/hr.yaml` |
| `module.hr_livechat` | required_by | `agents/modules/generated/hr_livechat.yaml` |
| `module.im_livechat_mail_bot` | required_by | `agents/modules/generated/im_livechat_mail_bot.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |

## Full wiki excerpt

- SME owner: [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml)
- Domain: `platform_core`
- Category: Website/Live Chat
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/im_livechat)
- Direct dependencies: [`digest`](../digest/overview.md), [`mail`](../mail/overview.md), [`rating`](../rating/overview.md), [`utm`](../utm/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`crm_livechat`](../crm_livechat/overview.md), [`hr_livechat`](../hr_livechat/overview.md), [`im_livechat_mail_bot`](../im_livechat_mail_bot/overview.md), [`spreadsheet_dashboard_im_livechat`](../spreadsheet_dashboard_im_livechat/overview.md), [`test_discuss_full`](../test_discuss_full/overview.md), [`website_livechat`](../website_livechat/overview.md)
- Impact graph: [`module:im_livechat`](../../impact-graph.json)

## Purpose

Chat with your website visitors

## Model relationships

- `chatbot.message`
- `chatbot.script` — extended by [`crm_livechat`](../crm_livechat/overview.md), [`website_livechat`](../website_livechat/overview.md)
- `chatbot.script.answer`
- `chatbot.script.step` — extended by [`crm_livechat`](../crm_livechat/overview.md), [`website_crm_livechat`](../website_crm_livechat/overview.md), [`website_livechat`](../website_livechat/overview.md)
- `discuss.channel` — extended by [`crm_livechat`](../crm_livechat/overview.md), [`hr`](../hr/overview.md), [`mail`](../mail/overview.md), [`mail_bot`](../mail_bot/overview.md), [`website_crm_livechat`](../website_crm_livechat/overview.md), [`website_livechat`](../website_livechat/overview.md)
- `im_livechat.channel` — extended by [`website_livechat`](../website_livechat/overview.md)
- `im_livechat.channel.rule`
- `im_livechat.report.channel`
- `im_livechat.report.operator`
- Extends `digest.digest` — defined by [`digest`](../digest/overview.md)
- Extends `discuss.channel` — defined by [`mail`](../mail/overview.md)
- Extends `discuss.channel.member` — defined by [`mail`](../mail/overview.md)
- Extends `image.mixin` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb` — defined by [`base`](../base/overview.md)
- Extends `mail.message` — defined by [`mail`](../mail/overview.md)
- Extends `rating.mixin` — defined by [`rating`](../rating/overview.md)
- Extends `rating.parent.mixin` — defined by [`rating`](../rating/overview.md)
- Extends `rating.rating` — defined by [`rating`](../rating/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `res.users.settings` — defined by [`base`](../base/overview.md)
- Extends `utm.source.mixin` — defined by [`utm`](../utm/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.crm_livechat`](../../../agents/modules/generated/crm_livechat.yaml) — model_extended_by, required_by
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — depends_on, extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — model_extended_by
- [`module.hr_livechat`](../../../agents/modules/generated/hr_livechat.yaml) — required_by
- [`module.im_livechat_mail_bot`](../../../agents/modules/generated/im_livechat_mail_bot.yaml) — required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.mail_bot`](../../../agents/modules/generated/mail_bot.yaml) — model_extended_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.rating`](../../../agents/modules/generated/rating.yaml) — depends_on, extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.spreadsheet_dashboard_im_livechat`](../../../agents/modules/generated/spreadsheet_dashboard_im_livechat.yaml) — required_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.test_discuss_full`](../../../agents/modules/generated/test_discuss_full.yaml) — required_by
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — depends_on, extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_crm_livechat`](../../../agents/modules/generated/website_crm_livechat.yaml) — model_extended_by
- [`module.website_livechat`](../../../agents/modules/generated/website_livechat.yaml) — model_extended_by, required_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 6 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`crm_livechat`](../crm_livechat/overview.md), [`hr`](../hr/overview.md), [`mail`](../mail/overview.md), [`mail_bot`](../mail_bot/overview.md), [`website_crm_livechat`](../website_crm_livechat/overview.md), [`website_livechat`](../website_livechat/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`digest`](../digest/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`rating`](../rating/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`utm`](../utm/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
