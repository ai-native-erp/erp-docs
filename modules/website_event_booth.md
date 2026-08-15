---
layout: page
title: "Online Event Booths (website_event_booth)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_event_booth/
nav_order: 0
---
# Online Event Booths — `website_event_booth`

**Source:** [`agents/modules/generated/website_event_booth.yaml`](../../agents/modules/generated/website_event_booth.yaml) · **Wiki:** [`knowledge/modules/website_event_booth/overview.md`](../../knowledge/modules/website_event_booth/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_event_booth</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Online Event Booths</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_event_booth</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_booth"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Events, display your booths on your website

## Direct dependencies

[`event_booth`](event_booth.md), [`website_event`](website_event.md)

## Reverse dependencies (modules that depend on this)

[`website_event_booth_exhibitor`](website_event_booth_exhibitor.md), [`website_event_booth_sale`](website_event_booth_sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.event</code></div><div class="role">extended by <code>website_event_booth</code></div></div>
<div class="model"><div class="name"><code>event.type</code></div><div class="role">extended by <code>website_event_booth</code></div></div>
<div class="model"><div class="name"><code>website.event.menu</code></div><div class="role">extended by <code>website_event_booth</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.event` | extends_model_from | `agents/modules/generated/event.yaml` |
| `module.event_booth` | depends_on | `agents/modules/generated/event_booth.yaml` |
| `module.event_crm` | extends_model_from | `agents/modules/generated/event_crm.yaml` |
| `module.website_event` | depends_on, extends_model_from | `agents/modules/generated/website_event.yaml` |
| `module.website_event_booth_exhibitor` | required_by | `agents/modules/generated/website_event_booth_exhibitor.yaml` |
| `module.website_event_booth_sale` | required_by | `agents/modules/generated/website_event_booth_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_event_booth`](../../../agents/modules/generated/website_event_booth.yaml)
- Domain: `website_ecommerce`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_booth)
- Direct dependencies: [`event_booth`](../event_booth/overview.md), [`website_event`](../website_event/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_event_booth_exhibitor`](../website_event_booth_exhibitor/overview.md), [`website_event_booth_sale`](../website_event_booth_sale/overview.md)
- Impact graph: [`module:website_event_booth`](../../impact-graph.json)

## Purpose

Events, display your booths on your website

## Model relationships

- Extends `event.event` — defined by [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`website_event`](../website_event/overview.md)
- Extends `event.type` — defined by [`event`](../event/overview.md), [`website_event`](../website_event/overview.md)
- Extends `website.event.menu` — defined by [`website_event`](../website_event/overview.md)

## Related SME agents

- [`module.event`](../../../agents/modules/generated/event.yaml) — extends_model_from
- [`module.event_booth`](../../../agents/modules/generated/event_booth.yaml) — depends_on
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — extends_model_from
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — depends_on, extends_model_from
- [`module.website_event_booth_exhibitor`](../../../agents/modules/generated/website_event_booth_exhibitor.yaml) — required_by
- [`module.website_event_booth_sale`](../../../agents/modules/generated/website_event_booth_sale.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`event`](../event/overview.md), [`event_crm`](../event_crm/overview.md), [`website_event`](../website_event/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
