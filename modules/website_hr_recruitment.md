---
layout: page
title: "Online Jobs (website_hr_recruitment)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_hr_recruitment/
nav_order: 0
---
# Online Jobs — `website_hr_recruitment`

**Source:** [`agents/modules/generated/website_hr_recruitment.yaml`](../../agents/modules/generated/website_hr_recruitment.yaml) · **Wiki:** [`knowledge/modules/website_hr_recruitment/overview.md`](../../knowledge/modules/website_hr_recruitment/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_hr_recruitment</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Online Jobs</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_hr_recruitment</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_hr_recruitment"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage your online hiring process

## Direct dependencies

[`hr_recruitment`](hr_recruitment.md), [`website_mail`](website_mail.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.job</code></div><div class="role">defined by <code>website_hr_recruitment</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.applicant</code></div><div class="role">extended by <code>website_hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.department</code></div><div class="role">extended by <code>website_hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.job</code></div><div class="role">extended by <code>website_hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>hr.recruitment.source</code></div><div class="role">extended by <code>website_hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>website.published.multi.mixin</code></div><div class="role">extended by <code>website_hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>website.searchable.mixin</code></div><div class="role">extended by <code>website_hr_recruitment</code></div></div>
<div class="model"><div class="name"><code>website.seo.metadata</code></div><div class="role">extended by <code>website_hr_recruitment</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr` | extends_model_from, model_extended_by | `agents/modules/generated/hr.yaml` |
| `module.hr_recruitment` | depends_on, extends_model_from, model_extended_by | `agents/modules/generated/hr_recruitment.yaml` |
| `module.hr_recruitment_survey` | model_extended_by | `agents/modules/generated/hr_recruitment_survey.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_mail` | depends_on | `agents/modules/generated/website_mail.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_hr_recruitment`](../../../agents/modules/generated/website_hr_recruitment.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_hr_recruitment)
- Direct dependencies: [`hr_recruitment`](../hr_recruitment/overview.md), [`website_mail`](../website_mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_hr_recruitment`](../../impact-graph.json)

## Purpose

Manage your online hiring process

## Model relationships

- `hr.job` — extended by [`hr`](../hr/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_recruitment_survey`](../hr_recruitment_survey/overview.md)
- Extends `hr.applicant` — defined by [`hr_recruitment`](../hr_recruitment/overview.md)
- Extends `hr.department` — defined by [`hr`](../hr/overview.md)
- Extends `hr.job` — defined by [`hr`](../hr/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md)
- Extends `hr.recruitment.source` — defined by [`hr_recruitment`](../hr_recruitment/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)
- Extends `website.published.multi.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.searchable.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.seo.metadata` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.hr`](../../../agents/modules/generated/hr.yaml) — extends_model_from, model_extended_by
- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.hr_recruitment_survey`](../../../agents/modules/generated/hr_recruitment_survey.yaml) — model_extended_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_mail`](../../../agents/modules/generated/website_mail.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr`](../hr/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_recruitment_survey`](../hr_recruitment_survey/overview.md).
- Review model owners used by this module: [`hr`](../hr/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl, qa_upgrade.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
