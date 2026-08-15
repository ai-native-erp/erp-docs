---
layout: page
title: "Send SMS to Visitor with leads (website_crm_sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_crm_sms/
nav_order: 0
---
# Send SMS to Visitor with leads — `website_crm_sms`

**Source:** [`agents/modules/generated/website_crm_sms.yaml`](../../agents/modules/generated/website_crm_sms.yaml) · **Wiki:** [`knowledge/modules/website_crm_sms/overview.md`](../../knowledge/modules/website_crm_sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_crm_sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Send SMS to Visitor with leads</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_crm_sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_crm_sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Allows to send sms to website visitor that have lead

## Direct dependencies

[`crm`](crm.md), [`website_sms`](website_sms.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>website.visitor</code></div><div class="role">extended by <code>website_crm_sms</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.crm` | depends_on | `agents/modules/generated/crm.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_event` | extends_model_from | `agents/modules/generated/website_event.yaml` |
| `module.website_event_track` | extends_model_from | `agents/modules/generated/website_event_track.yaml` |
| `module.website_sms` | depends_on | `agents/modules/generated/website_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_crm_sms`](../../../agents/modules/generated/website_crm_sms.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_crm_sms)
- Direct dependencies: [`crm`](../crm/overview.md), [`website_sms`](../website_sms/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_crm_sms`](../../impact-graph.json)

## Purpose

Allows to send sms to website visitor that have lead

## Model relationships

- Extends `website.visitor` — defined by [`website`](../website/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md)

## Related SME agents

- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — extends_model_from
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — extends_model_from
- [`module.website_sms`](../../../agents/modules/generated/website_sms.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`website`](../website/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
