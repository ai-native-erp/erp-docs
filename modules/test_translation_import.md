---
layout: page
title: "test-translation-import (test_translation_import)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_translation_import/
nav_order: 0
---
# test-translation-import — `test_translation_import`

**Source:** [`agents/modules/generated/test_translation_import.yaml`](../../agents/modules/generated/test_translation_import.yaml) · **Wiki:** [`knowledge/modules/test_translation_import/overview.md`](../../knowledge/modules/test_translation_import/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_translation_import</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">test-translation-import</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/test_translation_import</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_translation_import"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>test.translation.import.model1</code></div><div class="role">defined by <code>test_translation_import</code></div></div>
<div class="model"><div class="name"><code>test.translation.import.model2</code></div><div class="role">defined by <code>test_translation_import</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>test.translation.import.model1</code></div><div class="role">extended by <code>test_translation_import</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | depends_on | `agents/modules/generated/base.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_translation_import`](../../../agents/modules/generated/test_translation_import.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_translation_import)
- Direct dependencies: [`base`](../base/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_translation_import`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `test.translation.import.model1`
- `test.translation.import.model2`
- Extends `test.translation.import.model1` — framework/dynamic owner

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
