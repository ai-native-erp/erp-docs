---
layout: page
title: "Online Task Submission (website_form_project)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_form_project/
nav_order: 0
---
# Online Task Submission — `website_form_project`

**Source:** [`agents/modules/generated/website_form_project.yaml`](../../agents/modules/generated/website_form_project.yaml) · **Wiki:** [`knowledge/modules/website_form_project/overview.md`](../../knowledge/modules/website_form_project/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_form_project</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Online Task Submission</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_form_project</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_form_project"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Add a task suggestion form to your website

## Direct dependencies

[`project`](project.md), [`website`](website.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.project` | depends_on | `agents/modules/generated/project.yaml` |
| `module.website` | depends_on | `agents/modules/generated/website.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_form_project`](../../../agents/modules/generated/website_form_project.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_form_project)
- Direct dependencies: [`project`](../project/overview.md), [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_form_project`](../../impact-graph.json)

## Purpose

Add a task suggestion form to your website

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.project`](../../../agents/modules/generated/project.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
