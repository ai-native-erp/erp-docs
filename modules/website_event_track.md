---
layout: page
title: "Advanced Events (website_event_track)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_event_track/
nav_order: 0
---
# Advanced Events — `website_event_track`

**Source:** [`agents/modules/generated/website_event_track.yaml`](../../agents/modules/generated/website_event_track.yaml) · **Wiki:** [`knowledge/modules/website_event_track/overview.md`](../../knowledge/modules/website_event_track/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_event_track</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Advanced Events</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_event_track</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_track"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Sponsors, Tracks, Agenda, Event News

## Direct dependencies

[`website_event`](website_event.md)

## Reverse dependencies (modules that depend on this)

[`mass_mailing_event_track`](mass_mailing_event_track.md), [`mass_mailing_event_track_sms`](mass_mailing_event_track_sms.md), [`test_event_full`](test_event_full.md), [`website_event_track_live`](website_event_track_live.md), [`website_event_track_quiz`](website_event_track_quiz.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.track</code></div><div class="role">defined by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>event.track.location</code></div><div class="role">defined by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>event.track.stage</code></div><div class="role">defined by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>event.track.tag</code></div><div class="role">defined by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>event.track.tag.category</code></div><div class="role">defined by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>event.track.visitor</code></div><div class="role">defined by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>website.visitor</code></div><div class="role">defined by <code>website_event_track</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.event</code></div><div class="role">extended by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>event.type</code></div><div class="role">extended by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>website.event.menu</code></div><div class="role">extended by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>website.menu</code></div><div class="role">extended by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>website.published.mixin</code></div><div class="role">extended by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>website.seo.metadata</code></div><div class="role">extended by <code>website_event_track</code></div></div>
<div class="model"><div class="name"><code>website.visitor</code></div><div class="role">extended by <code>website_event_track</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.event` | extends_model_from | `agents/modules/generated/event.yaml` |
| `module.event_crm` | extends_model_from | `agents/modules/generated/event_crm.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing_event_track` | model_extended_by, required_by | `agents/modules/generated/mass_mailing_event_track.yaml` |
| `module.mass_mailing_event_track_sms` | required_by | `agents/modules/generated/mass_mailing_event_track_sms.yaml` |
| `module.test_event_full` | required_by | `agents/modules/generated/test_event_full.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_crm` | model_extended_by | `agents/modules/generated/website_crm.yaml` |
| `module.website_crm_sms` | model_extended_by | `agents/modules/generated/website_crm_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml)
- Domain: `website_ecommerce`
- Category: Marketing
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_track)
- Direct dependencies: [`website_event`](../website_event/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`mass_mailing_event_track`](../mass_mailing_event_track/overview.md), [`mass_mailing_event_track_sms`](../mass_mailing_event_track_sms/overview.md), [`test_event_full`](../test_event_full/overview.md), [`website_event_track_live`](../website_event_track_live/overview.md), [`website_event_track_quiz`](../website_event_track_quiz/overview.md)
- Impact graph: [`module:website_event_track`](../../impact-graph.json)

## Purpose

Sponsors, Tracks, Agenda, Event News

## Model relationships

- `event.track` — extended by [`mass_mailing_event_track`](../mass_mailing_event_track/overview.md), [`website_event_track_live`](../website_event_track_live/overview.md), [`website_event_track_quiz`](../website_event_track_quiz/overview.md)
- `event.track.location`
- `event.track.stage`
- `event.track.tag`
- `event.track.tag.category`
- `event.track.visitor` — extended by [`website_event_track_quiz`](../website_event_track_quiz/overview.md)
- `website.visitor` — extended by [`website_crm`](../website_crm/overview.md), [`website_crm_sms`](../website_crm_sms/overview.md), [`website_event`](../website_event/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sms`](../website_sms/overview.md)
- Extends `event.event` — defined by [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`website_event`](../website_event/overview.md)
- Extends `event.type` — defined by [`event`](../event/overview.md), [`website_event`](../website_event/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)
- Extends `website.event.menu` — defined by [`website_event`](../website_event/overview.md)
- Extends `website.menu` — defined by [`website`](../website/overview.md)
- Extends `website.published.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.seo.metadata` — defined by [`website`](../website/overview.md)
- Extends `website.visitor` — defined by [`website`](../website/overview.md), [`website_event`](../website_event/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.event`](../../../agents/modules/generated/event.yaml) — extends_model_from
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing_event_track`](../../../agents/modules/generated/mass_mailing_event_track.yaml) — model_extended_by, required_by
- [`module.mass_mailing_event_track_sms`](../../../agents/modules/generated/mass_mailing_event_track_sms.yaml) — required_by
- [`module.test_event_full`](../../../agents/modules/generated/test_event_full.yaml) — required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_crm`](../../../agents/modules/generated/website_crm.yaml) — model_extended_by
- [`module.website_crm_sms`](../../../agents/modules/generated/website_crm_sms.yaml) — model_extended_by
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.website_event_track_live`](../../../agents/modules/generated/website_event_track_live.yaml) — model_extended_by, required_by
- [`module.website_event_track_quiz`](../../../agents/modules/generated/website_event_track_quiz.yaml) — model_extended_by, required_by
- [`module.website_livechat`](../../../agents/modules/generated/website_livechat.yaml) — model_extended_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by
- [`module.website_sms`](../../../agents/modules/generated/website_sms.yaml) — model_extended_by

## Regression impact checklist

- Review 5 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`mass_mailing_event_track`](../mass_mailing_event_track/overview.md), [`website_crm`](../website_crm/overview.md), [`website_crm_sms`](../website_crm_sms/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track_live`](../website_event_track_live/overview.md), [`website_event_track_quiz`](../website_event_track_quiz/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sms`](../website_sms/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`mail`](../mail/overview.md), [`website`](../website/overview.md), [`website_event`](../website_event/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
