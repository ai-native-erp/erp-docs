---
layout: page
title: "eLearning (website_slides)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_slides/
nav_order: 0
---
# eLearning — `website_slides`

**Source:** [`agents/modules/generated/website_slides.yaml`](../../agents/modules/generated/website_slides.yaml) · **Wiki:** [`knowledge/modules/website_slides/overview.md`](../../knowledge/modules/website_slides/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_slides</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">eLearning</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_slides</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_slides"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage and publish an eLearning platform

## Direct dependencies

[`portal_rating`](portal_rating.md), [`website`](website.md), [`website_mail`](website_mail.md), [`website_profile`](website_profile.md)

## Reverse dependencies (modules that depend on this)

[`hr_skills_slides`](hr_skills_slides.md), [`mass_mailing_slides`](mass_mailing_slides.md), [`test_website_modules`](test_website_modules.md), [`website_sale_slides`](website_sale_slides.md), [`website_slides_forum`](website_slides_forum.md), [`website_slides_survey`](website_slides_survey.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>slide.answer</code></div><div class="role">defined by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.channel</code></div><div class="role">defined by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.channel.invite</code></div><div class="role">defined by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.channel.partner</code></div><div class="role">defined by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.channel.tag</code></div><div class="role">defined by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.channel.tag.group</code></div><div class="role">defined by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.embed</code></div><div class="role">defined by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.question</code></div><div class="role">defined by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.slide</code></div><div class="role">defined by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.slide.partner</code></div><div class="role">defined by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.slide.resource</code></div><div class="role">defined by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.tag</code></div><div class="role">defined by <code>website_slides</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>base.partner.merge.automatic.wizard</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>gamification.challenge</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>gamification.karma.tracking</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>image.mixin</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>ir.binary</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>mail.composer.mixin</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>rating.mixin</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>res.groups</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.channel</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>slide.channel.partner</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>website.cover_properties.mixin</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>website.published.mixin</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>website.published.multi.mixin</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>website.searchable.mixin</code></div><div class="role">extended by <code>website_slides</code></div></div>
<div class="model"><div class="name"><code>website.seo.metadata</code></div><div class="role">extended by <code>website_slides</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.gamification` | extends_model_from | `agents/modules/generated/gamification.yaml` |
| `module.hr_skills_slides` | model_extended_by, required_by | `agents/modules/generated/hr_skills_slides.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml)
- Domain: `website_ecommerce`
- Category: Website/eLearning
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_slides)
- Direct dependencies: [`portal_rating`](../portal_rating/overview.md), [`website`](../website/overview.md), [`website_mail`](../website_mail/overview.md), [`website_profile`](../website_profile/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_skills_slides`](../hr_skills_slides/overview.md), [`mass_mailing_slides`](../mass_mailing_slides/overview.md), [`test_website_modules`](../test_website_modules/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_slides_forum`](../website_slides_forum/overview.md), [`website_slides_survey`](../website_slides_survey/overview.md)
- Impact graph: [`module:website_slides`](../../impact-graph.json)

## Purpose

Manage and publish an eLearning platform

## Model relationships

- `slide.answer`
- `slide.channel` — extended by [`hr_skills_slides`](../hr_skills_slides/overview.md), [`mass_mailing_slides`](../mass_mailing_slides/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_slides_forum`](../website_slides_forum/overview.md), [`website_slides_survey`](../website_slides_survey/overview.md)
- `slide.channel.invite`
- `slide.channel.partner` — extended by [`hr_skills_slides`](../hr_skills_slides/overview.md)
- `slide.channel.tag`
- `slide.channel.tag.group`
- `slide.embed`
- `slide.question`
- `slide.slide` — extended by [`website_slides_survey`](../website_slides_survey/overview.md)
- `slide.slide.partner` — extended by [`website_slides_survey`](../website_slides_survey/overview.md)
- `slide.slide.resource`
- `slide.tag`
- Extends `base.partner.merge.automatic.wizard` — defined by [`base`](../base/overview.md)
- Extends `gamification.challenge` — defined by [`gamification`](../gamification/overview.md)
- Extends `gamification.karma.tracking` — defined by [`gamification`](../gamification/overview.md)
- Extends `image.mixin` — defined by [`base`](../base/overview.md)
- Extends `ir.binary` — defined by [`base`](../base/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.composer.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `rating.mixin` — defined by [`rating`](../rating/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.groups` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `slide.channel` — framework/dynamic owner
- Extends `slide.channel.partner` — framework/dynamic owner
- Extends `website` — defined by [`website`](../website/overview.md)
- Extends `website.cover_properties.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.published.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.published.multi.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.searchable.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.seo.metadata` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.gamification`](../../../agents/modules/generated/gamification.yaml) — extends_model_from
- [`module.hr_skills_slides`](../../../agents/modules/generated/hr_skills_slides.yaml) — model_extended_by, required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_slides`](../../../agents/modules/generated/mass_mailing_slides.yaml) — model_extended_by, required_by
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.portal_rating`](../../../agents/modules/generated/portal_rating.yaml) — depends_on
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.rating`](../../../agents/modules/generated/rating.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.test_website_modules`](../../../agents/modules/generated/test_website_modules.yaml) — required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on, extends_model_from
- [`module.website_mail`](../../../agents/modules/generated/website_mail.yaml) — depends_on
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_profile`](../../../agents/modules/generated/website_profile.yaml) — depends_on
- [`module.website_sale_slides`](../../../agents/modules/generated/website_sale_slides.yaml) — model_extended_by, required_by
- [`module.website_slides_forum`](../../../agents/modules/generated/website_slides_forum.yaml) — model_extended_by, required_by
- [`module.website_slides_survey`](../../../agents/modules/generated/website_slides_survey.yaml) — model_extended_by, required_by

## Regression impact checklist

- Review 6 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr_skills_slides`](../hr_skills_slides/overview.md), [`mass_mailing_slides`](../mass_mailing_slides/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_slides_forum`](../website_slides_forum/overview.md), [`website_slides_survey`](../website_slides_survey/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`gamification`](../gamification/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`rating`](../rating/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
