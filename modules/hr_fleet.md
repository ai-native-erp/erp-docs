---
layout: page
title: "Fleet History (hr_fleet)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_fleet/
nav_order: 0
---
# Fleet History — `hr_fleet`

**Source:** [`agents/modules/generated/hr_fleet.yaml`](../../agents/modules/generated/hr_fleet.yaml) · **Wiki:** [`knowledge/modules/hr_fleet/overview.md`](../../knowledge/modules/hr_fleet/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_fleet</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Fleet History</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_fleet</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_fleet"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Get history of driven cars by employees

## Direct dependencies

[`fleet`](fleet.md), [`hr`](hr.md)

## Reverse dependencies (modules that depend on this)

[`test_discuss_full`](test_discuss_full.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>fleet.vehicle</code></div><div class="role">extended by <code>hr_fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.assignation.log</code></div><div class="role">extended by <code>hr_fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.log.contract</code></div><div class="role">extended by <code>hr_fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.log.services</code></div><div class="role">extended by <code>hr_fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.odometer</code></div><div class="role">extended by <code>hr_fleet</code></div></div>
<div class="model"><div class="name"><code>hr.departure.wizard</code></div><div class="role">extended by <code>hr_fleet</code></div></div>
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr_fleet</code></div></div>
<div class="model"><div class="name"><code>hr.employee.public</code></div><div class="role">extended by <code>hr_fleet</code></div></div>
<div class="model"><div class="name"><code>mail.activity.plan.template</code></div><div class="role">extended by <code>hr_fleet</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>hr_fleet</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.fleet` | depends_on, extends_model_from | `agents/modules/generated/fleet.yaml` |
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.test_discuss_full` | required_by | `agents/modules/generated/test_discuss_full.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_fleet`](../../../agents/modules/generated/hr_fleet.yaml)
- Domain: `human_resources`
- Category: Human Resources
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_fleet)
- Direct dependencies: [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_discuss_full`](../test_discuss_full/overview.md)
- Impact graph: [`module:hr_fleet`](../../impact-graph.json)

## Purpose

Get history of driven cars by employees

## Model relationships

- Extends `fleet.vehicle` — defined by [`fleet`](../fleet/overview.md)
- Extends `fleet.vehicle.assignation.log` — defined by [`fleet`](../fleet/overview.md)
- Extends `fleet.vehicle.log.contract` — defined by [`fleet`](../fleet/overview.md)
- Extends `fleet.vehicle.log.services` — defined by [`fleet`](../fleet/overview.md)
- Extends `fleet.vehicle.odometer` — defined by [`fleet`](../fleet/overview.md)
- Extends `hr.departure.wizard` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `hr.employee.public` — defined by [`hr`](../hr/overview.md)
- Extends `mail.activity.plan.template` — defined by [`mail`](../mail/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.fleet`](../../../agents/modules/generated/fleet.yaml) — depends_on, extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.test_discuss_full`](../../../agents/modules/generated/test_discuss_full.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
