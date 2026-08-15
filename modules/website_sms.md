---
layout: page
title: "Send SMS to Visitor (website_sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_sms/
nav_order: 0
---
# Send SMS to Visitor — `website_sms`

**Source:** [`agents/modules/generated/website_sms.yaml`](../../agents/modules/generated/website_sms.yaml) · **Wiki:** [`knowledge/modules/website_sms/overview.md`](../../knowledge/modules/website_sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Send SMS to Visitor</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Allows to send sms to website visitor

## Direct dependencies

[`sms`](sms.md), [`website`](website.md)

## Reverse dependencies (modules that depend on this)

[`website_crm_sms`](website_crm_sms.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>website.visitor</code></div><div class="role">extended by <code>website_sms</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.sms` | depends_on | `agents/modules/generated/sms.yaml` |
| `module.website` | depends_on, extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_crm_sms` | required_by | `agents/modules/generated/website_crm_sms.yaml` |
| `module.website_event` | extends_model_from | `agents/modules/generated/website_event.yaml` |
| `module.website_event_track` | extends_model_from | `agents/modules/generated/website_event_track.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_sms`](../../../agents/modules/generated/website_sms.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sms)
- Direct dependencies: [`sms`](../sms/overview.md), [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_crm_sms`](../website_crm_sms/overview.md)
- Impact graph: [`module:website_sms`](../../impact-graph.json)

## Purpose

Allows to send sms to website visitor

## Model relationships

- Extends `website.visitor` — defined by [`website`](../website/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md)

## Related SME agents

- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on, extends_model_from
- [`module.website_crm_sms`](../../../agents/modules/generated/website_crm_sms.yaml) — required_by
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — extends_model_from
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`website`](../website/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
