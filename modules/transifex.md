---
layout: page
title: "Transifex integration (transifex)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/transifex/
nav_order: 0
---
# Transifex integration — `transifex`

**Source:** [`agents/modules/generated/transifex.yaml`](../../agents/modules/generated/transifex.yaml) · **Wiki:** [`knowledge/modules/transifex/overview.md`](../../knowledge/modules/transifex/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>transifex</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Transifex integration</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/transifex</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/transifex"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Add a link to edit a translation in Transifex

## Direct dependencies

[`base`](base.md), [`web`](web.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>transifex.code.translation</code></div><div class="role">defined by <code>transifex</code></div></div>
<div class="model"><div class="name"><code>transifex.translation</code></div><div class="role">defined by <code>transifex</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>base</code></div><div class="role">extended by <code>transifex</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |

## Full wiki excerpt

- SME owner: [`module.transifex`](../../../agents/modules/generated/transifex.yaml)
- Domain: `platform_core`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/transifex)
- Direct dependencies: [`base`](../base/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:transifex`](../../impact-graph.json)

## Purpose

Add a link to edit a translation in Transifex

## Model relationships

- `transifex.code.translation`
- `transifex.translation`
- Extends `base` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
