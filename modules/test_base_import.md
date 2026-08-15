---
layout: page
title: "Test - Base Import (test_base_import)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_base_import/
nav_order: 0
---
# Test - Base Import — `test_base_import`

**Source:** [`agents/modules/generated/test_base_import.yaml`](../../agents/modules/generated/test_base_import.yaml) · **Wiki:** [`knowledge/modules/test_base_import/overview.md`](../../knowledge/modules/test_base_import/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_base_import</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Test - Base Import</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_base_import</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_base_import"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Base Import Tests: Ensure Flow Robustness

## Direct dependencies

[`base_import`](base_import.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base_import` | depends_on | `agents/modules/generated/base_import.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_base_import`](../../../agents/modules/generated/test_base_import.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_base_import)
- Direct dependencies: [`base_import`](../base_import/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_base_import`](../../impact-graph.json)

## Purpose

Base Import Tests: Ensure Flow Robustness

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.base_import`](../../../agents/modules/generated/base_import.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
