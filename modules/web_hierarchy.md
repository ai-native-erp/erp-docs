---
layout: page
title: "Web Hierarchy (web_hierarchy)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/web_hierarchy/
nav_order: 0
---
# Web Hierarchy — `web_hierarchy`

**Source:** [`agents/modules/generated/web_hierarchy.yaml`](../../agents/modules/generated/web_hierarchy.yaml) · **Wiki:** [`knowledge/modules/web_hierarchy/overview.md`](../../knowledge/modules/web_hierarchy/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>web_hierarchy</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Web Hierarchy</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/web_hierarchy</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/web_hierarchy"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`hr_org_chart`](hr_org_chart.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>base</code></div><div class="role">extended by <code>web_hierarchy</code></div></div>
<div class="model"><div class="name"><code>ir.actions.act_window.view</code></div><div class="role">extended by <code>web_hierarchy</code></div></div>
<div class="model"><div class="name"><code>ir.ui.view</code></div><div class="role">extended by <code>web_hierarchy</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.hr_org_chart` | required_by | `agents/modules/generated/hr_org_chart.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |

## Full wiki excerpt

- SME owner: [`module.web_hierarchy`](../../../agents/modules/generated/web_hierarchy.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/web_hierarchy)
- Direct dependencies: [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_org_chart`](../hr_org_chart/overview.md)
- Impact graph: [`module:web_hierarchy`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `base` — defined by [`base`](../base/overview.md)
- Extends `ir.actions.act_window.view` — defined by [`base`](../base/overview.md)
- Extends `ir.ui.view` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.hr_org_chart`](../../../agents/modules/generated/hr_org_chart.yaml) — required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
