---
layout: page
title: "Employees - Mexico (l10n_mx_hr)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_mx_hr/
nav_order: 0
---
# Employees - Mexico — `l10n_mx_hr`

**Source:** [`agents/modules/generated/l10n_mx_hr.yaml`](../../agents/modules/generated/l10n_mx_hr.yaml) · **Wiki:** [`knowledge/modules/l10n_mx_hr/overview.md`](../../knowledge/modules/l10n_mx_hr/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_mx_hr</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Employees - Mexico</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_mx_hr</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_mx_hr"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Adds specific fields to Employees for Mexican companies.

## Direct dependencies

[`hr`](hr.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>l10n_mx_hr</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_mx_hr`](../../../agents/modules/generated/l10n_mx_hr.yaml)
- Domain: `localization`
- Category: Human Resources/Employees
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_mx_hr)
- Direct dependencies: [`hr`](../hr/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_mx_hr`](../../impact-graph.json)

## Purpose

Adds specific fields to Employees for Mexican companies.

## Model relationships

- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)

## Related SME agents

- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`hr`](../hr/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
