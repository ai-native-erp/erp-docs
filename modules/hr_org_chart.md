---
layout: page
title: "HR Org Chart (hr_org_chart)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_org_chart/
nav_order: 0
---
# HR Org Chart — `hr_org_chart`

**Source:** [`agents/modules/generated/hr_org_chart.yaml`](../../agents/modules/generated/hr_org_chart.yaml) · **Wiki:** [`knowledge/modules/hr_org_chart/overview.md`](../../knowledge/modules/hr_org_chart/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_org_chart</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">HR Org Chart</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_org_chart</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_org_chart"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`hr`](hr.md), [`web_hierarchy`](web_hierarchy.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr_org_chart</code></div></div>
<div class="model"><div class="name"><code>hr.employee.base</code></div><div class="role">extended by <code>hr_org_chart</code></div></div>
<div class="model"><div class="name"><code>hr.employee.public</code></div><div class="role">extended by <code>hr_org_chart</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.web_hierarchy` | depends_on | `agents/modules/generated/web_hierarchy.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_org_chart`](../../../agents/modules/generated/hr_org_chart.yaml)
- Domain: `human_resources`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_org_chart)
- Direct dependencies: [`hr`](../hr/overview.md), [`web_hierarchy`](../web_hierarchy/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:hr_org_chart`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee.base` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee.public` — defined by [`hr`](../hr/overview.md)

## Related SME agents

- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.web_hierarchy`](../../../agents/modules/generated/web_hierarchy.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`hr`](../hr/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
