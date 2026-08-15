---
layout: page
title: "Events (website_event)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_event/
nav_order: 0
---
# Events — `website_event`

**Source:** [`agents/modules/generated/website_event.yaml`](../../agents/modules/generated/website_event.yaml) · **Wiki:** [`knowledge/modules/website_event/overview.md`](../../knowledge/modules/website_event/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_event</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Events</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_event</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Publish events, sell tickets

## Direct dependencies

[`event`](event.md), [`website`](website.md), [`website_mail`](website_mail.md), [`website_partner`](website_partner.md)

## Reverse dependencies (modules that depend on this)

[`website_event_booth`](website_event_booth.md), [`website_event_crm`](website_event_crm.md), [`website_event_jitsi`](website_event_jitsi.md), [`website_event_sale`](website_event_sale.md), [`website_event_track`](website_event_track.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.event</code></div><div class="role">defined by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>event.question</code></div><div class="role">defined by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>event.question.answer</code></div><div class="role">defined by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>event.registration</code></div><div class="role">defined by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>event.registration.answer</code></div><div class="role">defined by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>event.tag</code></div><div class="role">defined by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>event.tag.category</code></div><div class="role">defined by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>event.type</code></div><div class="role">defined by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>website.event.menu</code></div><div class="role">defined by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>website.visitor</code></div><div class="role">defined by <code>website_event</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.event</code></div><div class="role">extended by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>event.registration</code></div><div class="role">extended by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>event.tag</code></div><div class="role">extended by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>event.tag.category</code></div><div class="role">extended by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>event.type</code></div><div class="role">extended by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>website.cover_properties.mixin</code></div><div class="role">extended by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>website.menu</code></div><div class="role">extended by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>website.published.multi.mixin</code></div><div class="role">extended by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>website.searchable.mixin</code></div><div class="role">extended by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>website.seo.metadata</code></div><div class="role">extended by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>website.snippet.filter</code></div><div class="role">extended by <code>website_event</code></div></div>
<div class="model"><div class="name"><code>website.visitor</code></div><div class="role">extended by <code>website_event</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.event` | depends_on, extends_model_from | `agents/modules/generated/event.yaml` |
| `module.event_booth` | model_extended_by | `agents/modules/generated/event_booth.yaml` |
| `module.event_crm` | extends_model_from, model_extended_by | `agents/modules/generated/event_crm.yaml` |
| `module.event_crm_sale` | model_extended_by | `agents/modules/generated/event_crm_sale.yaml` |
| `module.event_sale` | model_extended_by | `agents/modules/generated/event_sale.yaml` |
| `module.mass_mailing_event` | model_extended_by | `agents/modules/generated/mass_mailing_event.yaml` |
| `module.mass_mailing_event_sms` | model_extended_by | `agents/modules/generated/mass_mailing_event_sms.yaml` |
| `module.mass_mailing_event_track` | model_extended_by | `agents/modules/generated/mass_mailing_event_track.yaml` |
| `module.mass_mailing_event_track_sms` | model_extended_by | `agents/modules/generated/mass_mailing_event_track_sms.yaml` |
| `module.website` | depends_on, extends_model_from | `agents/modules/generated/website.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_event`](../../../agents/modules/generated/website_event.yaml)
- Domain: `website_ecommerce`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event)
- Direct dependencies: [`event`](../event/overview.md), [`website`](../website/overview.md), [`website_mail`](../website_mail/overview.md), [`website_partner`](../website_partner/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_event_booth`](../website_event_booth/overview.md), [`website_event_crm`](../website_event_crm/overview.md), [`website_event_jitsi`](../website_event_jitsi/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_event_track`](../website_event_track/overview.md)
- Impact graph: [`module:website_event`](../../impact-graph.json)

## Purpose

Publish events, sell tickets

## Model relationships

- `event.event` — extended by [`event_booth`](../event_booth/overview.md), [`event_crm`](../event_crm/overview.md), [`event_sale`](../event_sale/overview.md), [`mass_mailing_event`](../mass_mailing_event/overview.md), [`mass_mailing_event_sms`](../mass_mailing_event_sms/overview.md), [`mass_mailing_event_track`](../mass_mailing_event_track/overview.md), [`mass_mailing_event_track_sms`](../mass_mailing_event_track_sms/overview.md), [`website_event_booth`](../website_event_booth/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_event_track_quiz`](../website_event_track_quiz/overview.md)
- `event.question`
- `event.question.answer`
- `event.registration` — extended by [`event_crm`](../event_crm/overview.md), [`event_crm_sale`](../event_crm_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`mass_mailing_event`](../mass_mailing_event/overview.md), [`website_event_crm`](../website_event_crm/overview.md)
- `event.registration.answer`
- `event.tag`
- `event.tag.category`
- `event.type` — extended by [`event_booth`](../event_booth/overview.md), [`website_event_booth`](../website_event_booth/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md), [`website_event_track`](../website_event_track/overview.md)
- `website.event.menu` — extended by [`website_event_booth`](../website_event_booth/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md), [`website_event_track`](../website_event_track/overview.md)
- `website.visitor` — extended by [`website_crm`](../website_crm/overview.md), [`website_crm_sms`](../website_crm_sms/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sms`](../website_sms/overview.md)
- Extends `event.event` — defined by [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md)
- Extends `event.registration` — defined by [`event`](../event/overview.md)
- Extends `event.tag` — defined by [`event`](../event/overview.md)
- Extends `event.tag.category` — defined by [`event`](../event/overview.md)
- Extends `event.type` — defined by [`event`](../event/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)
- Extends `website.cover_properties.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.menu` — defined by [`website`](../website/overview.md)
- Extends `website.published.multi.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.searchable.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.seo.metadata` — defined by [`website`](../website/overview.md)
- Extends `website.snippet.filter` — defined by [`website`](../website/overview.md)
- Extends `website.visitor` — defined by [`website`](../website/overview.md), [`website_event_track`](../website_event_track/overview.md)

## Related SME agents

- [`module.event`](../../../agents/modules/generated/event.yaml) — depends_on, extends_model_from
- [`module.event_booth`](../../../agents/modules/generated/event_booth.yaml) — model_extended_by
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — extends_model_from, model_extended_by
- [`module.event_crm_sale`](../../../agents/modules/generated/event_crm_sale.yaml) — model_extended_by
- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — model_extended_by
- [`module.mass_mailing_event`](../../../agents/modules/generated/mass_mailing_event.yaml) — model_extended_by
- [`module.mass_mailing_event_sms`](../../../agents/modules/generated/mass_mailing_event_sms.yaml) — model_extended_by
- [`module.mass_mailing_event_track`](../../../agents/modules/generated/mass_mailing_event_track.yaml) — model_extended_by
- [`module.mass_mailing_event_track_sms`](../../../agents/modules/generated/mass_mailing_event_track_sms.yaml) — model_extended_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on, extends_model_from
- [`module.website_crm`](../../../agents/modules/generated/website_crm.yaml) — model_extended_by
- [`module.website_crm_sms`](../../../agents/modules/generated/website_crm_sms.yaml) — model_extended_by
- [`module.website_event_booth`](../../../agents/modules/generated/website_event_booth.yaml) — model_extended_by, required_by
- [`module.website_event_crm`](../../../agents/modules/generated/website_event_crm.yaml) — model_extended_by, required_by
- [`module.website_event_exhibitor`](../../../agents/modules/generated/website_event_exhibitor.yaml) — model_extended_by
- [`module.website_event_jitsi`](../../../agents/modules/generated/website_event_jitsi.yaml) — required_by
- [`module.website_event_meet`](../../../agents/modules/generated/website_event_meet.yaml) — model_extended_by
- [`module.website_event_sale`](../../../agents/modules/generated/website_event_sale.yaml) — required_by
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — extends_model_from, model_extended_by, required_by
- [`module.website_event_track_quiz`](../../../agents/modules/generated/website_event_track_quiz.yaml) — model_extended_by
- [`module.website_livechat`](../../../agents/modules/generated/website_livechat.yaml) — model_extended_by
- [`module.website_mail`](../../../agents/modules/generated/website_mail.yaml) — depends_on
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — depends_on
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by
- [`module.website_sms`](../../../agents/modules/generated/website_sms.yaml) — model_extended_by

## Regression impact checklist

- Review 5 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`event_booth`](../event_booth/overview.md), [`event_crm`](../event_crm/overview.md), [`event_crm_sale`](../event_crm_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`mass_mailing_event`](../mass_mailing_event/overview.md), [`mass_mailing_event_sms`](../mass_mailing_event_sms/overview.md), [`mass_mailing_event_track`](../mass_mailing_event_track/overview.md), [`mass_mailing_event_track_sms`](../mass_mailing_event_track_sms/overview.md), [`website_crm`](../website_crm/overview.md), [`website_crm_sms`](../website_crm_sms/overview.md), [`website_event_booth`](../website_event_booth/overview.md), [`website_event_crm`](../website_event_crm/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_event_track_quiz`](../website_event_track_quiz/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sms`](../website_sms/overview.md).
- Review model owners used by this module: [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`website`](../website/overview.md), [`website_event_track`](../website_event_track/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
