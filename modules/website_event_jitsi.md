---
layout: page
title: "Event / Jitsi (website_event_jitsi)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_event_jitsi/
nav_order: 0
---
# Event / Jitsi — `website_event_jitsi`

**Source:** [`agents/modules/generated/website_event_jitsi.yaml`](../../agents/modules/generated/website_event_jitsi.yaml) · **Wiki:** [`knowledge/modules/website_event_jitsi/overview.md`](../../knowledge/modules/website_event_jitsi/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_event_jitsi</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Event / Jitsi</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_event_jitsi</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_jitsi"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Event / Jitsi

## Direct dependencies

[`website_event`](website_event.md), [`website_jitsi`](website_jitsi.md)

## Reverse dependencies (modules that depend on this)

[`website_event_exhibitor`](website_event_exhibitor.md), [`website_event_meet`](website_event_meet.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website_event_jitsi</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.website_event` | depends_on | `agents/modules/generated/website_event.yaml` |
| `module.website_event_exhibitor` | required_by | `agents/modules/generated/website_event_exhibitor.yaml` |
| `module.website_event_meet` | required_by | `agents/modules/generated/website_event_meet.yaml` |
| `module.website_jitsi` | depends_on | `agents/modules/generated/website_jitsi.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_event_jitsi`](../../../agents/modules/generated/website_event_jitsi.yaml)
- Domain: `website_ecommerce`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_jitsi)
- Direct dependencies: [`website_event`](../website_event/overview.md), [`website_jitsi`](../website_jitsi/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md)
- Impact graph: [`module:website_event_jitsi`](../../impact-graph.json)

## Purpose

Event / Jitsi

## Model relationships

- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — depends_on
- [`module.website_event_exhibitor`](../../../agents/modules/generated/website_event_exhibitor.yaml) — required_by
- [`module.website_event_meet`](../../../agents/modules/generated/website_event_meet.yaml) — required_by
- [`module.website_jitsi`](../../../agents/modules/generated/website_jitsi.yaml) — depends_on

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
