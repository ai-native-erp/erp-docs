---
layout: page
title: "HR Attendance Holidays (hr_holidays_attendance)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_holidays_attendance/
nav_order: 0
---
# HR Attendance Holidays — `hr_holidays_attendance`

**Source:** [`agents/modules/generated/hr_holidays_attendance.yaml`](../../agents/modules/generated/hr_holidays_attendance.yaml) · **Wiki:** [`knowledge/modules/hr_holidays_attendance/overview.md`](../../knowledge/modules/hr_holidays_attendance/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_holidays_attendance</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">HR Attendance Holidays</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_holidays_attendance</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_holidays_attendance"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Attendance Holidays

## Direct dependencies

[`hr_attendance`](hr_attendance.md), [`hr_holidays`](hr_holidays.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.attendance</code></div><div class="role">extended by <code>hr_holidays_attendance</code></div></div>
<div class="model"><div class="name"><code>hr.leave</code></div><div class="role">extended by <code>hr_holidays_attendance</code></div></div>
<div class="model"><div class="name"><code>hr.leave.accrual.level</code></div><div class="role">extended by <code>hr_holidays_attendance</code></div></div>
<div class="model"><div class="name"><code>hr.leave.allocation</code></div><div class="role">extended by <code>hr_holidays_attendance</code></div></div>
<div class="model"><div class="name"><code>hr.leave.type</code></div><div class="role">extended by <code>hr_holidays_attendance</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>hr_holidays_attendance</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>hr_holidays_attendance</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.hr_attendance` | depends_on, extends_model_from | `agents/modules/generated/hr_attendance.yaml` |
| `module.hr_holidays` | depends_on, extends_model_from | `agents/modules/generated/hr_holidays.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_holidays_attendance`](../../../agents/modules/generated/hr_holidays_attendance.yaml)
- Domain: `human_resources`
- Category: Human Resources
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_holidays_attendance)
- Direct dependencies: [`hr_attendance`](../hr_attendance/overview.md), [`hr_holidays`](../hr_holidays/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:hr_holidays_attendance`](../../impact-graph.json)

## Purpose

Attendance Holidays

## Model relationships

- Extends `hr.attendance` — defined by [`hr_attendance`](../hr_attendance/overview.md)
- Extends `hr.leave` — defined by [`hr_holidays`](../hr_holidays/overview.md)
- Extends `hr.leave.accrual.level` — defined by [`hr_holidays`](../hr_holidays/overview.md)
- Extends `hr.leave.allocation` — defined by [`hr_holidays`](../hr_holidays/overview.md)
- Extends `hr.leave.type` — defined by [`hr_holidays`](../hr_holidays/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.hr_attendance`](../../../agents/modules/generated/hr_attendance.yaml) — depends_on, extends_model_from
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — depends_on, extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
