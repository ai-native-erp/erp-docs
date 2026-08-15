---
layout: page
title: "Recruitment - SMS (hr_recruitment_sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_recruitment_sms/
nav_order: 0
---
# Recruitment - SMS — `hr_recruitment_sms`

**Source:** [`agents/modules/generated/hr_recruitment_sms.yaml`](../../agents/modules/generated/hr_recruitment_sms.yaml) · **Wiki:** [`knowledge/modules/hr_recruitment_sms/overview.md`](../../knowledge/modules/hr_recruitment_sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_recruitment_sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Recruitment - SMS</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_recruitment_sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_recruitment_sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Mass mailing sms to job applicants

## Direct dependencies

[`hr_recruitment`](hr_recruitment.md), [`sms`](sms.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr_recruitment` | depends_on | `agents/modules/generated/hr_recruitment.yaml` |
| `module.sms` | depends_on | `agents/modules/generated/sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_recruitment_sms`](../../../agents/modules/generated/hr_recruitment_sms.yaml)
- Domain: `human_resources`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_recruitment_sms)
- Direct dependencies: [`hr_recruitment`](../hr_recruitment/overview.md), [`sms`](../sms/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:hr_recruitment_sms`](../../impact-graph.json)

## Purpose

Mass mailing sms to job applicants

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — depends_on
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
