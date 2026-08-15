---
layout: page
title: "Test RPC (test_rpc)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_rpc/
nav_order: 0
---
# Test RPC — `test_rpc`

**Source:** [`agents/modules/generated/test_rpc.yaml`](../../agents/modules/generated/test_rpc.yaml) · **Wiki:** [`knowledge/modules/test_rpc/overview.md`](../../knowledge/modules/test_rpc/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_rpc</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Test RPC</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/test_rpc</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_rpc"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md), [`web`](web.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>test_rpc.model_a</code></div><div class="role">defined by <code>test_rpc</code></div></div>
<div class="model"><div class="name"><code>test_rpc.model_b</code></div><div class="role">defined by <code>test_rpc</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | depends_on | `agents/modules/generated/base.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_rpc`](../../../agents/modules/generated/test_rpc.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_rpc)
- Direct dependencies: [`base`](../base/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_rpc`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `test_rpc.model_a`
- `test_rpc.model_b`

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
