---
layout: page
title: "France - Time Off (l10n_fr_hr_holidays)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_fr_hr_holidays/
nav_order: 0
---
# France - Time Off — `l10n_fr_hr_holidays`

**Source:** [`agents/modules/generated/l10n_fr_hr_holidays.yaml`](../../agents/modules/generated/l10n_fr_hr_holidays.yaml) · **Wiki:** [`knowledge/modules/l10n_fr_hr_holidays/overview.md`](../../knowledge/modules/l10n_fr_hr_holidays/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_fr_hr_holidays</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">France - Time Off</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_fr_hr_holidays</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_fr_hr_holidays"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Management of leaves for part-time workers in France

## Direct dependencies

[`hr_holidays`](hr_holidays.md), [`l10n_fr`](l10n_fr.md)

## Reverse dependencies (modules that depend on this)

[`l10n_fr_hr_work_entry_holidays`](l10n_fr_hr_work_entry_holidays.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.leave</code></div><div class="role">extended by <code>l10n_fr_hr_holidays</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>l10n_fr_hr_holidays</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>l10n_fr_hr_holidays</code></div></div>
<div class="model"><div class="name"><code>resource.calendar</code></div><div class="role">extended by <code>l10n_fr_hr_holidays</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.hr_holidays` | depends_on, extends_model_from | `agents/modules/generated/hr_holidays.yaml` |
| `module.l10n_fr` | depends_on | `agents/modules/generated/l10n_fr.yaml` |
| `module.l10n_fr_hr_work_entry_holidays` | required_by | `agents/modules/generated/l10n_fr_hr_work_entry_holidays.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |
| `module.resource` | extends_model_from | `agents/modules/generated/resource.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_fr_hr_holidays`](../../../agents/modules/generated/l10n_fr_hr_holidays.yaml)
- Domain: `localization`
- Category: Human Resources/Time Off
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_fr_hr_holidays)
- Direct dependencies: [`hr_holidays`](../hr_holidays/overview.md), [`l10n_fr`](../l10n_fr/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_fr_hr_work_entry_holidays`](../l10n_fr_hr_work_entry_holidays/overview.md)
- Impact graph: [`module:l10n_fr_hr_holidays`](../../impact-graph.json)

## Purpose

Management of leaves for part-time workers in France

## Model relationships

- Extends `hr.leave` — defined by [`hr_holidays`](../hr_holidays/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `resource.calendar` — defined by [`resource`](../resource/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — depends_on, extends_model_from
- [`module.l10n_fr`](../../../agents/modules/generated/l10n_fr.yaml) — depends_on
- [`module.l10n_fr_hr_work_entry_holidays`](../../../agents/modules/generated/l10n_fr_hr_work_entry_holidays.yaml) — required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`resource`](../resource/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
