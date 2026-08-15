---
layout: page
title: "Hr Recruitment Interview Forms (hr_recruitment_survey)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_recruitment_survey/
nav_order: 0
---
# Hr Recruitment Interview Forms — `hr_recruitment_survey`

**Source:** [`agents/modules/generated/hr_recruitment_survey.yaml`](../../agents/modules/generated/hr_recruitment_survey.yaml) · **Wiki:** [`knowledge/modules/hr_recruitment_survey/overview.md`](../../knowledge/modules/hr_recruitment_survey/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_recruitment_survey</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Hr Recruitment Interview Forms</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_recruitment_survey</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_recruitment_survey"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Surveys

## Direct dependencies

[`hr_recruitment`](hr_recruitment.md), [`survey`](survey.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.applicant</code></div><div class="role">extended by <code>hr_recruitment_survey</code></div></div>
<div class="model"><div class="name"><code>hr.job</code></div><div class="role">extended by <code>hr_recruitment_survey</code></div></div>
<div class="model"><div class="name"><code>survey.invite</code></div><div class="role">extended by <code>hr_recruitment_survey</code></div></div>
<div class="model"><div class="name"><code>survey.user_input</code></div><div class="role">extended by <code>hr_recruitment_survey</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr` | extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.hr_recruitment` | depends_on, extends_model_from | `agents/modules/generated/hr_recruitment.yaml` |
| `module.survey` | depends_on, extends_model_from | `agents/modules/generated/survey.yaml` |
| `module.website_hr_recruitment` | extends_model_from | `agents/modules/generated/website_hr_recruitment.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_recruitment_survey`](../../../agents/modules/generated/hr_recruitment_survey.yaml)
- Domain: `human_resources`
- Category: Human Resources
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_recruitment_survey)
- Direct dependencies: [`hr_recruitment`](../hr_recruitment/overview.md), [`survey`](../survey/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:hr_recruitment_survey`](../../impact-graph.json)

## Purpose

Surveys

## Model relationships

- Extends `hr.applicant` — defined by [`hr_recruitment`](../hr_recruitment/overview.md)
- Extends `hr.job` — defined by [`hr`](../hr/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md)
- Extends `survey.invite` — defined by [`survey`](../survey/overview.md)
- Extends `survey.user_input` — defined by [`survey`](../survey/overview.md)

## Related SME agents

- [`module.hr`](../../../agents/modules/generated/hr.yaml) — extends_model_from
- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — depends_on, extends_model_from
- [`module.survey`](../../../agents/modules/generated/survey.yaml) — depends_on, extends_model_from
- [`module.website_hr_recruitment`](../../../agents/modules/generated/website_hr_recruitment.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`hr`](../hr/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`survey`](../survey/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
