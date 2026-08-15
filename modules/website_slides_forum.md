---
layout: page
title: "Forum on Courses (website_slides_forum)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_slides_forum/
nav_order: 0
---
# Forum on Courses — `website_slides_forum`

**Source:** [`agents/modules/generated/website_slides_forum.yaml`](../../agents/modules/generated/website_slides_forum.yaml) · **Wiki:** [`knowledge/modules/website_slides_forum/overview.md`](../../knowledge/modules/website_slides_forum/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_slides_forum</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Forum on Courses</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_slides_forum</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_slides_forum"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Allows to link forum on a course

## Direct dependencies

[`website_forum`](website_forum.md), [`website_slides`](website_slides.md)

## Reverse dependencies (modules that depend on this)

[`test_website_slides_full`](test_website_slides_full.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>forum.forum</code></div><div class="role">extended by <code>website_slides_forum</code></div></div>
<div class="model"><div class="name"><code>slide.channel</code></div><div class="role">extended by <code>website_slides_forum</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.test_website_slides_full` | required_by | `agents/modules/generated/test_website_slides_full.yaml` |
| `module.website_forum` | depends_on, extends_model_from | `agents/modules/generated/website_forum.yaml` |
| `module.website_slides` | depends_on, extends_model_from | `agents/modules/generated/website_slides.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_slides_forum`](../../../agents/modules/generated/website_slides_forum.yaml)
- Domain: `website_ecommerce`
- Category: Website/eLearning
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_slides_forum)
- Direct dependencies: [`website_forum`](../website_forum/overview.md), [`website_slides`](../website_slides/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_website_slides_full`](../test_website_slides_full/overview.md)
- Impact graph: [`module:website_slides_forum`](../../impact-graph.json)

## Purpose

Allows to link forum on a course

## Model relationships

- Extends `forum.forum` — defined by [`website_forum`](../website_forum/overview.md)
- Extends `slide.channel` — defined by [`website_slides`](../website_slides/overview.md)

## Related SME agents

- [`module.test_website_slides_full`](../../../agents/modules/generated/test_website_slides_full.yaml) — required_by
- [`module.website_forum`](../../../agents/modules/generated/website_forum.yaml) — depends_on, extends_model_from
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`website_forum`](../website_forum/overview.md), [`website_slides`](../website_slides/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
