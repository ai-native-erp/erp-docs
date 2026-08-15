---
layout: page
title: "Website Events CRM (website_event_crm)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_event_crm/
nav_order: 0
---
# Website Events CRM — `website_event_crm`

**Source:** [`agents/modules/generated/website_event_crm.yaml`](../../agents/modules/generated/website_event_crm.yaml) · **Wiki:** [`knowledge/modules/website_event_crm/overview.md`](../../knowledge/modules/website_event_crm/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_event_crm</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Website Events CRM</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_event_crm</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_crm"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`event_crm`](event_crm.md), [`website_event`](website_event.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.registration</code></div><div class="role">extended by <code>website_event_crm</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.event` | extends_model_from | `agents/modules/generated/event.yaml` |
| `module.event_crm` | depends_on | `agents/modules/generated/event_crm.yaml` |
| `module.website_event` | depends_on, extends_model_from | `agents/modules/generated/website_event.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_event_crm`](../../../agents/modules/generated/website_event_crm.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_crm)
- Direct dependencies: [`event_crm`](../event_crm/overview.md), [`website_event`](../website_event/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_event_crm`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `event.registration` — defined by [`event`](../event/overview.md), [`website_event`](../website_event/overview.md)

## Related SME agents

- [`module.event`](../../../agents/modules/generated/event.yaml) — extends_model_from
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — depends_on
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`event`](../event/overview.md), [`website_event`](../website_event/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
