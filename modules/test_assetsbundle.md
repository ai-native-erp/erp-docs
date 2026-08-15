---
layout: page
title: "test-assetsbundle (test_assetsbundle)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_assetsbundle/
nav_order: 0
---
# test-assetsbundle — `test_assetsbundle`

**Source:** [`agents/modules/generated/test_assetsbundle.yaml`](../../agents/modules/generated/test_assetsbundle.yaml) · **Wiki:** [`knowledge/modules/test_assetsbundle/overview.md`](../../knowledge/modules/test_assetsbundle/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_assetsbundle</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">test-assetsbundle</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/test_assetsbundle</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_assetsbundle"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.qweb</code></div><div class="role">extended by <code>test_assetsbundle</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_assetsbundle`](../../../agents/modules/generated/test_assetsbundle.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_assetsbundle)
- Direct dependencies: [`base`](../base/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_assetsbundle`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `ir.qweb` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
