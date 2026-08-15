---
layout: page
title: "test module to test data only modules (test_data_module)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_data_module/
nav_order: 0
---
# test module to test data only modules — `test_data_module`

**Source:** [`agents/modules/generated/test_data_module.yaml`](../../agents/modules/generated/test_data_module.yaml) · **Wiki:** [`knowledge/modules/test_data_module/overview.md`](../../knowledge/modules/test_data_module/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_data_module</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">test module to test data only modules</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/test_data_module</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_data_module"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Reverse dependencies (modules that depend on this)

[`test_data_module_install`](test_data_module_install.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.test_data_module_install` | required_by | `agents/modules/generated/test_data_module_install.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_data_module`](../../../agents/modules/generated/test_data_module.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_data_module)
- Direct dependencies: None
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_data_module_install`](../test_data_module_install/overview.md)
- Impact graph: [`module:test_data_module`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.test_data_module_install`](../../../agents/modules/generated/test_data_module_install.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
