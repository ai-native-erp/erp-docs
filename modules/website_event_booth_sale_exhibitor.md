---
layout: page
title: "Booths Sale/Exhibitors Bridge (website_event_booth_sale_exhibitor)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_event_booth_sale_exhibitor/
nav_order: 0
---
# Booths Sale/Exhibitors Bridge — `website_event_booth_sale_exhibitor`

**Source:** [`agents/modules/generated/website_event_booth_sale_exhibitor.yaml`](../../agents/modules/generated/website_event_booth_sale_exhibitor.yaml) · **Wiki:** [`knowledge/modules/website_event_booth_sale_exhibitor/overview.md`](../../knowledge/modules/website_event_booth_sale_exhibitor/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_event_booth_sale_exhibitor</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Booths Sale/Exhibitors Bridge</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_event_booth_sale_exhibitor</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_booth_sale_exhibitor"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Bridge module between website_event_booth_exhibitor and website_event_booth_sale.

## Direct dependencies

[`website_event_booth_sale`](website_event_booth_sale.md), [`website_event_exhibitor`](website_event_exhibitor.md)

## Reverse dependencies (modules that depend on this)

[`test_event_full`](test_event_full.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>event.booth.registration</code></div><div class="role">extended by <code>website_event_booth_sale_exhibitor</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.event_booth_sale` | extends_model_from | `agents/modules/generated/event_booth_sale.yaml` |
| `module.test_event_full` | required_by | `agents/modules/generated/test_event_full.yaml` |
| `module.website_event_booth_sale` | depends_on | `agents/modules/generated/website_event_booth_sale.yaml` |
| `module.website_event_exhibitor` | depends_on | `agents/modules/generated/website_event_exhibitor.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_event_booth_sale_exhibitor`](../../../agents/modules/generated/website_event_booth_sale_exhibitor.yaml)
- Domain: `website_ecommerce`
- Category: Marketing/Events
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_event_booth_sale_exhibitor)
- Direct dependencies: [`website_event_booth_sale`](../website_event_booth_sale/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_event_full`](../test_event_full/overview.md)
- Impact graph: [`module:website_event_booth_sale_exhibitor`](../../impact-graph.json)

## Purpose

Bridge module between website_event_booth_exhibitor and website_event_booth_sale.

## Model relationships

- Extends `event.booth.registration` — defined by [`event_booth_sale`](../event_booth_sale/overview.md)

## Related SME agents

- [`module.event_booth_sale`](../../../agents/modules/generated/event_booth_sale.yaml) — extends_model_from
- [`module.test_event_full`](../../../agents/modules/generated/test_event_full.yaml) — required_by
- [`module.website_event_booth_sale`](../../../agents/modules/generated/website_event_booth_sale.yaml) — depends_on
- [`module.website_event_exhibitor`](../../../agents/modules/generated/website_event_exhibitor.yaml) — depends_on

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`event_booth_sale`](../event_booth_sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
