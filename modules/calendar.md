---
layout: page
title: "Calendar (calendar)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/calendar/
nav_order: 0
---
# Calendar — `calendar`

**Source:** [`agents/modules/generated/calendar.yaml`](../../agents/modules/generated/calendar.yaml) · **Wiki:** [`knowledge/modules/calendar/overview.md`](../../knowledge/modules/calendar/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>calendar</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Calendar</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/calendar</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/calendar"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Schedule employees' meetings

## Direct dependencies

[`base`](base.md), [`mail`](mail.md), [`onboarding`](onboarding.md)

## Reverse dependencies (modules that depend on this)

[`calendar_sms`](calendar_sms.md), [`crm`](crm.md), [`google_calendar`](google_calendar.md), [`hr_holidays`](hr_holidays.md), [`hr_homeworking`](hr_homeworking.md), [`hr_recruitment`](hr_recruitment.md), [`microsoft_calendar`](microsoft_calendar.md), [`test_discuss_full`](test_discuss_full.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>calendar.alarm</code></div><div class="role">defined by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.alarm_manager</code></div><div class="role">defined by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.attendee</code></div><div class="role">defined by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.event</code></div><div class="role">defined by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.event.type</code></div><div class="role">defined by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.filters</code></div><div class="role">defined by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.popover.delete.wizard</code></div><div class="role">defined by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.provider.config</code></div><div class="role">defined by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.recurrence</code></div><div class="role">defined by <code>calendar</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>calendar.alarm</code></div><div class="role">extended by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>mail.activity</code></div><div class="role">extended by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>mail.activity.schedule</code></div><div class="role">extended by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>mail.activity.type</code></div><div class="role">extended by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>onboarding.onboarding</code></div><div class="role">extended by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>onboarding.onboarding.step</code></div><div class="role">extended by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>calendar</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>calendar</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.calendar_sms` | model_extended_by, required_by | `agents/modules/generated/calendar_sms.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | extends_model_from, model_extended_by, required_by | `agents/modules/generated/crm.yaml` |
| `module.google_calendar` | model_extended_by, required_by | `agents/modules/generated/google_calendar.yaml` |
| `module.hr_holidays` | required_by | `agents/modules/generated/hr_holidays.yaml` |
| `module.hr_homeworking` | required_by | `agents/modules/generated/hr_homeworking.yaml` |
| `module.hr_recruitment` | model_extended_by, required_by | `agents/modules/generated/hr_recruitment.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |

## Full wiki excerpt

- SME owner: [`module.calendar`](../../../agents/modules/generated/calendar.yaml)
- Domain: `platform_core`
- Category: Productivity/Calendar
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/calendar)
- Direct dependencies: [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`onboarding`](../onboarding/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`calendar_sms`](../calendar_sms/overview.md), [`crm`](../crm/overview.md), [`google_calendar`](../google_calendar/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md), [`test_discuss_full`](../test_discuss_full/overview.md)
- Impact graph: [`module:calendar`](../../impact-graph.json)

## Purpose

Schedule employees' meetings

## Model relationships

- `calendar.alarm` — extended by [`calendar_sms`](../calendar_sms/overview.md)
- `calendar.alarm_manager` — extended by [`calendar_sms`](../calendar_sms/overview.md), [`google_calendar`](../google_calendar/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md)
- `calendar.attendee` — extended by [`google_calendar`](../google_calendar/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md)
- `calendar.event` — extended by [`calendar_sms`](../calendar_sms/overview.md), [`crm`](../crm/overview.md), [`google_calendar`](../google_calendar/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md)
- `calendar.event.type`
- `calendar.filters`
- `calendar.popover.delete.wizard`
- `calendar.provider.config`
- `calendar.recurrence` — extended by [`google_calendar`](../google_calendar/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md)
- Extends `calendar.alarm` — framework/dynamic owner
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `mail.activity` — defined by [`mail`](../mail/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.activity.schedule` — defined by [`mail`](../mail/overview.md)
- Extends `mail.activity.type` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `onboarding.onboarding` — defined by [`onboarding`](../onboarding/overview.md)
- Extends `onboarding.onboarding.step` — defined by [`onboarding`](../onboarding/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.calendar_sms`](../../../agents/modules/generated/calendar_sms.yaml) — model_extended_by, required_by
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from, model_extended_by, required_by
- [`module.google_calendar`](../../../agents/modules/generated/google_calendar.yaml) — model_extended_by, required_by
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — required_by
- [`module.hr_homeworking`](../../../agents/modules/generated/hr_homeworking.yaml) — required_by
- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — model_extended_by, required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.microsoft_calendar`](../../../agents/modules/generated/microsoft_calendar.yaml) — model_extended_by, required_by
- [`module.onboarding`](../../../agents/modules/generated/onboarding.yaml) — depends_on, extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.test_discuss_full`](../../../agents/modules/generated/test_discuss_full.yaml) — required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 8 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`calendar_sms`](../calendar_sms/overview.md), [`crm`](../crm/overview.md), [`google_calendar`](../google_calendar/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`onboarding`](../onboarding/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
