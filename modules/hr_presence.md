---
layout: page
title: "Employee Presence Control (hr_presence)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_presence/
nav_order: 0
---
# Employee Presence Control — `hr_presence`

**Source:** [`agents/modules/generated/hr_presence.yaml`](../../agents/modules/generated/hr_presence.yaml) · **Wiki:** [`knowledge/modules/hr_presence/overview.md`](../../knowledge/modules/hr_presence/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_presence</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Employee Presence Control</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_presence</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_presence"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`hr`](hr.md), [`hr_holidays`](hr_holidays.md), [`sms`](sms.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.employee.base</code></div><div class="role">extended by <code>hr_presence</code></div></div>
<div class="model"><div class="name"><code>ir.websocket</code></div><div class="role">extended by <code>hr_presence</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>hr_presence</code></div></div>
<div class="model"><div class="name"><code>res.users.log</code></div><div class="role">extended by <code>hr_presence</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.bus` | extends_model_from | `agents/modules/generated/bus.yaml` |
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.hr_holidays` | depends_on | `agents/modules/generated/hr_holidays.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |
| `module.sms` | depends_on | `agents/modules/generated/sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_presence`](../../../agents/modules/generated/hr_presence.yaml)
- Domain: `human_resources`
- Category: Human Resources
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_presence)
- Direct dependencies: [`hr`](../hr/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`sms`](../sms/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:hr_presence`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `hr.employee.base` — defined by [`hr`](../hr/overview.md)
- Extends `ir.websocket` — defined by [`bus`](../bus/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.users.log` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.bus`](../../../agents/modules/generated/bus.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — depends_on
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`bus`](../bus/overview.md), [`hr`](../hr/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
