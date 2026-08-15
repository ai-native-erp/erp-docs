---
layout: page
title: "Surveys (survey)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/survey/
nav_order: 0
---
# Surveys — `survey`

**Source:** [`agents/modules/generated/survey.yaml`](../../agents/modules/generated/survey.yaml) · **Wiki:** [`knowledge/modules/survey/overview.md`](../../knowledge/modules/survey/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>survey</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Surveys</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/survey</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/survey"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Send your surveys or share them live.

## Direct dependencies

[`auth_signup`](auth_signup.md), [`gamification`](gamification.md), [`http_routing`](http_routing.md), [`mail`](mail.md), [`web_tour`](web_tour.md)

## Reverse dependencies (modules that depend on this)

[`hr_recruitment_survey`](hr_recruitment_survey.md), [`hr_skills_survey`](hr_skills_survey.md), [`website_slides_survey`](website_slides_survey.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>survey.invite</code></div><div class="role">defined by <code>survey</code></div></div>
<div class="model"><div class="name"><code>survey.question</code></div><div class="role">defined by <code>survey</code></div></div>
<div class="model"><div class="name"><code>survey.question.answer</code></div><div class="role">defined by <code>survey</code></div></div>
<div class="model"><div class="name"><code>survey.survey</code></div><div class="role">defined by <code>survey</code></div></div>
<div class="model"><div class="name"><code>survey.user_input</code></div><div class="role">defined by <code>survey</code></div></div>
<div class="model"><div class="name"><code>survey.user_input.line</code></div><div class="role">defined by <code>survey</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>gamification.badge</code></div><div class="role">extended by <code>survey</code></div></div>
<div class="model"><div class="name"><code>gamification.challenge</code></div><div class="role">extended by <code>survey</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>survey</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>survey</code></div></div>
<div class="model"><div class="name"><code>mail.composer.mixin</code></div><div class="role">extended by <code>survey</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>survey</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>survey</code></div></div>
<div class="model"><div class="name"><code>survey.survey</code></div><div class="role">extended by <code>survey</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.auth_signup` | depends_on | `agents/modules/generated/auth_signup.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.gamification` | depends_on, extends_model_from | `agents/modules/generated/gamification.yaml` |
| `module.hr_recruitment_survey` | model_extended_by, required_by | `agents/modules/generated/hr_recruitment_survey.yaml` |
| `module.hr_skills_survey` | model_extended_by, required_by | `agents/modules/generated/hr_skills_survey.yaml` |
| `module.http_routing` | depends_on | `agents/modules/generated/http_routing.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |

## Full wiki excerpt

- SME owner: [`module.survey`](../../../agents/modules/generated/survey.yaml)
- Domain: `marketing_events`
- Category: Marketing/Surveys
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/survey)
- Direct dependencies: [`auth_signup`](../auth_signup/overview.md), [`gamification`](../gamification/overview.md), [`http_routing`](../http_routing/overview.md), [`mail`](../mail/overview.md), [`web_tour`](../web_tour/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_recruitment_survey`](../hr_recruitment_survey/overview.md), [`hr_skills_survey`](../hr_skills_survey/overview.md), [`website_slides_survey`](../website_slides_survey/overview.md)
- Impact graph: [`module:survey`](../../impact-graph.json)

## Purpose

Send your surveys or share them live.

## Model relationships

- `survey.invite` — extended by [`hr_recruitment_survey`](../hr_recruitment_survey/overview.md)
- `survey.question`
- `survey.question.answer`
- `survey.survey` — extended by [`website_slides_survey`](../website_slides_survey/overview.md)
- `survey.user_input` — extended by [`hr_recruitment_survey`](../hr_recruitment_survey/overview.md), [`hr_skills_survey`](../hr_skills_survey/overview.md), [`website_slides_survey`](../website_slides_survey/overview.md)
- `survey.user_input.line`
- Extends `gamification.badge` — defined by [`gamification`](../gamification/overview.md), [`website_profile`](../website_profile/overview.md)
- Extends `gamification.challenge` — defined by [`gamification`](../gamification/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.composer.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `survey.survey` — framework/dynamic owner

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — depends_on
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.gamification`](../../../agents/modules/generated/gamification.yaml) — depends_on, extends_model_from
- [`module.hr_recruitment_survey`](../../../agents/modules/generated/hr_recruitment_survey.yaml) — model_extended_by, required_by
- [`module.hr_skills_survey`](../../../agents/modules/generated/hr_skills_survey.yaml) — model_extended_by, required_by
- [`module.http_routing`](../../../agents/modules/generated/http_routing.yaml) — depends_on
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.web_tour`](../../../agents/modules/generated/web_tour.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_profile`](../../../agents/modules/generated/website_profile.yaml) — extends_model_from
- [`module.website_slides_survey`](../../../agents/modules/generated/website_slides_survey.yaml) — model_extended_by, required_by

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr_recruitment_survey`](../hr_recruitment_survey/overview.md), [`hr_skills_survey`](../hr_skills_survey/overview.md), [`website_slides_survey`](../website_slides_survey/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`gamification`](../gamification/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md), [`website_profile`](../website_profile/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
