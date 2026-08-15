---
layout: page
title: "Events Booths (event_booth)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/event_booth/
nav_order: 0
---
# Events Booths — `event_booth`

**Source:** [`agents/modules/generated/event_booth.yaml`](../../agents/modules/generated/event_booth.yaml) · **Wiki:** [`knowledge/modules/event_booth/overview.md`](../../knowledge/modules/event_booth/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>event_booth</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Events Booths</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/event_booth</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/event_booth"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage event booths

## Direct dependencies

[`event`](event.md)

## Reverse dependencies (modules that depend on this)

[`event_booth_sale`](event_booth_sale.md), [`test_event_full`](test_event_full.md), [`website_event_booth`](website_event_booth.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.booth</code></div><div class="role">defined by <code>event_booth</code></div></div>
<div class="model"><div class="name"><code>event.booth.category</code></div><div class="role">defined by <code>event_booth</code></div></div>
<div class="model"><div class="name"><code>event.type.booth</code></div><div class="role">defined by <code>event_booth</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.event</code></div><div class="role">extended by <code>event_booth</code></div></div>
<div class="model"><div class="name"><code>event.type</code></div><div class="role">extended by <code>event_booth</code></div></div>
<div class="model"><div class="name"><code>event.type.booth</code></div><div class="role">extended by <code>event_booth</code></div></div>
<div class="model"><div class="name"><code>image.mixin</code></div><div class="role">extended by <code>event_booth</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>event_booth</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>event_booth</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.event` | depends_on, extends_model_from | `agents/modules/generated/event.yaml` |
| `module.event_booth_sale` | model_extended_by, required_by | `agents/modules/generated/event_booth_sale.yaml` |
| `module.event_crm` | extends_model_from | `agents/modules/generated/event_crm.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.test_event_full` | required_by | `agents/modules/generated/test_event_full.yaml` |
| `module.website_event` | extends_model_from | `agents/modules/generated/website_event.yaml` |
| `module.website_event_booth` | required_by | `agents/modules/generated/website_event_booth.yaml` |
| `module.website_event_booth_exhibitor` | model_extended_by | `agents/modules/generated/website_event_booth_exhibitor.yaml` |

## Full wiki excerpt

- SME owner: [`module.event_booth`](../../../agents/modules/generated/event_booth.yaml)
- Domain: `marketing_events`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/event_booth)
- Direct dependencies: [`event`](../event/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`event_booth_sale`](../event_booth_sale/overview.md), [`test_event_full`](../test_event_full/overview.md), [`website_event_booth`](../website_event_booth/overview.md)
- Impact graph: [`module:event_booth`](../../impact-graph.json)

## Purpose

Manage event booths

## Model relationships

- `event.booth` — extended by [`event_booth_sale`](../event_booth_sale/overview.md), [`website_event_booth_exhibitor`](../website_event_booth_exhibitor/overview.md)
- `event.booth.category` — extended by [`event_booth_sale`](../event_booth_sale/overview.md), [`website_event_booth_exhibitor`](../website_event_booth_exhibitor/overview.md)
- `event.type.booth` — extended by [`event_booth_sale`](../event_booth_sale/overview.md)
- Extends `event.event` — defined by [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`website_event`](../website_event/overview.md)
- Extends `event.type` — defined by [`event`](../event/overview.md), [`website_event`](../website_event/overview.md)
- Extends `event.type.booth` — framework/dynamic owner
- Extends `image.mixin` — defined by [`base`](../base/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.event`](../../../agents/modules/generated/event.yaml) — depends_on, extends_model_from
- [`module.event_booth_sale`](../../../agents/modules/generated/event_booth_sale.yaml) — model_extended_by, required_by
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.test_event_full`](../../../agents/modules/generated/test_event_full.yaml) — required_by
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — extends_model_from
- [`module.website_event_booth`](../../../agents/modules/generated/website_event_booth.yaml) — required_by
- [`module.website_event_booth_exhibitor`](../../../agents/modules/generated/website_event_booth_exhibitor.yaml) — model_extended_by

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`event_booth_sale`](../event_booth_sale/overview.md), [`website_event_booth_exhibitor`](../website_event_booth_exhibitor/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`mail`](../mail/overview.md), [`website_event`](../website_event/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
