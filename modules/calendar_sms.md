---
layout: page
title: "Calendar - SMS (calendar_sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/calendar_sms/
nav_order: 0
---
# Calendar - SMS — `calendar_sms`

**Source:** [`agents/modules/generated/calendar_sms.yaml`](../../agents/modules/generated/calendar_sms.yaml) · **Wiki:** [`knowledge/modules/calendar_sms/overview.md`](../../knowledge/modules/calendar_sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>calendar_sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Calendar - SMS</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/calendar_sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/calendar_sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Send text messages as event reminders

## Direct dependencies

[`calendar`](calendar.md), [`sms`](sms.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>calendar.alarm</code></div><div class="role">extended by <code>calendar_sms</code></div></div>
<div class="model"><div class="name"><code>calendar.alarm_manager</code></div><div class="role">extended by <code>calendar_sms</code></div></div>
<div class="model"><div class="name"><code>calendar.event</code></div><div class="role">extended by <code>calendar_sms</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.calendar` | depends_on, extends_model_from | `agents/modules/generated/calendar.yaml` |
| `module.google_calendar` | extends_model_from | `agents/modules/generated/google_calendar.yaml` |
| `module.microsoft_calendar` | extends_model_from | `agents/modules/generated/microsoft_calendar.yaml` |
| `module.sms` | depends_on | `agents/modules/generated/sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.calendar_sms`](../../../agents/modules/generated/calendar_sms.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/calendar_sms)
- Direct dependencies: [`calendar`](../calendar/overview.md), [`sms`](../sms/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:calendar_sms`](../../impact-graph.json)

## Purpose

Send text messages as event reminders

## Model relationships

- Extends `calendar.alarm` — defined by [`calendar`](../calendar/overview.md)
- Extends `calendar.alarm_manager` — defined by [`calendar`](../calendar/overview.md)
- Extends `calendar.event` — defined by [`calendar`](../calendar/overview.md), [`google_calendar`](../google_calendar/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md)

## Related SME agents

- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — depends_on, extends_model_from
- [`module.google_calendar`](../../../agents/modules/generated/google_calendar.yaml) — extends_model_from
- [`module.microsoft_calendar`](../../../agents/modules/generated/microsoft_calendar.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`calendar`](../calendar/overview.md), [`google_calendar`](../google_calendar/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
