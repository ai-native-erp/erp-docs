---
layout: page
title: "Time Off in Payslips (hr_work_entry_holidays)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_work_entry_holidays/
nav_order: 0
---
# Time Off in Payslips — `hr_work_entry_holidays`

**Source:** [`agents/modules/generated/hr_work_entry_holidays.yaml`](../../agents/modules/generated/hr_work_entry_holidays.yaml) · **Wiki:** [`knowledge/modules/hr_work_entry_holidays/overview.md`](../../knowledge/modules/hr_work_entry_holidays/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_work_entry_holidays</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Time Off in Payslips</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_work_entry_holidays</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_work_entry_holidays"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage Time Off in Payslips

## Direct dependencies

[`hr_holidays`](hr_holidays.md), [`hr_work_entry_contract`](hr_work_entry_contract.md)

## Reverse dependencies (modules that depend on this)

[`l10n_fr_hr_work_entry_holidays`](l10n_fr_hr_work_entry_holidays.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.contract</code></div><div class="role">extended by <code>hr_work_entry_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.employee.base</code></div><div class="role">extended by <code>hr_work_entry_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave</code></div><div class="role">extended by <code>hr_work_entry_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.leave.type</code></div><div class="role">extended by <code>hr_work_entry_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.work.entry</code></div><div class="role">extended by <code>hr_work_entry_holidays</code></div></div>
<div class="model"><div class="name"><code>hr.work.entry.type</code></div><div class="role">extended by <code>hr_work_entry_holidays</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr` | extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.hr_contract` | extends_model_from | `agents/modules/generated/hr_contract.yaml` |
| `module.hr_holidays` | depends_on, extends_model_from | `agents/modules/generated/hr_holidays.yaml` |
| `module.hr_work_entry` | extends_model_from | `agents/modules/generated/hr_work_entry.yaml` |
| `module.hr_work_entry_contract` | depends_on | `agents/modules/generated/hr_work_entry_contract.yaml` |
| `module.l10n_fr_hr_work_entry_holidays` | required_by | `agents/modules/generated/l10n_fr_hr_work_entry_holidays.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_work_entry_holidays`](../../../agents/modules/generated/hr_work_entry_holidays.yaml)
- Domain: `human_resources`
- Category: Human Resources/Payroll
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_work_entry_holidays)
- Direct dependencies: [`hr_holidays`](../hr_holidays/overview.md), [`hr_work_entry_contract`](../hr_work_entry_contract/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_fr_hr_work_entry_holidays`](../l10n_fr_hr_work_entry_holidays/overview.md)
- Impact graph: [`module:hr_work_entry_holidays`](../../impact-graph.json)

## Purpose

Manage Time Off in Payslips

## Model relationships

- Extends `hr.contract` — defined by [`hr_contract`](../hr_contract/overview.md)
- Extends `hr.employee.base` — defined by [`hr`](../hr/overview.md)
- Extends `hr.leave` — defined by [`hr_holidays`](../hr_holidays/overview.md)
- Extends `hr.leave.type` — defined by [`hr_holidays`](../hr_holidays/overview.md)
- Extends `hr.work.entry` — defined by [`hr_work_entry`](../hr_work_entry/overview.md)
- Extends `hr.work.entry.type` — defined by [`hr_work_entry`](../hr_work_entry/overview.md)

## Related SME agents

- [`module.hr`](../../../agents/modules/generated/hr.yaml) — extends_model_from
- [`module.hr_contract`](../../../agents/modules/generated/hr_contract.yaml) — extends_model_from
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — depends_on, extends_model_from
- [`module.hr_work_entry`](../../../agents/modules/generated/hr_work_entry.yaml) — extends_model_from
- [`module.hr_work_entry_contract`](../../../agents/modules/generated/hr_work_entry_contract.yaml) — depends_on
- [`module.l10n_fr_hr_work_entry_holidays`](../../../agents/modules/generated/l10n_fr_hr_work_entry_holidays.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`hr`](../hr/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_work_entry`](../hr_work_entry/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
