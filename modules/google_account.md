---
layout: page
title: "Google Users (google_account)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/google_account/
nav_order: 0
---
# Google Users — `google_account`

**Source:** [`agents/modules/generated/google_account.yaml`](../../agents/modules/generated/google_account.yaml) · **Wiki:** [`knowledge/modules/google_account/overview.md`](../../knowledge/modules/google_account/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>google_account</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Google Users</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">integrations</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/google_account</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/google_account"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base_setup`](base_setup.md)

## Reverse dependencies (modules that depend on this)

[`google_calendar`](google_calendar.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>google.service</code></div><div class="role">defined by <code>google_account</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base_setup` | depends_on | `agents/modules/generated/base_setup.yaml` |
| `module.google_calendar` | required_by | `agents/modules/generated/google_calendar.yaml` |

## Full wiki excerpt

- SME owner: [`module.google_account`](../../../agents/modules/generated/google_account.yaml)
- Domain: `integrations`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/google_account)
- Direct dependencies: [`base_setup`](../base_setup/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`google_calendar`](../google_calendar/overview.md)
- Impact graph: [`module:google_account`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `google.service`

## Related SME agents

- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on
- [`module.google_calendar`](../../../agents/modules/generated/google_calendar.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
