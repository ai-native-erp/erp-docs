---
layout: page
title: "Google Calendar (google_calendar)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/google_calendar/
nav_order: 0
---
# Google Calendar — `google_calendar`

**Source:** [`agents/modules/generated/google_calendar.yaml`](../../agents/modules/generated/google_calendar.yaml) · **Wiki:** [`knowledge/modules/google_calendar/overview.md`](../../knowledge/modules/google_calendar/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>google_calendar</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Google Calendar</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">integrations</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/google_calendar</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/google_calendar"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`calendar`](calendar.md), [`google_account`](google_account.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>calendar.attendee</code></div><div class="role">defined by <code>google_calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.event</code></div><div class="role">defined by <code>google_calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.recurrence</code></div><div class="role">defined by <code>google_calendar</code></div></div>
<div class="model"><div class="name"><code>google.calendar.account.reset</code></div><div class="role">defined by <code>google_calendar</code></div></div>
<div class="model"><div class="name"><code>google.calendar.credentials</code></div><div class="role">defined by <code>google_calendar</code></div></div>
<div class="model"><div class="name"><code>google.calendar.sync</code></div><div class="role">defined by <code>google_calendar</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>calendar.alarm_manager</code></div><div class="role">extended by <code>google_calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.attendee</code></div><div class="role">extended by <code>google_calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.event</code></div><div class="role">extended by <code>google_calendar</code></div></div>
<div class="model"><div class="name"><code>calendar.recurrence</code></div><div class="role">extended by <code>google_calendar</code></div></div>
<div class="model"><div class="name"><code>google.calendar.sync</code></div><div class="role">extended by <code>google_calendar</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>google_calendar</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>google_calendar</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.calendar` | depends_on, extends_model_from | `agents/modules/generated/calendar.yaml` |
| `module.calendar_sms` | model_extended_by | `agents/modules/generated/calendar_sms.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | model_extended_by | `agents/modules/generated/crm.yaml` |
| `module.google_account` | depends_on | `agents/modules/generated/google_account.yaml` |
| `module.hr_recruitment` | model_extended_by | `agents/modules/generated/hr_recruitment.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.google_calendar`](../../../agents/modules/generated/google_calendar.yaml)
- Domain: `integrations`
- Category: Productivity
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/google_calendar)
- Direct dependencies: [`calendar`](../calendar/overview.md), [`google_account`](../google_account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:google_calendar`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `calendar.attendee` — extended by [`microsoft_calendar`](../microsoft_calendar/overview.md)
- `calendar.event` — extended by [`calendar_sms`](../calendar_sms/overview.md), [`crm`](../crm/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md)
- `calendar.recurrence` — extended by [`microsoft_calendar`](../microsoft_calendar/overview.md)
- `google.calendar.account.reset`
- `google.calendar.credentials`
- `google.calendar.sync`
- Extends `calendar.alarm_manager` — defined by [`calendar`](../calendar/overview.md)
- Extends `calendar.attendee` — defined by [`calendar`](../calendar/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md)
- Extends `calendar.event` — defined by [`calendar`](../calendar/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md)
- Extends `calendar.recurrence` — defined by [`calendar`](../calendar/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md)
- Extends `google.calendar.sync` — framework/dynamic owner
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — depends_on, extends_model_from
- [`module.calendar_sms`](../../../agents/modules/generated/calendar_sms.yaml) — model_extended_by
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — model_extended_by
- [`module.google_account`](../../../agents/modules/generated/google_account.yaml) — depends_on
- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — model_extended_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.microsoft_calendar`](../../../agents/modules/generated/microsoft_calendar.yaml) — extends_model_from, model_extended_by

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`calendar_sms`](../calendar_sms/overview.md), [`crm`](../crm/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`calendar`](../calendar/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
