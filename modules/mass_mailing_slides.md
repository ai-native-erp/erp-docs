---
layout: page
title: "Mass mailing on course members (mass_mailing_slides)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mass_mailing_slides/
nav_order: 0
---
# Mass mailing on course members — `mass_mailing_slides`

**Source:** [`agents/modules/generated/mass_mailing_slides.yaml`](../../agents/modules/generated/mass_mailing_slides.yaml) · **Wiki:** [`knowledge/modules/mass_mailing_slides/overview.md`](../../knowledge/modules/mass_mailing_slides/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mass_mailing_slides</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Mass mailing on course members</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mass_mailing_slides</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mass_mailing_slides"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`mass_mailing`](mass_mailing.md), [`website_slides`](website_slides.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>slide.channel</code></div><div class="role">extended by <code>mass_mailing_slides</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mass_mailing` | depends_on | `agents/modules/generated/mass_mailing.yaml` |
| `module.website_slides` | depends_on, extends_model_from | `agents/modules/generated/website_slides.yaml` |

## Full wiki excerpt

- SME owner: [`module.mass_mailing_slides`](../../../agents/modules/generated/mass_mailing_slides.yaml)
- Domain: `marketing_events`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mass_mailing_slides)
- Direct dependencies: [`mass_mailing`](../mass_mailing/overview.md), [`website_slides`](../website_slides/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:mass_mailing_slides`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `slide.channel` — defined by [`website_slides`](../website_slides/overview.md)

## Related SME agents

- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — depends_on
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`website_slides`](../website_slides/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
