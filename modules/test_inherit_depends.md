---
layout: page
title: "test-inherit-depends (test_inherit_depends)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_inherit_depends/
nav_order: 0
---
# test-inherit-depends — `test_inherit_depends`

**Source:** [`agents/modules/generated/test_inherit_depends.yaml`](../../agents/modules/generated/test_inherit_depends.yaml) · **Wiki:** [`knowledge/modules/test_inherit_depends/overview.md`](../../knowledge/modules/test_inherit_depends/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_inherit_depends</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">test-inherit-depends</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/test_inherit_depends</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_inherit_depends"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`test_inherit`](test_inherit.md), [`test_new_api`](test_new_api.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>test_new_api.foo</code></div><div class="role">defined by <code>test_inherit_depends</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>test_inherit.mixin</code></div><div class="role">extended by <code>test_inherit_depends</code></div></div>
<div class="model"><div class="name"><code>test_new_api.foo</code></div><div class="role">extended by <code>test_inherit_depends</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.test_inherit` | depends_on, extends_model_from | `agents/modules/generated/test_inherit.yaml` |
| `module.test_new_api` | depends_on, extends_model_from | `agents/modules/generated/test_new_api.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_inherit_depends`](../../../agents/modules/generated/test_inherit_depends.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_inherit_depends)
- Direct dependencies: [`test_inherit`](../test_inherit/overview.md), [`test_new_api`](../test_new_api/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_inherit_depends`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `test_new_api.foo`
- Extends `test_inherit.mixin` — defined by [`test_inherit`](../test_inherit/overview.md)
- Extends `test_new_api.foo` — defined by [`test_new_api`](../test_new_api/overview.md)

## Related SME agents

- [`module.test_inherit`](../../../agents/modules/generated/test_inherit.yaml) — depends_on, extends_model_from
- [`module.test_new_api`](../../../agents/modules/generated/test_new_api.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`test_inherit`](../test_inherit/overview.md), [`test_new_api`](../test_new_api/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
