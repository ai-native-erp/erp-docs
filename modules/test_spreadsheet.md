---
layout: page
title: "Spreadsheet Test (test_spreadsheet)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_spreadsheet/
nav_order: 0
---
# Spreadsheet Test — `test_spreadsheet`

**Source:** [`agents/modules/generated/test_spreadsheet.yaml`](../../agents/modules/generated/test_spreadsheet.yaml) · **Wiki:** [`knowledge/modules/test_spreadsheet/overview.md`](../../knowledge/modules/test_spreadsheet/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_spreadsheet</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Spreadsheet Test</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_spreadsheet</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_spreadsheet"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Spreadsheet Test, mainly to test the mixin behavior

## Direct dependencies

[`spreadsheet`](spreadsheet.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>spreadsheet.test</code></div><div class="role">defined by <code>test_spreadsheet</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>spreadsheet.mixin</code></div><div class="role">extended by <code>test_spreadsheet</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.spreadsheet` | depends_on, extends_model_from | `agents/modules/generated/spreadsheet.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_spreadsheet`](../../../agents/modules/generated/test_spreadsheet.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_spreadsheet)
- Direct dependencies: [`spreadsheet`](../spreadsheet/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_spreadsheet`](../../impact-graph.json)

## Purpose

Spreadsheet Test, mainly to test the mixin behavior

## Model relationships

- `spreadsheet.test`
- Extends `spreadsheet.mixin` — defined by [`spreadsheet`](../spreadsheet/overview.md)

## Related SME agents

- [`module.spreadsheet`](../../../agents/modules/generated/spreadsheet.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`spreadsheet`](../spreadsheet/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
