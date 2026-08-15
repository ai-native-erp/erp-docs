---
layout: page
title: "Data Recycle (data_recycle)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/data_recycle/
nav_order: 0
---
# Data Recycle — `data_recycle`

**Source:** [`agents/modules/generated/data_recycle.yaml`](../../agents/modules/generated/data_recycle.yaml) · **Wiki:** [`knowledge/modules/data_recycle/overview.md`](../../knowledge/modules/data_recycle/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>data_recycle</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Data Recycle</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/data_recycle</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/data_recycle"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Find old records and archive/delete them

## Direct dependencies

[`mail`](mail.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>data_recycle.model</code></div><div class="role">defined by <code>data_recycle</code></div></div>
<div class="model"><div class="name"><code>data_recycle.record</code></div><div class="role">defined by <code>data_recycle</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mail` | depends_on | `agents/modules/generated/mail.yaml` |

## Full wiki excerpt

- SME owner: [`module.data_recycle`](../../../agents/modules/generated/data_recycle.yaml)
- Domain: `platform_core`
- Category: Productivity/Data Cleaning
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/data_recycle)
- Direct dependencies: [`mail`](../mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:data_recycle`](../../impact-graph.json)

## Purpose

Find old records and archive/delete them

## Model relationships

- `data_recycle.model`
- `data_recycle.record`

## Related SME agents

- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
