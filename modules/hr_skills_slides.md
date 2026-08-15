---
layout: page
title: "Skills e-learning (hr_skills_slides)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_skills_slides/
nav_order: 0
---
# Skills e-learning — `hr_skills_slides`

**Source:** [`agents/modules/generated/hr_skills_slides.yaml`](../../agents/modules/generated/hr_skills_slides.yaml) · **Wiki:** [`knowledge/modules/hr_skills_slides/overview.md`](../../knowledge/modules/hr_skills_slides/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_skills_slides</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Skills e-learning</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_skills_slides</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_skills_slides"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Add completed courses to resume of your employees

## Direct dependencies

[`hr_skills`](hr_skills.md), [`website_slides`](website_slides.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr_skills_slides</code></div></div>
<div class="model"><div class="name"><code>hr.resume.line</code></div><div class="role">extended by <code>hr_skills_slides</code></div></div>
<div class="model"><div class="name"><code>slide.channel</code></div><div class="role">extended by <code>hr_skills_slides</code></div></div>
<div class="model"><div class="name"><code>slide.channel.partner</code></div><div class="role">extended by <code>hr_skills_slides</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr` | extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.hr_skills` | depends_on, extends_model_from | `agents/modules/generated/hr_skills.yaml` |
| `module.website_slides` | depends_on, extends_model_from | `agents/modules/generated/website_slides.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_skills_slides`](../../../agents/modules/generated/hr_skills_slides.yaml)
- Domain: `human_resources`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_skills_slides)
- Direct dependencies: [`hr_skills`](../hr_skills/overview.md), [`website_slides`](../website_slides/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:hr_skills_slides`](../../impact-graph.json)

## Purpose

Add completed courses to resume of your employees

## Model relationships

- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `hr.resume.line` — defined by [`hr_skills`](../hr_skills/overview.md)
- Extends `slide.channel` — defined by [`website_slides`](../website_slides/overview.md)
- Extends `slide.channel.partner` — defined by [`website_slides`](../website_slides/overview.md)

## Related SME agents

- [`module.hr`](../../../agents/modules/generated/hr.yaml) — extends_model_from
- [`module.hr_skills`](../../../agents/modules/generated/hr_skills.yaml) — depends_on, extends_model_from
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`hr`](../hr/overview.md), [`hr_skills`](../hr_skills/overview.md), [`website_slides`](../website_slides/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
