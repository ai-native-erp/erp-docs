---
layout: page
title: "Attachments List and Document Indexation (attachment_indexation)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/attachment_indexation/
nav_order: 0
---
# Attachments List and Document Indexation — `attachment_indexation`

**Source:** [`agents/modules/generated/attachment_indexation.yaml`](../../agents/modules/generated/attachment_indexation.yaml) · **Wiki:** [`knowledge/modules/attachment_indexation/overview.md`](../../knowledge/modules/attachment_indexation/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>attachment_indexation</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Attachments List and Document Indexation</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/attachment_indexation</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/attachment_indexation"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`hr_recruitment`](hr_recruitment.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>attachment_indexation</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.hr_recruitment` | required_by | `agents/modules/generated/hr_recruitment.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |

## Full wiki excerpt

- SME owner: [`module.attachment_indexation`](../../../agents/modules/generated/attachment_indexation.yaml)
- Domain: `platform_core`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/attachment_indexation)
- Direct dependencies: [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_recruitment`](../hr_recruitment/overview.md)
- Impact graph: [`module:attachment_indexation`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `ir.attachment` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
