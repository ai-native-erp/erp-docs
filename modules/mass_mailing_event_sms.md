---
layout: page
title: "Event Attendees SMS Marketing (mass_mailing_event_sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mass_mailing_event_sms/
nav_order: 0
---
# Event Attendees SMS Marketing — `mass_mailing_event_sms`

**Source:** [`agents/modules/generated/mass_mailing_event_sms.yaml`](../../agents/modules/generated/mass_mailing_event_sms.yaml) · **Wiki:** [`knowledge/modules/mass_mailing_event_sms/overview.md`](../../knowledge/modules/mass_mailing_event_sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mass_mailing_event_sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Event Attendees SMS Marketing</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mass_mailing_event_sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mass_mailing_event_sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`event`](event.md), [`mass_mailing`](mass_mailing.md), [`mass_mailing_event`](mass_mailing_event.md), [`mass_mailing_sms`](mass_mailing_sms.md), [`sms`](sms.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.event</code></div><div class="role">extended by <code>mass_mailing_event_sms</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.event` | depends_on, extends_model_from | `agents/modules/generated/event.yaml` |
| `module.event_crm` | extends_model_from | `agents/modules/generated/event_crm.yaml` |
| `module.mass_mailing` | depends_on | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_event` | depends_on | `agents/modules/generated/mass_mailing_event.yaml` |
| `module.mass_mailing_sms` | depends_on | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.sms` | depends_on | `agents/modules/generated/sms.yaml` |
| `module.website_event` | extends_model_from | `agents/modules/generated/website_event.yaml` |

## Full wiki excerpt

- SME owner: [`module.mass_mailing_event_sms`](../../../agents/modules/generated/mass_mailing_event_sms.yaml)
- Domain: `marketing_events`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mass_mailing_event_sms)
- Direct dependencies: [`event`](../event/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_event`](../mass_mailing_event/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`sms`](../sms/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:mass_mailing_event_sms`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `event.event` — defined by [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`website_event`](../website_event/overview.md)

## Related SME agents

- [`module.event`](../../../agents/modules/generated/event.yaml) — depends_on, extends_model_from
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — depends_on
- [`module.mass_mailing_event`](../../../agents/modules/generated/mass_mailing_event.yaml) — depends_on
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — depends_on
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`website_event`](../website_event/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
