---
layout: page
title: "Booths/Exhibitors Bridge (website_event_booth_exhibitor)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_event_booth_exhibitor/
nav_order: 0
---
# Booths/Exhibitors Bridge — `website_event_booth_exhibitor`

**Source:** [`agents/modules/generated/website_event_booth_exhibitor.yaml`](../../agents/modules/generated/website_event_booth_exhibitor.yaml) · **Wiki:** [`knowledge/modules/website_event_booth_exhibitor/overview.md`](../../knowledge/modules/website_event_booth_exhibitor/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_event_booth_exhibitor</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Booths/Exhibitors Bridge</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_event_booth_exhibitor</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_booth_exhibitor"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Event Booths, automatically create a sponsor.

## Direct dependencies

[`website_event_booth`](website_event_booth.md), [`website_event_exhibitor`](website_event_exhibitor.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.booth</code></div><div class="role">extended by <code>website_event_booth_exhibitor</code></div></div>
<div class="model"><div class="name"><code>event.booth.category</code></div><div class="role">extended by <code>website_event_booth_exhibitor</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.event_booth` | extends_model_from | `agents/modules/generated/event_booth.yaml` |
| `module.website_event_booth` | depends_on | `agents/modules/generated/website_event_booth.yaml` |
| `module.website_event_exhibitor` | depends_on | `agents/modules/generated/website_event_exhibitor.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_event_booth_exhibitor`](../../../agents/modules/generated/website_event_booth_exhibitor.yaml)
- Domain: `website_ecommerce`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_booth_exhibitor)
- Direct dependencies: [`website_event_booth`](../website_event_booth/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_event_booth_exhibitor`](../../impact-graph.json)

## Purpose

Event Booths, automatically create a sponsor.

## Model relationships

- Extends `event.booth` — defined by [`event_booth`](../event_booth/overview.md)
- Extends `event.booth.category` — defined by [`event_booth`](../event_booth/overview.md)

## Related SME agents

- [`module.event_booth`](../../../agents/modules/generated/event_booth.yaml) — extends_model_from
- [`module.website_event_booth`](../../../agents/modules/generated/website_event_booth.yaml) — depends_on
- [`module.website_event_exhibitor`](../../../agents/modules/generated/website_event_exhibitor.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`event_booth`](../event_booth/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
