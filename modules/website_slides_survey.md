---
layout: page
title: "Course Certifications (website_slides_survey)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_slides_survey/
nav_order: 0
---
# Course Certifications — `website_slides_survey`

**Source:** [`agents/modules/generated/website_slides_survey.yaml`](../../agents/modules/generated/website_slides_survey.yaml) · **Wiki:** [`knowledge/modules/website_slides_survey/overview.md`](../../knowledge/modules/website_slides_survey/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_slides_survey</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Course Certifications</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_slides_survey</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_slides_survey"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Add certification capabilities to your courses

## Direct dependencies

[`survey`](survey.md), [`website_slides`](website_slides.md)

## Reverse dependencies (modules that depend on this)

[`test_website_slides_full`](test_website_slides_full.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>slide.channel</code></div><div class="role">extended by <code>website_slides_survey</code></div></div>
<div class="model"><div class="name"><code>slide.slide</code></div><div class="role">extended by <code>website_slides_survey</code></div></div>
<div class="model"><div class="name"><code>slide.slide.partner</code></div><div class="role">extended by <code>website_slides_survey</code></div></div>
<div class="model"><div class="name"><code>survey.survey</code></div><div class="role">extended by <code>website_slides_survey</code></div></div>
<div class="model"><div class="name"><code>survey.user_input</code></div><div class="role">extended by <code>website_slides_survey</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.survey` | depends_on, extends_model_from | `agents/modules/generated/survey.yaml` |
| `module.test_website_slides_full` | required_by | `agents/modules/generated/test_website_slides_full.yaml` |
| `module.website_slides` | depends_on, extends_model_from | `agents/modules/generated/website_slides.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_slides_survey`](../../../agents/modules/generated/website_slides_survey.yaml)
- Domain: `website_ecommerce`
- Category: Website/eLearning
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_slides_survey)
- Direct dependencies: [`survey`](../survey/overview.md), [`website_slides`](../website_slides/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_website_slides_full`](../test_website_slides_full/overview.md)
- Impact graph: [`module:website_slides_survey`](../../impact-graph.json)

## Purpose

Add certification capabilities to your courses

## Model relationships

- Extends `slide.channel` — defined by [`website_slides`](../website_slides/overview.md)
- Extends `slide.slide` — defined by [`website_slides`](../website_slides/overview.md)
- Extends `slide.slide.partner` — defined by [`website_slides`](../website_slides/overview.md)
- Extends `survey.survey` — defined by [`survey`](../survey/overview.md)
- Extends `survey.user_input` — defined by [`survey`](../survey/overview.md)

## Related SME agents

- [`module.survey`](../../../agents/modules/generated/survey.yaml) — depends_on, extends_model_from
- [`module.test_website_slides_full`](../../../agents/modules/generated/test_website_slides_full.yaml) — required_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`survey`](../survey/overview.md), [`website_slides`](../website_slides/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
