---
layout: page
title: "HR - Livechat (hr_livechat)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_livechat/
nav_order: 0
---
# HR - Livechat — `hr_livechat`

**Source:** [`agents/modules/generated/hr_livechat.yaml`](../../agents/modules/generated/hr_livechat.yaml) · **Wiki:** [`knowledge/modules/hr_livechat/overview.md`](../../knowledge/modules/hr_livechat/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_livechat</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">HR - Livechat</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_livechat</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_livechat"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`hr`](hr.md), [`im_livechat`](im_livechat.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr` | depends_on | `agents/modules/generated/hr.yaml` |
| `module.im_livechat` | depends_on | `agents/modules/generated/im_livechat.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_livechat`](../../../agents/modules/generated/hr_livechat.yaml)
- Domain: `human_resources`
- Category: Human Resources
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_livechat)
- Direct dependencies: [`hr`](../hr/overview.md), [`im_livechat`](../im_livechat/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:hr_livechat`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
