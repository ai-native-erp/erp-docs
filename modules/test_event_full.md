---
layout: page
title: "Test Full Event Flow (test_event_full)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_event_full/
nav_order: 0
---
# Test Full Event Flow — `test_event_full`

**Source:** [`agents/modules/generated/test_event_full.yaml`](../../agents/modules/generated/test_event_full.yaml) · **Wiki:** [`knowledge/modules/test_event_full/overview.md`](../../knowledge/modules/test_event_full/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_event_full</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Test Full Event Flow</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_event_full</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_event_full"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`event`](event.md), [`event_booth`](event_booth.md), [`event_crm`](event_crm.md), [`event_crm_sale`](event_crm_sale.md), [`event_sale`](event_sale.md), [`event_sms`](event_sms.md), [`payment_demo`](payment_demo.md), [`website_event_booth_sale_exhibitor`](website_event_booth_sale_exhibitor.md), [`website_event_exhibitor`](website_event_exhibitor.md), [`website_event_meet`](website_event_meet.md), [`website_event_sale`](website_event_sale.md), [`website_event_track`](website_event_track.md), [`website_event_track_live`](website_event_track_live.md), [`website_event_track_quiz`](website_event_track_quiz.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.event` | depends_on | `agents/modules/generated/event.yaml` |
| `module.event_booth` | depends_on | `agents/modules/generated/event_booth.yaml` |
| `module.event_crm` | depends_on | `agents/modules/generated/event_crm.yaml` |
| `module.event_crm_sale` | depends_on | `agents/modules/generated/event_crm_sale.yaml` |
| `module.event_sale` | depends_on | `agents/modules/generated/event_sale.yaml` |
| `module.event_sms` | depends_on | `agents/modules/generated/event_sms.yaml` |
| `module.payment_demo` | depends_on | `agents/modules/generated/payment_demo.yaml` |
| `module.website_event_booth_sale_exhibitor` | depends_on | `agents/modules/generated/website_event_booth_sale_exhibitor.yaml` |
| `module.website_event_exhibitor` | depends_on | `agents/modules/generated/website_event_exhibitor.yaml` |
| `module.website_event_meet` | depends_on | `agents/modules/generated/website_event_meet.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_event_full`](../../../agents/modules/generated/test_event_full.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_event_full)
- Direct dependencies: [`event`](../event/overview.md), [`event_booth`](../event_booth/overview.md), [`event_crm`](../event_crm/overview.md), [`event_crm_sale`](../event_crm_sale/overview.md), [`event_sale`](../event_sale/overview.md), [`event_sms`](../event_sms/overview.md), [`payment_demo`](../payment_demo/overview.md), [`website_event_booth_sale_exhibitor`](../website_event_booth_sale_exhibitor/overview.md), [`website_event_exhibitor`](../website_event_exhibitor/overview.md), [`website_event_meet`](../website_event_meet/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_event_track_live`](../website_event_track_live/overview.md), [`website_event_track_quiz`](../website_event_track_quiz/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_event_full`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.event`](../../../agents/modules/generated/event.yaml) — depends_on
- [`module.event_booth`](../../../agents/modules/generated/event_booth.yaml) — depends_on
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — depends_on
- [`module.event_crm_sale`](../../../agents/modules/generated/event_crm_sale.yaml) — depends_on
- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — depends_on
- [`module.event_sms`](../../../agents/modules/generated/event_sms.yaml) — depends_on
- [`module.payment_demo`](../../../agents/modules/generated/payment_demo.yaml) — depends_on
- [`module.website_event_booth_sale_exhibitor`](../../../agents/modules/generated/website_event_booth_sale_exhibitor.yaml) — depends_on
- [`module.website_event_exhibitor`](../../../agents/modules/generated/website_event_exhibitor.yaml) — depends_on
- [`module.website_event_meet`](../../../agents/modules/generated/website_event_meet.yaml) — depends_on
- [`module.website_event_sale`](../../../agents/modules/generated/website_event_sale.yaml) — depends_on
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — depends_on
- [`module.website_event_track_live`](../../../agents/modules/generated/website_event_track_live.yaml) — depends_on
- [`module.website_event_track_quiz`](../../../agents/modules/generated/website_event_track_quiz.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
