---
layout: page
title: "Base import module (base_import_module)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/base_import_module/
nav_order: 0
---
# Base import module — `base_import_module`

**Source:** [`agents/modules/generated/base_import_module.yaml`](../../agents/modules/generated/base_import_module.yaml) · **Wiki:** [`knowledge/modules/base_import_module/overview.md`](../../knowledge/modules/base_import_module/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base_import_module</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Base import module</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/base_import_module</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base_import_module"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`web`](web.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>base.import.module</code></div><div class="role">defined by <code>base_import_module</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>base.module.uninstall</code></div><div class="role">extended by <code>base_import_module</code></div></div>
<div class="model"><div class="name"><code>ir.module.module</code></div><div class="role">extended by <code>base_import_module</code></div></div>
<div class="model"><div class="name"><code>ir.ui.view</code></div><div class="role">extended by <code>base_import_module</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |

## Full wiki excerpt

- SME owner: [`module.base_import_module`](../../../agents/modules/generated/base_import_module.yaml)
- Domain: `platform_core`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base_import_module)
- Direct dependencies: [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:base_import_module`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `base.import.module`
- Extends `base.module.uninstall` — defined by [`base`](../base/overview.md)
- Extends `ir.module.module` — defined by [`base`](../base/overview.md), [`website`](../website/overview.md)
- Extends `ir.ui.view` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
