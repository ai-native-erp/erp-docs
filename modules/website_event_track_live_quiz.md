---
layout: page
title: "Quiz on Live Event Tracks (website_event_track_live_quiz)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_event_track_live_quiz/
nav_order: 0
---
# Quiz on Live Event Tracks — `website_event_track_live_quiz`

**Source:** [`agents/modules/generated/website_event_track_live_quiz.yaml`](../../agents/modules/generated/website_event_track_live_quiz.yaml) · **Wiki:** [`knowledge/modules/website_event_track_live_quiz/overview.md`](../../knowledge/modules/website_event_track_live_quiz/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_event_track_live_quiz</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Quiz on Live Event Tracks</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_event_track_live_quiz</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_track_live_quiz"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Bridge module to support quiz features during "live" tracks.

## Direct dependencies

[`website_event_track_live`](website_event_track_live.md), [`website_event_track_quiz`](website_event_track_quiz.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.website_event_track_live` | depends_on | `agents/modules/generated/website_event_track_live.yaml` |
| `module.website_event_track_quiz` | depends_on | `agents/modules/generated/website_event_track_quiz.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_event_track_live_quiz`](../../../agents/modules/generated/website_event_track_live_quiz.yaml)
- Domain: `website_ecommerce`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_track_live_quiz)
- Direct dependencies: [`website_event_track_live`](../website_event_track_live/overview.md), [`website_event_track_quiz`](../website_event_track_quiz/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_event_track_live_quiz`](../../impact-graph.json)

## Purpose

Bridge module to support quiz features during "live" tracks.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.website_event_track_live`](../../../agents/modules/generated/website_event_track_live.yaml) — depends_on
- [`module.website_event_track_quiz`](../../../agents/modules/generated/website_event_track_quiz.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
