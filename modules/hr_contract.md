---
layout: page
title: "Employee Contracts (hr_contract)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_contract/
nav_order: 0
---
# Employee Contracts — `hr_contract`

**Source:** [`agents/modules/generated/hr_contract.yaml`](../../agents/modules/generated/hr_contract.yaml) · **Wiki:** [`knowledge/modules/hr_contract/overview.md`](../../knowledge/modules/hr_contract/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_contract</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Employee Contracts</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_contract</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_contract"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`hr`](hr.md)

## Reverse dependencies (modules that depend on this)

[`hr_work_entry_contract`](hr_work_entry_contract.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.contract</code></div><div class="role">defined by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>hr.contract.history</code></div><div class="role">defined by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>hr.payroll.structure.type</code></div><div class="role">defined by <code>hr_contract</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.departure.wizard</code></div><div class="role">extended by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>hr.employee.base</code></div><div class="role">extended by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>hr.employee.public</code></div><div class="role">extended by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>mail.activity.schedule</code></div><div class="role">extended by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>resource.calendar</code></div><div class="role">extended by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>resource.calendar.leaves</code></div><div class="role">extended by <code>hr_contract</code></div></div>
<div class="model"><div class="name"><code>resource.resource</code></div><div class="role">extended by <code>hr_contract</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.hr_work_entry_contract` | model_extended_by, required_by | `agents/modules/generated/hr_work_entry_contract.yaml` |
| `module.hr_work_entry_holidays` | model_extended_by | `agents/modules/generated/hr_work_entry_holidays.yaml` |
| `module.l10n_fr_hr_work_entry_holidays` | model_extended_by | `agents/modules/generated/l10n_fr_hr_work_entry_holidays.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_contract`](../../../agents/modules/generated/hr_contract.yaml)
- Domain: `human_resources`
- Category: Human Resources/Contracts
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_contract)
- Direct dependencies: [`hr`](../hr/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_work_entry_contract`](../hr_work_entry_contract/overview.md)
- Impact graph: [`module:hr_contract`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `hr.contract` — extended by [`hr_work_entry_contract`](../hr_work_entry_contract/overview.md), [`hr_work_entry_holidays`](../hr_work_entry_holidays/overview.md), [`l10n_fr_hr_work_entry_holidays`](../l10n_fr_hr_work_entry_holidays/overview.md)
- `hr.contract.history`
- `hr.payroll.structure.type`
- Extends `hr.departure.wizard` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee.base` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee.public` — defined by [`hr`](../hr/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.activity.schedule` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `resource.calendar` — defined by [`resource`](../resource/overview.md)
- Extends `resource.calendar.leaves` — defined by [`resource`](../resource/overview.md)
- Extends `resource.resource` — defined by [`resource`](../resource/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.hr_work_entry_contract`](../../../agents/modules/generated/hr_work_entry_contract.yaml) — model_extended_by, required_by
- [`module.hr_work_entry_holidays`](../../../agents/modules/generated/hr_work_entry_holidays.yaml) — model_extended_by
- [`module.l10n_fr_hr_work_entry_holidays`](../../../agents/modules/generated/l10n_fr_hr_work_entry_holidays.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr_work_entry_contract`](../hr_work_entry_contract/overview.md), [`hr_work_entry_holidays`](../hr_work_entry_holidays/overview.md), [`l10n_fr_hr_work_entry_holidays`](../l10n_fr_hr_work_entry_holidays/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`hr`](../hr/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`resource`](../resource/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
