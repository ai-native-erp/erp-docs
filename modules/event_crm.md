---
layout: page
title: "Event CRM (event_crm)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/event_crm/
nav_order: 0
---
# Event CRM — `event_crm`

**Source:** [`agents/modules/generated/event_crm.yaml`](../../agents/modules/generated/event_crm.yaml) · **Wiki:** [`knowledge/modules/event_crm/overview.md`](../../knowledge/modules/event_crm/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>event_crm</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Event CRM</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/event_crm</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/event_crm"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`crm`](crm.md), [`event`](event.md)

## Reverse dependencies (modules that depend on this)

[`event_crm_sale`](event_crm_sale.md), [`test_crm_full`](test_crm_full.md), [`test_event_full`](test_event_full.md), [`website_event_crm`](website_event_crm.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.event</code></div><div class="role">defined by <code>event_crm</code></div></div>
<div class="model"><div class="name"><code>event.lead.rule</code></div><div class="role">defined by <code>event_crm</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.lead</code></div><div class="role">extended by <code>event_crm</code></div></div>
<div class="model"><div class="name"><code>event.event</code></div><div class="role">extended by <code>event_crm</code></div></div>
<div class="model"><div class="name"><code>event.registration</code></div><div class="role">extended by <code>event_crm</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.crm` | depends_on, extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.event` | depends_on, extends_model_from | `agents/modules/generated/event.yaml` |
| `module.event_booth` | model_extended_by | `agents/modules/generated/event_booth.yaml` |
| `module.event_crm_sale` | required_by | `agents/modules/generated/event_crm_sale.yaml` |
| `module.event_sale` | model_extended_by | `agents/modules/generated/event_sale.yaml` |
| `module.mass_mailing_event` | model_extended_by | `agents/modules/generated/mass_mailing_event.yaml` |
| `module.mass_mailing_event_sms` | model_extended_by | `agents/modules/generated/mass_mailing_event_sms.yaml` |
| `module.mass_mailing_event_track` | model_extended_by | `agents/modules/generated/mass_mailing_event_track.yaml` |
| `module.mass_mailing_event_track_sms` | model_extended_by | `agents/modules/generated/mass_mailing_event_track_sms.yaml` |
| `module.test_crm_full` | required_by | `agents/modules/generated/test_crm_full.yaml` |

## Full wiki excerpt

- SME owner: [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml)
- Domain: `marketing_events`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/event_crm)
- Direct dependencies: [`crm`](../crm/overview.md), [`event`](../event/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`event_crm_sale`](../event_crm_sale/overview.md), [`test_crm_full`](../test_crm_full/overview.md), [`test_event_full`](../test_event_full/overview.md), [`website_event_crm`](../website_event_crm/overview.md)
- Impact graph: [`module:event_crm`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `event.event` — extended by [`event_booth`](../event_booth/overview.md), [`event_sale`](../event_sale/overview.md), [`mass_mailing_event`](../mass_mailing_event/overview.md), [`mass_mailing_event_sms`](../mass_mailing_event_sms/overview.md), [`mass_mailing_event_track`](../mass_mailing_event_track/overview.md), [`mass_mailing_event_track_sms`](../mass_mailing_event_track_sms/overview.md), [`website_event`](../website_event/overview.md), [`website_event_booth`](../website_event_booth/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_event_track_quiz`](../website_event_track_quiz/overview.md)
- `event.lead.rule`
- Extends `crm.lead` — defined by [`crm`](../crm/overview.md)
- Extends `event.event` — defined by [`event`](../event/overview.md), [`website_event`](../website_event/overview.md)
- Extends `event.registration` — defined by [`event`](../event/overview.md), [`website_event`](../website_event/overview.md)

## Related SME agents

- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on, extends_model_from
- [`module.event`](../../../agents/modules/generated/event.yaml) — depends_on, extends_model_from
- [`module.event_booth`](../../../agents/modules/generated/event_booth.yaml) — model_extended_by
- [`module.event_crm_sale`](../../../agents/modules/generated/event_crm_sale.yaml) — required_by
- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — model_extended_by
- [`module.mass_mailing_event`](../../../agents/modules/generated/mass_mailing_event.yaml) — model_extended_by
- [`module.mass_mailing_event_sms`](../../../agents/modules/generated/mass_mailing_event_sms.yaml) — model_extended_by
- [`module.mass_mailing_event_track`](../../../agents/modules/generated/mass_mailing_event_track.yaml) — model_extended_by
- [`module.mass_mailing_event_track_sms`](../../../agents/modules/generated/mass_mailing_event_track_sms.yaml) — model_extended_by
- [`module.test_crm_full`](../../../agents/modules/generated/test_crm_full.yaml) — required_by
- [`module.test_event_full`](../../../agents/modules/generated/test_event_full.yaml) — required_by
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — extends_model_from, model_extended_by
- [`module.website_event_booth`](../../../agents/modules/generated/website_event_booth.yaml) — model_extended_by
- [`module.website_event_crm`](../../../agents/modules/generated/website_event_crm.yaml) — required_by
- [`module.website_event_exhibitor`](../../../agents/modules/generated/website_event_exhibitor.yaml) — model_extended_by
- [`module.website_event_meet`](../../../agents/modules/generated/website_event_meet.yaml) — model_extended_by
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — model_extended_by
- [`module.website_event_track_quiz`](../../../agents/modules/generated/website_event_track_quiz.yaml) — model_extended_by

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`event_booth`](../event_booth/overview.md), [`event_sale`](../event_sale/overview.md), [`mass_mailing_event`](../mass_mailing_event/overview.md), [`mass_mailing_event_sms`](../mass_mailing_event_sms/overview.md), [`mass_mailing_event_track`](../mass_mailing_event_track/overview.md), [`mass_mailing_event_track_sms`](../mass_mailing_event_track_sms/overview.md), [`website_event`](../website_event/overview.md), [`website_event_booth`](../website_event_booth/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_event_track_quiz`](../website_event_track_quiz/overview.md).
- Review model owners used by this module: [`crm`](../crm/overview.md), [`event`](../event/overview.md), [`website_event`](../website_event/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
