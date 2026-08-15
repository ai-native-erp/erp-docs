---
layout: page
title: "Maintenance (maintenance)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/maintenance/
nav_order: 0
---
# Maintenance — `maintenance`

**Source:** [`agents/modules/generated/maintenance.yaml`](../../agents/modules/generated/maintenance.yaml) · **Wiki:** [`knowledge/modules/maintenance/overview.md`](../../knowledge/modules/maintenance/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>maintenance</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Maintenance</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">manufacturing</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/maintenance</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/maintenance"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Track equipment and manage maintenance requests

## Direct dependencies

[`mail`](mail.md)

## Reverse dependencies (modules that depend on this)

[`hr_maintenance`](hr_maintenance.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>maintenance.equipment</code></div><div class="role">defined by <code>maintenance</code></div></div>
<div class="model"><div class="name"><code>maintenance.equipment.category</code></div><div class="role">defined by <code>maintenance</code></div></div>
<div class="model"><div class="name"><code>maintenance.mixin</code></div><div class="role">defined by <code>maintenance</code></div></div>
<div class="model"><div class="name"><code>maintenance.request</code></div><div class="role">defined by <code>maintenance</code></div></div>
<div class="model"><div class="name"><code>maintenance.stage</code></div><div class="role">defined by <code>maintenance</code></div></div>
<div class="model"><div class="name"><code>maintenance.team</code></div><div class="role">defined by <code>maintenance</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>maintenance</code></div></div>
<div class="model"><div class="name"><code>mail.alias.mixin</code></div><div class="role">extended by <code>maintenance</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>maintenance</code></div></div>
<div class="model"><div class="name"><code>mail.thread.cc</code></div><div class="role">extended by <code>maintenance</code></div></div>
<div class="model"><div class="name"><code>maintenance.mixin</code></div><div class="role">extended by <code>maintenance</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>maintenance</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.hr_maintenance` | model_extended_by, required_by | `agents/modules/generated/hr_maintenance.yaml` |
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |

## Full wiki excerpt

- SME owner: [`module.maintenance`](../../../agents/modules/generated/maintenance.yaml)
- Domain: `manufacturing`
- Category: Manufacturing/Maintenance
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/maintenance)
- Direct dependencies: [`mail`](../mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_maintenance`](../hr_maintenance/overview.md)
- Impact graph: [`module:maintenance`](../../impact-graph.json)

## Purpose

Track equipment and manage maintenance requests

## Model relationships

- `maintenance.equipment` — extended by [`hr_maintenance`](../hr_maintenance/overview.md)
- `maintenance.equipment.category`
- `maintenance.mixin`
- `maintenance.request` — extended by [`hr_maintenance`](../hr_maintenance/overview.md)
- `maintenance.stage`
- `maintenance.team`
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.alias.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.cc` — defined by [`mail`](../mail/overview.md)
- Extends `maintenance.mixin` — framework/dynamic owner
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.hr_maintenance`](../../../agents/modules/generated/hr_maintenance.yaml) — model_extended_by, required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr_maintenance`](../hr_maintenance/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`mail`](../mail/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
