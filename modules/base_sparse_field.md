---
layout: page
title: "Sparse Fields (base_sparse_field)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/base_sparse_field/
nav_order: 0
---
# Sparse Fields — `base_sparse_field`

**Source:** [`agents/modules/generated/base_sparse_field.yaml`](../../agents/modules/generated/base_sparse_field.yaml) · **Wiki:** [`knowledge/modules/base_sparse_field/overview.md`](../../knowledge/modules/base_sparse_field/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base_sparse_field</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sparse Fields</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/base_sparse_field</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base_sparse_field"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Implementation of sparse fields.

## Direct dependencies

[`base`](base.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>sparse_fields.test</code></div><div class="role">defined by <code>base_sparse_field</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>base</code></div><div class="role">extended by <code>base_sparse_field</code></div></div>
<div class="model"><div class="name"><code>ir.model.fields</code></div><div class="role">extended by <code>base_sparse_field</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |

## Full wiki excerpt

- SME owner: [`module.base_sparse_field`](../../../agents/modules/generated/base_sparse_field.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base_sparse_field)
- Direct dependencies: [`base`](../base/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:base_sparse_field`](../../impact-graph.json)

## Purpose

Implementation of sparse fields.

## Model relationships

- `sparse_fields.test`
- Extends `base` — defined by [`base`](../base/overview.md)
- Extends `ir.model.fields` — defined by [`base`](../base/overview.md), [`website`](../website/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
