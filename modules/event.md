---
layout: page
title: "Events Organization (event)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/event/
nav_order: 0
---
# Events Organization — `event`

**Source:** [`agents/modules/generated/event.yaml`](../../agents/modules/generated/event.yaml) · **Wiki:** [`knowledge/modules/event/overview.md`](../../knowledge/modules/event/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>event</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Events Organization</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/event</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/event"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Trainings, Conferences, Meetings, Exhibitions, Registrations

## Direct dependencies

[`barcodes`](barcodes.md), [`base_setup`](base_setup.md), [`mail`](mail.md), [`phone_validation`](phone_validation.md), [`portal`](portal.md), [`utm`](utm.md)

## Reverse dependencies (modules that depend on this)

[`event_booth`](event_booth.md), [`event_crm`](event_crm.md), [`event_sale`](event_sale.md), [`event_sms`](event_sms.md), [`mass_mailing_event`](mass_mailing_event.md), [`mass_mailing_event_sms`](mass_mailing_event_sms.md), [`test_event_full`](test_event_full.md), [`website_event`](website_event.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.event</code></div><div class="role">defined by <code>event</code></div></div>
<div class="model"><div class="name"><code>event.event.ticket</code></div><div class="role">defined by <code>event</code></div></div>
<div class="model"><div class="name"><code>event.mail</code></div><div class="role">defined by <code>event</code></div></div>
<div class="model"><div class="name"><code>event.mail.registration</code></div><div class="role">defined by <code>event</code></div></div>
<div class="model"><div class="name"><code>event.registration</code></div><div class="role">defined by <code>event</code></div></div>
<div class="model"><div class="name"><code>event.stage</code></div><div class="role">defined by <code>event</code></div></div>
<div class="model"><div class="name"><code>event.tag</code></div><div class="role">defined by <code>event</code></div></div>
<div class="model"><div class="name"><code>event.tag.category</code></div><div class="role">defined by <code>event</code></div></div>
<div class="model"><div class="name"><code>event.type</code></div><div class="role">defined by <code>event</code></div></div>
<div class="model"><div class="name"><code>event.type.mail</code></div><div class="role">defined by <code>event</code></div></div>
<div class="model"><div class="name"><code>event.type.ticket</code></div><div class="role">defined by <code>event</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.type.ticket</code></div><div class="role">extended by <code>event</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>event</code></div></div>
<div class="model"><div class="name"><code>mail.template</code></div><div class="role">extended by <code>event</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>event</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>event</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>event</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.barcodes` | depends_on | `agents/modules/generated/barcodes.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_setup` | depends_on | `agents/modules/generated/base_setup.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.event_booth` | model_extended_by, required_by | `agents/modules/generated/event_booth.yaml` |
| `module.event_crm` | model_extended_by, required_by | `agents/modules/generated/event_crm.yaml` |
| `module.event_crm_sale` | model_extended_by | `agents/modules/generated/event_crm_sale.yaml` |
| `module.event_sale` | model_extended_by, required_by | `agents/modules/generated/event_sale.yaml` |
| `module.event_sms` | model_extended_by, required_by | `agents/modules/generated/event_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.event`](../../../agents/modules/generated/event.yaml)
- Domain: `marketing_events`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/event)
- Direct dependencies: [`barcodes`](../barcodes/overview.md), [`base_setup`](../base_setup/overview.md), [`mail`](../mail/overview.md), [`phone_validation`](../phone_validation/overview.md), [`portal`](../portal/overview.md), [`utm`](../utm/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`event_booth`](../event_booth/overview.md), [`event_crm`](../event_crm/overview.md), [`event_sale`](../event_sale/overview.md), [`event_sms`](../event_sms/overview.md), [`mass_mailing_event`](../mass_mailing_event/overview.md), [`mass_mailing_event_sms`](../mass_mailing_event_sms/overview.md), [`test_event_full`](../test_event_full/overview.md), [`website_event`](../website_event/overview.md)
- Impact graph: [`module:event`](../../impact-graph.json)

## Purpose

Trainings, Conferences, Meetings, Exhibitions, Registrations

## Model relationships

- `event.event` — extended by [`event_booth`](../event_booth/overview.md), [`event_crm`](../event_crm/overview.md), [`event_sale`](../event_sale/overview.md), [`mass_mailing_event`](../mass_mailing_event/overview.md), [`mass_mailing_event_sms`](../mass_mailing_event_sms/overview.md), [`mass_mailing_event_track`](../mass_mailing_event_track/overview.md), [`mass_mailing_event_track_sms`](../mass_mailing_event_track_sms/overview.md), [`website_event`](../website_event/overview.md), [`website_event_booth`](../website_event_booth/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_event_track_quiz`](../website_event_track_quiz/overview.md)
- `event.event.ticket` — extended by [`event_sale`](../event_sale/overview.md)
- `event.mail` — extended by [`event_sms`](../event_sms/overview.md)
- `event.mail.registration` — extended by [`event_sms`](../event_sms/overview.md)
- `event.registration` — extended by [`event_crm`](../event_crm/overview.md), [`event_crm_sale`](../event_crm_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`mass_mailing_event`](../mass_mailing_event/overview.md), [`website_event`](../website_event/overview.md), [`website_event_crm`](../website_event_crm/overview.md)
- `event.stage`
- `event.tag` — extended by [`website_event`](../website_event/overview.md)
- `event.tag.category` — extended by [`website_event`](../website_event/overview.md)
- `event.type` — extended by [`event_booth`](../event_booth/overview.md), [`website_event`](../website_event/overview.md), [`website_event_booth`](../website_event_booth/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md), [`website_event_track`](../website_event_track/overview.md)
- `event.type.mail` — extended by [`event_sms`](../event_sms/overview.md)
- `event.type.ticket` — extended by [`event_sale`](../event_sale/overview.md)
- Extends `event.type.ticket` — framework/dynamic owner
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.template` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.barcodes`](../../../agents/modules/generated/barcodes.yaml) — depends_on
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.event_booth`](../../../agents/modules/generated/event_booth.yaml) — model_extended_by, required_by
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — model_extended_by, required_by
- [`module.event_crm_sale`](../../../agents/modules/generated/event_crm_sale.yaml) — model_extended_by
- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — model_extended_by, required_by
- [`module.event_sms`](../../../agents/modules/generated/event_sms.yaml) — model_extended_by, required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mass_mailing_event`](../../../agents/modules/generated/mass_mailing_event.yaml) — model_extended_by, required_by
- [`module.mass_mailing_event_sms`](../../../agents/modules/generated/mass_mailing_event_sms.yaml) — model_extended_by, required_by
- [`module.mass_mailing_event_track`](../../../agents/modules/generated/mass_mailing_event_track.yaml) — model_extended_by
- [`module.mass_mailing_event_track_sms`](../../../agents/modules/generated/mass_mailing_event_track_sms.yaml) — model_extended_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — depends_on, extends_model_from
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.test_event_full`](../../../agents/modules/generated/test_event_full.yaml) — required_by
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — model_extended_by, required_by
- [`module.website_event_booth`](../../../agents/modules/generated/website_event_booth.yaml) — model_extended_by
- [`module.website_event_crm`](../../../agents/modules/generated/website_event_crm.yaml) — model_extended_by
- [`module.website_event_exhibitor`](../../../agents/modules/generated/website_event_exhibitor.yaml) — model_extended_by
- [`module.website_event_meet`](../../../agents/modules/generated/website_event_meet.yaml) — model_extended_by
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — model_extended_by
- [`module.website_event_track_quiz`](../../../agents/modules/generated/website_event_track_quiz.yaml) — model_extended_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 8 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`event_booth`](../event_booth/overview.md), [`event_crm`](../event_crm/overview.md), [`event_crm_sale`](../event_crm_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`event_sms`](../event_sms/overview.md), [`mass_mailing_event`](../mass_mailing_event/overview.md), [`mass_mailing_event_sms`](../mass_mailing_event_sms/overview.md), [`mass_mailing_event_track`](../mass_mailing_event_track/overview.md), [`mass_mailing_event_track_sms`](../mass_mailing_event_track_sms/overview.md), [`website_event`](../website_event/overview.md), [`website_event_booth`](../website_event_booth/overview.md), [`website_event_crm`](../website_event_crm/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_event_track_quiz`](../website_event_track_quiz/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
