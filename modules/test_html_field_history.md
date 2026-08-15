---
layout: page
title: "Test - html_field_history (test_html_field_history)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_html_field_history/
nav_order: 0
---
# Test - html_field_history — `test_html_field_history`

**Source:** [`agents/modules/generated/test_html_field_history.yaml`](../../agents/modules/generated/test_html_field_history.yaml) · **Wiki:** [`knowledge/modules/test_html_field_history/overview.md`](../../knowledge/modules/test_html_field_history/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_html_field_history</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Test - html_field_history</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_html_field_history</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_html_field_history"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`web_editor`](web_editor.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>html.field.history.test</code></div><div class="role">defined by <code>test_html_field_history</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>html.field.history.mixin</code></div><div class="role">extended by <code>test_html_field_history</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.web_editor` | depends_on, extends_model_from | `agents/modules/generated/web_editor.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_html_field_history`](../../../agents/modules/generated/test_html_field_history.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_html_field_history)
- Direct dependencies: [`web_editor`](../web_editor/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_html_field_history`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `html.field.history.test`
- Extends `html.field.history.mixin` — defined by [`web_editor`](../web_editor/overview.md)

## Related SME agents

- [`module.web_editor`](../../../agents/modules/generated/web_editor.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`web_editor`](../web_editor/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
