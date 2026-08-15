---
layout: page
title: "test-inherits (test_inherits)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_inherits/
nav_order: 0
---
# test-inherits — `test_inherits`

**Source:** [`agents/modules/generated/test_inherits.yaml`](../../agents/modules/generated/test_inherits.yaml) · **Wiki:** [`knowledge/modules/test_inherits/overview.md`](../../knowledge/modules/test_inherits/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_inherits</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">test-inherits</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/test_inherits</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_inherits"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md)

## Reverse dependencies (modules that depend on this)

[`test_inherits_depends`](test_inherits_depends.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>test.another_box</code></div><div class="role">defined by <code>test_inherits</code></div></div>
<div class="model"><div class="name"><code>test.another_unit</code></div><div class="role">defined by <code>test_inherits</code></div></div>
<div class="model"><div class="name"><code>test.box</code></div><div class="role">defined by <code>test_inherits</code></div></div>
<div class="model"><div class="name"><code>test.pallet</code></div><div class="role">defined by <code>test_inherits</code></div></div>
<div class="model"><div class="name"><code>test.unit</code></div><div class="role">defined by <code>test_inherits</code></div></div>
<div class="model"><div class="name"><code>test.unit.line</code></div><div class="role">defined by <code>test_inherits</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>test.another_unit</code></div><div class="role">extended by <code>test_inherits</code></div></div>
<div class="model"><div class="name"><code>test.box</code></div><div class="role">extended by <code>test_inherits</code></div></div>
<div class="model"><div class="name"><code>test.unit</code></div><div class="role">extended by <code>test_inherits</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | depends_on | `agents/modules/generated/base.yaml` |
| `module.test_inherits_depends` | model_extended_by, required_by | `agents/modules/generated/test_inherits_depends.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_inherits`](../../../agents/modules/generated/test_inherits.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_inherits)
- Direct dependencies: [`base`](../base/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_inherits_depends`](../test_inherits_depends/overview.md)
- Impact graph: [`module:test_inherits`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `test.another_box`
- `test.another_unit`
- `test.box`
- `test.pallet`
- `test.unit` — extended by [`test_inherits_depends`](../test_inherits_depends/overview.md)
- `test.unit.line`
- Extends `test.another_unit` — framework/dynamic owner
- Extends `test.box` — framework/dynamic owner
- Extends `test.unit` — framework/dynamic owner

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on
- [`module.test_inherits_depends`](../../../agents/modules/generated/test_inherits_depends.yaml) — model_extended_by, required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`test_inherits_depends`](../test_inherits_depends/overview.md).
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
