---
layout: page
title: "Website Jitsi (website_jitsi)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_jitsi/
nav_order: 0
---
# Website Jitsi — `website_jitsi`

**Source:** [`agents/modules/generated/website_jitsi.yaml`](../../agents/modules/generated/website_jitsi.yaml) · **Wiki:** [`knowledge/modules/website_jitsi/overview.md`](../../knowledge/modules/website_jitsi/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_jitsi</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Website Jitsi</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_jitsi</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_jitsi"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Create Jitsi room on website.

## Direct dependencies

[`website`](website.md)

## Reverse dependencies (modules that depend on this)

[`website_event_jitsi`](website_event_jitsi.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>chat.room</code></div><div class="role">defined by <code>website_jitsi</code></div></div>
<div class="model"><div class="name"><code>chat.room.mixin</code></div><div class="role">defined by <code>website_jitsi</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.website` | depends_on | `agents/modules/generated/website.yaml` |
| `module.website_event_exhibitor` | model_extended_by | `agents/modules/generated/website_event_exhibitor.yaml` |
| `module.website_event_jitsi` | required_by | `agents/modules/generated/website_event_jitsi.yaml` |
| `module.website_event_meet` | model_extended_by | `agents/modules/generated/website_event_meet.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_jitsi`](../../../agents/modules/generated/website_jitsi.yaml)
- Domain: `website_ecommerce`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_jitsi)
- Direct dependencies: [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_event_jitsi`](../website_event_jitsi/overview.md)
- Impact graph: [`module:website_jitsi`](../../impact-graph.json)

## Purpose

Create Jitsi room on website.

## Model relationships

- `chat.room`
- `chat.room.mixin` — extended by [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md)

## Related SME agents

- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on
- [`module.website_event_exhibitor`](../../../agents/modules/generated/website_event_exhibitor.yaml) — model_extended_by
- [`module.website_event_jitsi`](../../../agents/modules/generated/website_event_jitsi.yaml) — required_by
- [`module.website_event_meet`](../../../agents/modules/generated/website_event_meet.yaml) — model_extended_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md).
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
