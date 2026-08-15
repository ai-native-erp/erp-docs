---
layout: page
title: "POS - HR (pos_hr)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_hr/
nav_order: 0
---
# POS - HR — `pos_hr`

**Source:** [`agents/modules/generated/pos_hr.yaml`](../../agents/modules/generated/pos_hr.yaml) · **Wiki:** [`knowledge/modules/pos_hr/overview.md`](../../knowledge/modules/pos_hr/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_hr</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">POS - HR</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_hr</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_hr"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Link module between Point of Sale and HR

## Direct dependencies

[`hr`](hr.md), [`point_of_sale`](point_of_sale.md)

## Reverse dependencies (modules that depend on this)

[`pos_hr_restaurant`](pos_hr_restaurant.md), [`spreadsheet_dashboard_pos_hr`](spreadsheet_dashboard_pos_hr.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>pos_hr</code></div></div>
<div class="model"><div class="name"><code>pos.config</code></div><div class="role">extended by <code>pos_hr</code></div></div>
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">extended by <code>pos_hr</code></div></div>
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>pos_hr</code></div></div>
<div class="model"><div class="name"><code>report.pos.order</code></div><div class="role">extended by <code>pos_hr</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>pos_hr</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.l10n_ch_pos` | extends_model_from | `agents/modules/generated/l10n_ch_pos.yaml` |
| `module.point_of_sale` | depends_on, extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.pos_hr_restaurant` | required_by | `agents/modules/generated/pos_hr_restaurant.yaml` |
| `module.spreadsheet_dashboard_pos_hr` | required_by | `agents/modules/generated/spreadsheet_dashboard_pos_hr.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_hr`](../../../agents/modules/generated/pos_hr.yaml)
- Domain: `point_of_sale`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_hr)
- Direct dependencies: [`hr`](../hr/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`pos_hr_restaurant`](../pos_hr_restaurant/overview.md), [`spreadsheet_dashboard_pos_hr`](../spreadsheet_dashboard_pos_hr/overview.md)
- Impact graph: [`module:pos_hr`](../../impact-graph.json)

## Purpose

Link module between Point of Sale and HR

## Model relationships

- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `pos.config` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.order` — defined by [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `report.pos.order` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on, extends_model_from
- [`module.pos_hr_restaurant`](../../../agents/modules/generated/pos_hr_restaurant.yaml) — required_by
- [`module.spreadsheet_dashboard_pos_hr`](../../../agents/modules/generated/spreadsheet_dashboard_pos_hr.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`hr`](../hr/overview.md), [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
