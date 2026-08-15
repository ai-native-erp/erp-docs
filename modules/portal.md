---
layout: page
title: "Customer Portal (portal)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/portal/
nav_order: 0
---
# Customer Portal — `portal`

**Source:** [`agents/modules/generated/portal.yaml`](../../agents/modules/generated/portal.yaml) · **Wiki:** [`knowledge/modules/portal/overview.md`](../../knowledge/modules/portal/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>portal</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Customer Portal</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/portal</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/portal"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Customer Portal

## Direct dependencies

[`auth_signup`](auth_signup.md), [`http_routing`](http_routing.md), [`mail`](mail.md), [`web`](web.md), [`web_editor`](web_editor.md)

## Reverse dependencies (modules that depend on this)

[`account`](account.md), [`auth_password_policy_portal`](auth_password_policy_portal.md), [`auth_totp_portal`](auth_totp_portal.md), [`digest`](digest.md), [`event`](event.md), [`mail_group`](mail_group.md), [`mass_mailing_sms`](mass_mailing_sms.md), [`payment`](payment.md), [`portal_rating`](portal_rating.md), [`project`](project.md), [`spreadsheet`](spreadsheet.md), [`test_mail_full`](test_mail_full.md), [`website`](website.md), [`website_crm_partner_assign`](website_crm_partner_assign.md), [`website_payment`](website_payment.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>portal.mixin</code></div><div class="role">defined by <code>portal</code></div></div>
<div class="model"><div class="name"><code>portal.share</code></div><div class="role">defined by <code>portal</code></div></div>
<div class="model"><div class="name"><code>portal.wizard</code></div><div class="role">defined by <code>portal</code></div></div>
<div class="model"><div class="name"><code>portal.wizard.user</code></div><div class="role">defined by <code>portal</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>portal</code></div></div>
<div class="model"><div class="name"><code>ir.qweb</code></div><div class="role">extended by <code>portal</code></div></div>
<div class="model"><div class="name"><code>ir.ui.view</code></div><div class="role">extended by <code>portal</code></div></div>
<div class="model"><div class="name"><code>mail.message</code></div><div class="role">extended by <code>portal</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>portal</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>portal</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>portal</code></div></div>
<div class="model"><div class="name"><code>res.users.apikeys.description</code></div><div class="role">extended by <code>portal</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from, model_extended_by, required_by | `agents/modules/generated/account.yaml` |
| `module.auth_password_policy_portal` | required_by | `agents/modules/generated/auth_password_policy_portal.yaml` |
| `module.auth_signup` | depends_on | `agents/modules/generated/auth_signup.yaml` |
| `module.auth_totp_portal` | required_by | `agents/modules/generated/auth_totp_portal.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.digest` | required_by | `agents/modules/generated/digest.yaml` |
| `module.event` | required_by | `agents/modules/generated/event.yaml` |
| `module.http_routing` | depends_on | `agents/modules/generated/http_routing.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |

## Full wiki excerpt

- SME owner: [`module.portal`](../../../agents/modules/generated/portal.yaml)
- Domain: `website_ecommerce`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/portal)
- Direct dependencies: [`auth_signup`](../auth_signup/overview.md), [`http_routing`](../http_routing/overview.md), [`mail`](../mail/overview.md), [`web`](../web/overview.md), [`web_editor`](../web_editor/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`account`](../account/overview.md), [`auth_password_policy_portal`](../auth_password_policy_portal/overview.md), [`auth_totp_portal`](../auth_totp_portal/overview.md), [`digest`](../digest/overview.md), [`event`](../event/overview.md), [`mail_group`](../mail_group/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`payment`](../payment/overview.md), [`portal_rating`](../portal_rating/overview.md), [`project`](../project/overview.md), [`spreadsheet`](../spreadsheet/overview.md), [`test_mail_full`](../test_mail_full/overview.md), [`website`](../website/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_payment`](../website_payment/overview.md)
- Impact graph: [`module:portal`](../../impact-graph.json)

## Purpose

Customer Portal

## Model relationships

- `portal.mixin` — extended by [`account`](../account/overview.md), [`l10n_in_ewaybill_stock`](../l10n_in_ewaybill_stock/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`sale`](../sale/overview.md), [`test_mail_full`](../test_mail_full/overview.md)
- `portal.share` — extended by [`project`](../project/overview.md)
- `portal.wizard`
- `portal.wizard.user` — extended by [`website`](../website/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb` — defined by [`base`](../base/overview.md)
- Extends `ir.ui.view` — defined by [`website`](../website/overview.md)
- Extends `mail.message` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users.apikeys.description` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from, model_extended_by, required_by
- [`module.auth_password_policy_portal`](../../../agents/modules/generated/auth_password_policy_portal.yaml) — required_by
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — depends_on
- [`module.auth_totp_portal`](../../../agents/modules/generated/auth_totp_portal.yaml) — required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — required_by
- [`module.event`](../../../agents/modules/generated/event.yaml) — required_by
- [`module.http_routing`](../../../agents/modules/generated/http_routing.yaml) — depends_on
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_in_ewaybill_stock`](../../../agents/modules/generated/l10n_in_ewaybill_stock.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mail_group`](../../../agents/modules/generated/mail_group.yaml) — required_by
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — required_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — required_by
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.portal_rating`](../../../agents/modules/generated/portal_rating.yaml) — required_by
- [`module.project`](../../../agents/modules/generated/project.yaml) — model_extended_by, required_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from, model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.spreadsheet`](../../../agents/modules/generated/spreadsheet.yaml) — required_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.test_mail_full`](../../../agents/modules/generated/test_mail_full.yaml) — model_extended_by, required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on
- [`module.web_editor`](../../../agents/modules/generated/web_editor.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from, model_extended_by, required_by
- [`module.website_crm_partner_assign`](../../../agents/modules/generated/website_crm_partner_assign.yaml) — required_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_payment`](../../../agents/modules/generated/website_payment.yaml) — required_by

## Regression impact checklist

- Review 15 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`l10n_in_ewaybill_stock`](../l10n_in_ewaybill_stock/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`sale`](../sale/overview.md), [`test_mail_full`](../test_mail_full/overview.md), [`website`](../website/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
