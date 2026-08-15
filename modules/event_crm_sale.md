---
layout: page
title: "Event CRM Sale (event_crm_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/event_crm_sale/
nav_order: 0
---
# Event CRM Sale — `event_crm_sale`

**Source:** [`agents/modules/generated/event_crm_sale.yaml`](../../agents/modules/generated/event_crm_sale.yaml) · **Wiki:** [`knowledge/modules/event_crm_sale/overview.md`](../../knowledge/modules/event_crm_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>event_crm_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Event CRM Sale</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/event_crm_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/event_crm_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`event_crm`](event_crm.md), [`event_sale`](event_sale.md)

## Reverse dependencies (modules that depend on this)

[`test_event_full`](test_event_full.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.registration</code></div><div class="role">extended by <code>event_crm_sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.event` | extends_model_from | `agents/modules/generated/event.yaml` |
| `module.event_crm` | depends_on | `agents/modules/generated/event_crm.yaml` |
| `module.event_sale` | depends_on | `agents/modules/generated/event_sale.yaml` |
| `module.test_event_full` | required_by | `agents/modules/generated/test_event_full.yaml` |
| `module.website_event` | extends_model_from | `agents/modules/generated/website_event.yaml` |

## Full wiki excerpt

- SME owner: [`module.event_crm_sale`](../../../agents/modules/generated/event_crm_sale.yaml)
- Domain: `marketing_events`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/event_crm_sale)
- Direct dependencies: [`event_crm`](../event_crm/overview.md), [`event_sale`](../event_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_event_full`](../test_event_full/overview.md)
- Impact graph: [`module:event_crm_sale`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `event.registration` — defined by [`event`](../event/overview.md), [`website_event`](../website_event/overview.md)

## Related SME agents

- [`module.event`](../../../agents/modules/generated/event.yaml) — extends_model_from
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — depends_on
- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — depends_on
- [`module.test_event_full`](../../../agents/modules/generated/test_event_full.yaml) — required_by
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`event`](../event/overview.md), [`website_event`](../website_event/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
