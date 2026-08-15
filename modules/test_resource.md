---
layout: page
title: "Test - Resource (test_resource)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_resource/
nav_order: 0
---
# Test - Resource — `test_resource`

**Source:** [`agents/modules/generated/test_resource.yaml`](../../agents/modules/generated/test_resource.yaml) · **Wiki:** [`knowledge/modules/test_resource/overview.md`](../../knowledge/modules/test_resource/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_resource</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Test - Resource</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_resource</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_resource"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`resource`](resource.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>resource.test</code></div><div class="role">defined by <code>test_resource</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>resource.mixin</code></div><div class="role">extended by <code>test_resource</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.resource` | depends_on, extends_model_from | `agents/modules/generated/resource.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_resource`](../../../agents/modules/generated/test_resource.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_resource)
- Direct dependencies: [`resource`](../resource/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_resource`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `resource.test`
- Extends `resource.mixin` — defined by [`resource`](../resource/overview.md)

## Related SME agents

- [`module.resource`](../../../agents/modules/generated/resource.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`resource`](../resource/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
