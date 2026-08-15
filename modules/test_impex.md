---
layout: page
title: "test-import-export (test_impex)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_impex/
nav_order: 0
---
# test-import-export — `test_impex`

**Source:** [`agents/modules/generated/test_impex.yaml`](../../agents/modules/generated/test_impex.yaml) · **Wiki:** [`knowledge/modules/test_impex/overview.md`](../../knowledge/modules/test_impex/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_impex</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">test-import-export</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/test_impex</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_impex"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>export.inherits.child</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.inherits.parent</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.m2o.str</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.m2o.str.child</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.many2many.other</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.many2one.required.subfield</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.one2many.child</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.one2many.child.1</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.one2many.child.2</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.one2many.multiple</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.one2many.multiple.child</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.one2many.recursive</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.selection.withdefault</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.unique</code></div><div class="role">defined by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.with.required.field</code></div><div class="role">defined by <code>test_impex</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>export.inherits.parent</code></div><div class="role">extended by <code>test_impex</code></div></div>
<div class="model"><div class="name"><code>export.one2many.multiple.child</code></div><div class="role">extended by <code>test_impex</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | depends_on | `agents/modules/generated/base.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_impex`](../../../agents/modules/generated/test_impex.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_impex)
- Direct dependencies: [`base`](../base/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_impex`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `export.inherits.child`
- `export.inherits.parent`
- `export.m2o.str`
- `export.m2o.str.child`
- `export.many2many.other`
- `export.many2one.required.subfield`
- `export.one2many.child`
- `export.one2many.child.1`
- `export.one2many.child.2`
- `export.one2many.multiple`
- `export.one2many.multiple.child`
- `export.one2many.recursive`
- `export.selection.withdefault`
- `export.unique`
- `export.with.required.field`
- Extends `export.inherits.parent` — framework/dynamic owner
- Extends `export.one2many.multiple.child` — framework/dynamic owner

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
