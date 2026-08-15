---
layout: page
title: "Event Meeting / Rooms (website_event_meet)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_event_meet/
nav_order: 0
---
# Event Meeting / Rooms — `website_event_meet`

**Source:** [`agents/modules/generated/website_event_meet.yaml`](../../agents/modules/generated/website_event_meet.yaml) · **Wiki:** [`knowledge/modules/website_event_meet/overview.md`](../../knowledge/modules/website_event_meet/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_event_meet</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Event Meeting / Rooms</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_event_meet</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_meet"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Event: meeting and chat rooms

## Direct dependencies

[`website_event_jitsi`](website_event_jitsi.md)

## Reverse dependencies (modules that depend on this)

[`test_event_full`](test_event_full.md), [`website_event_meet_quiz`](website_event_meet_quiz.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.meeting.room</code></div><div class="role">defined by <code>website_event_meet</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>chat.room.mixin</code></div><div class="role">extended by <code>website_event_meet</code></div></div>
<div class="model"><div class="name"><code>event.event</code></div><div class="role">extended by <code>website_event_meet</code></div></div>
<div class="model"><div class="name"><code>event.type</code></div><div class="role">extended by <code>website_event_meet</code></div></div>
<div class="model"><div class="name"><code>website.event.menu</code></div><div class="role">extended by <code>website_event_meet</code></div></div>
<div class="model"><div class="name"><code>website.published.mixin</code></div><div class="role">extended by <code>website_event_meet</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.event` | extends_model_from | `agents/modules/generated/event.yaml` |
| `module.event_crm` | extends_model_from | `agents/modules/generated/event_crm.yaml` |
| `module.test_event_full` | required_by | `agents/modules/generated/test_event_full.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_event` | extends_model_from | `agents/modules/generated/website_event.yaml` |
| `module.website_event_jitsi` | depends_on | `agents/modules/generated/website_event_jitsi.yaml` |
| `module.website_event_meet_quiz` | required_by | `agents/modules/generated/website_event_meet_quiz.yaml` |
| `module.website_jitsi` | extends_model_from | `agents/modules/generated/website_jitsi.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_event_meet`](../../../agents/modules/generated/website_event_meet.yaml)
- Domain: `website_ecommerce`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_meet)
- Direct dependencies: [`website_event_jitsi`](../website_event_jitsi/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_event_full`](../test_event_full/overview.md), [`website_event_meet_quiz`](../website_event_meet_quiz/overview.md)
- Impact graph: [`module:website_event_meet`](../../impact-graph.json)

## Purpose

Event: meeting and chat rooms

## Model relationships

- `event.meeting.room`
- Extends `chat.room.mixin` — defined by [`website_jitsi`](../website_jitsi/overview.md)
- Extends `event.event` — defined by [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`website_event`](../website_event/overview.md)
- Extends `event.type` — defined by [`event`](../event/overview.md), [`website_event`](../website_event/overview.md)
- Extends `website.event.menu` — defined by [`website_event`](../website_event/overview.md)
- Extends `website.published.mixin` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.event`](../../../agents/modules/generated/event.yaml) — extends_model_from
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — extends_model_from
- [`module.test_event_full`](../../../agents/modules/generated/test_event_full.yaml) — required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — extends_model_from
- [`module.website_event_jitsi`](../../../agents/modules/generated/website_event_jitsi.yaml) — depends_on
- [`module.website_event_meet_quiz`](../../../agents/modules/generated/website_event_meet_quiz.yaml) — required_by
- [`module.website_jitsi`](../../../agents/modules/generated/website_jitsi.yaml) — extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`website`](../website/overview.md), [`website_event`](../website_event/overview.md), [`website_jitsi`](../website_jitsi/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
