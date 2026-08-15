---
layout: page
title: "test-inherits-depends (test_inherits_depends)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_inherits_depends/
nav_order: 0
---
# test-inherits-depends — `test_inherits_depends`

**Source:** [`agents/modules/generated/test_inherits_depends.yaml`](../../agents/modules/generated/test_inherits_depends.yaml) · **Wiki:** [`knowledge/modules/test_inherits_depends/overview.md`](../../knowledge/modules/test_inherits_depends/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_inherits_depends</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">test-inherits-depends</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/test_inherits_depends</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_inherits_depends"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`test_inherits`](test_inherits.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>test.unit</code></div><div class="role">extended by <code>test_inherits_depends</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.test_inherits` | depends_on, extends_model_from | `agents/modules/generated/test_inherits.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_inherits_depends`](../../../agents/modules/generated/test_inherits_depends.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_inherits_depends)
- Direct dependencies: [`test_inherits`](../test_inherits/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_inherits_depends`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `test.unit` — defined by [`test_inherits`](../test_inherits/overview.md)

## Related SME agents

- [`module.test_inherits`](../../../agents/modules/generated/test_inherits.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`test_inherits`](../test_inherits/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
