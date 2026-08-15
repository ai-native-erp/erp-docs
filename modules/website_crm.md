---
layout: page
title: "Contact Form (website_crm)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_crm/
nav_order: 0
---
# Contact Form — `website_crm`

**Source:** [`agents/modules/generated/website_crm.yaml`](../../agents/modules/generated/website_crm.yaml) · **Wiki:** [`knowledge/modules/website_crm/overview.md`](../../knowledge/modules/website_crm/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_crm</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Contact Form</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_crm</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_crm"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Generate leads from a contact form

## Direct dependencies

[`crm`](crm.md), [`website`](website.md)

## Reverse dependencies (modules that depend on this)

[`test_crm_full`](test_crm_full.md), [`website_crm_iap_reveal`](website_crm_iap_reveal.md), [`website_crm_livechat`](website_crm_livechat.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.lead</code></div><div class="role">extended by <code>website_crm</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_crm</code></div></div>
<div class="model"><div class="name"><code>website.visitor</code></div><div class="role">extended by <code>website_crm</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.crm` | depends_on, extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.test_crm_full` | required_by | `agents/modules/generated/test_crm_full.yaml` |
| `module.website` | depends_on, extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_crm_iap_reveal` | required_by | `agents/modules/generated/website_crm_iap_reveal.yaml` |
| `module.website_crm_livechat` | required_by | `agents/modules/generated/website_crm_livechat.yaml` |
| `module.website_event` | extends_model_from | `agents/modules/generated/website_event.yaml` |
| `module.website_event_track` | extends_model_from | `agents/modules/generated/website_event_track.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_crm`](../../../agents/modules/generated/website_crm.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_crm)
- Direct dependencies: [`crm`](../crm/overview.md), [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_crm_full`](../test_crm_full/overview.md), [`website_crm_iap_reveal`](../website_crm_iap_reveal/overview.md), [`website_crm_livechat`](../website_crm_livechat/overview.md)
- Impact graph: [`module:website_crm`](../../impact-graph.json)

## Purpose

Generate leads from a contact form

## Model relationships

- Extends `crm.lead` — defined by [`crm`](../crm/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)
- Extends `website.visitor` — defined by [`website`](../website/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md)

## Related SME agents

- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on, extends_model_from
- [`module.test_crm_full`](../../../agents/modules/generated/test_crm_full.yaml) — required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on, extends_model_from
- [`module.website_crm_iap_reveal`](../../../agents/modules/generated/website_crm_iap_reveal.yaml) — required_by
- [`module.website_crm_livechat`](../../../agents/modules/generated/website_crm_livechat.yaml) — required_by
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — extends_model_from
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — extends_model_from

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`crm`](../crm/overview.md), [`website`](../website/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
