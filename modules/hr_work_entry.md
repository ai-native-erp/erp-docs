---
layout: page
title: "Work Entries (hr_work_entry)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_work_entry/
nav_order: 0
---
# Work Entries — `hr_work_entry`

**Source:** [`agents/modules/generated/hr_work_entry.yaml`](../../agents/modules/generated/hr_work_entry.yaml) · **Wiki:** [`knowledge/modules/hr_work_entry/overview.md`](../../knowledge/modules/hr_work_entry/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_work_entry</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Work Entries</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_work_entry</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_work_entry"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage work entries

## Direct dependencies

[`hr`](hr.md)

## Reverse dependencies (modules that depend on this)

[`hr_work_entry_contract`](hr_work_entry_contract.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.user.work.entry.employee</code></div><div class="role">defined by <code>hr_work_entry</code></div></div>
<div class="model"><div class="name"><code>hr.work.entry</code></div><div class="role">defined by <code>hr_work_entry</code></div></div>
<div class="model"><div class="name"><code>hr.work.entry.type</code></div><div class="role">defined by <code>hr_work_entry</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr_work_entry</code></div></div>
<div class="model"><div class="name"><code>resource.calendar.attendance</code></div><div class="role">extended by <code>hr_work_entry</code></div></div>
<div class="model"><div class="name"><code>resource.calendar.leaves</code></div><div class="role">extended by <code>hr_work_entry</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.hr_work_entry_contract` | model_extended_by, required_by | `agents/modules/generated/hr_work_entry_contract.yaml` |
| `module.hr_work_entry_holidays` | model_extended_by | `agents/modules/generated/hr_work_entry_holidays.yaml` |
| `module.l10n_fr_hr_work_entry_holidays` | model_extended_by | `agents/modules/generated/l10n_fr_hr_work_entry_holidays.yaml` |
| `module.resource` | extends_model_from | `agents/modules/generated/resource.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_work_entry`](../../../agents/modules/generated/hr_work_entry.yaml)
- Domain: `human_resources`
- Category: Human Resources/Employees
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_work_entry)
- Direct dependencies: [`hr`](../hr/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_work_entry_contract`](../hr_work_entry_contract/overview.md)
- Impact graph: [`module:hr_work_entry`](../../impact-graph.json)

## Purpose

Manage work entries

## Model relationships

- `hr.user.work.entry.employee`
- `hr.work.entry` — extended by [`hr_work_entry_contract`](../hr_work_entry_contract/overview.md), [`hr_work_entry_holidays`](../hr_work_entry_holidays/overview.md), [`l10n_fr_hr_work_entry_holidays`](../l10n_fr_hr_work_entry_holidays/overview.md)
- `hr.work.entry.type` — extended by [`hr_work_entry_contract`](../hr_work_entry_contract/overview.md), [`hr_work_entry_holidays`](../hr_work_entry_holidays/overview.md)
- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `resource.calendar.attendance` — defined by [`resource`](../resource/overview.md)
- Extends `resource.calendar.leaves` — defined by [`resource`](../resource/overview.md)

## Related SME agents

- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.hr_work_entry_contract`](../../../agents/modules/generated/hr_work_entry_contract.yaml) — model_extended_by, required_by
- [`module.hr_work_entry_holidays`](../../../agents/modules/generated/hr_work_entry_holidays.yaml) — model_extended_by
- [`module.l10n_fr_hr_work_entry_holidays`](../../../agents/modules/generated/l10n_fr_hr_work_entry_holidays.yaml) — model_extended_by
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr_work_entry_contract`](../hr_work_entry_contract/overview.md), [`hr_work_entry_holidays`](../hr_work_entry_holidays/overview.md), [`l10n_fr_hr_work_entry_holidays`](../l10n_fr_hr_work_entry_holidays/overview.md).
- Review model owners used by this module: [`hr`](../hr/overview.md), [`resource`](../resource/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
