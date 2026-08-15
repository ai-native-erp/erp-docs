---
layout: page
title: "Live Event Tracks (website_event_track_live)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_event_track_live/
nav_order: 0
---
# Live Event Tracks — `website_event_track_live`

**Source:** [`agents/modules/generated/website_event_track_live.yaml`](../../agents/modules/generated/website_event_track_live.yaml) · **Wiki:** [`knowledge/modules/website_event_track_live/overview.md`](../../knowledge/modules/website_event_track_live/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_event_track_live</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Live Event Tracks</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_event_track_live</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_track_live"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Support live tracks: streaming, participation, youtube

## Direct dependencies

[`website_event_track`](website_event_track.md)

## Reverse dependencies (modules that depend on this)

[`test_event_full`](test_event_full.md), [`website_event_track_live_quiz`](website_event_track_live_quiz.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.track</code></div><div class="role">extended by <code>website_event_track_live</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.test_event_full` | required_by | `agents/modules/generated/test_event_full.yaml` |
| `module.website_event_track` | depends_on, extends_model_from | `agents/modules/generated/website_event_track.yaml` |
| `module.website_event_track_live_quiz` | required_by | `agents/modules/generated/website_event_track_live_quiz.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_event_track_live`](../../../agents/modules/generated/website_event_track_live.yaml)
- Domain: `website_ecommerce`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_track_live)
- Direct dependencies: [`website_event_track`](../website_event_track/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_event_full`](../test_event_full/overview.md), [`website_event_track_live_quiz`](../website_event_track_live_quiz/overview.md)
- Impact graph: [`module:website_event_track_live`](../../impact-graph.json)

## Purpose

Support live tracks: streaming, participation, youtube

## Model relationships

- Extends `event.track` — defined by [`website_event_track`](../website_event_track/overview.md)

## Related SME agents

- [`module.test_event_full`](../../../agents/modules/generated/test_event_full.yaml) — required_by
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — depends_on, extends_model_from
- [`module.website_event_track_live_quiz`](../../../agents/modules/generated/website_event_track_live_quiz.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`website_event_track`](../website_event_track/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
