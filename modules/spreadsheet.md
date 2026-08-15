---
layout: page
title: "Spreadsheet (spreadsheet)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/spreadsheet/
nav_order: 0
---
# Spreadsheet — `spreadsheet`

**Source:** [`agents/modules/generated/spreadsheet.yaml`](../../agents/modules/generated/spreadsheet.yaml) · **Wiki:** [`knowledge/modules/spreadsheet/overview.md`](../../knowledge/modules/spreadsheet/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>spreadsheet</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Spreadsheet</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/spreadsheet</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/spreadsheet"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Spreadsheet

## Direct dependencies

[`bus`](bus.md), [`portal`](portal.md), [`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`spreadsheet_account`](spreadsheet_account.md), [`spreadsheet_dashboard`](spreadsheet_dashboard.md), [`test_spreadsheet`](test_spreadsheet.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>spreadsheet.mixin</code></div><div class="role">defined by <code>spreadsheet</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.currency</code></div><div class="role">extended by <code>spreadsheet</code></div></div>
<div class="model"><div class="name"><code>res.currency.rate</code></div><div class="role">extended by <code>spreadsheet</code></div></div>
<div class="model"><div class="name"><code>res.lang</code></div><div class="role">extended by <code>spreadsheet</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.bus` | depends_on | `agents/modules/generated/bus.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.portal` | depends_on | `agents/modules/generated/portal.yaml` |
| `module.spreadsheet_account` | required_by | `agents/modules/generated/spreadsheet_account.yaml` |
| `module.spreadsheet_dashboard` | model_extended_by, required_by | `agents/modules/generated/spreadsheet_dashboard.yaml` |
| `module.test_spreadsheet` | model_extended_by, required_by | `agents/modules/generated/test_spreadsheet.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |

## Full wiki excerpt

- SME owner: [`module.spreadsheet`](../../../agents/modules/generated/spreadsheet.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/spreadsheet)
- Direct dependencies: [`bus`](../bus/overview.md), [`portal`](../portal/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`spreadsheet_account`](../spreadsheet_account/overview.md), [`spreadsheet_dashboard`](../spreadsheet_dashboard/overview.md), [`test_spreadsheet`](../test_spreadsheet/overview.md)
- Impact graph: [`module:spreadsheet`](../../impact-graph.json)

## Purpose

Spreadsheet

## Model relationships

- `spreadsheet.mixin` — extended by [`spreadsheet_dashboard`](../spreadsheet_dashboard/overview.md), [`test_spreadsheet`](../test_spreadsheet/overview.md)
- Extends `res.currency` — defined by [`base`](../base/overview.md), [`l10n_cl`](../l10n_cl/overview.md)
- Extends `res.currency.rate` — defined by [`base`](../base/overview.md)
- Extends `res.lang` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.bus`](../../../agents/modules/generated/bus.yaml) — depends_on
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on
- [`module.spreadsheet_account`](../../../agents/modules/generated/spreadsheet_account.yaml) — required_by
- [`module.spreadsheet_dashboard`](../../../agents/modules/generated/spreadsheet_dashboard.yaml) — model_extended_by, required_by
- [`module.test_spreadsheet`](../../../agents/modules/generated/test_spreadsheet.yaml) — model_extended_by, required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`spreadsheet_dashboard`](../spreadsheet_dashboard/overview.md), [`test_spreadsheet`](../test_spreadsheet/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`l10n_cl`](../l10n_cl/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl, qa_upgrade.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
