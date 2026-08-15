---
layout: page
title: "Maintenance - HR (hr_maintenance)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/hr_maintenance/
nav_order: 0
---
# Maintenance - HR — `hr_maintenance`

**Source:** [`agents/modules/generated/hr_maintenance.yaml`](../../agents/modules/generated/hr_maintenance.yaml) · **Wiki:** [`knowledge/modules/hr_maintenance/overview.md`](../../knowledge/modules/hr_maintenance/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>hr_maintenance</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Maintenance - HR</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/hr_maintenance</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_maintenance"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Equipment, Assets, Internal Hardware, Allocation Tracking

## Direct dependencies

[`hr`](hr.md), [`maintenance`](maintenance.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>hr.employee</code></div><div class="role">extended by <code>hr_maintenance</code></div></div>
<div class="model"><div class="name"><code>maintenance.equipment</code></div><div class="role">extended by <code>hr_maintenance</code></div></div>
<div class="model"><div class="name"><code>maintenance.request</code></div><div class="role">extended by <code>hr_maintenance</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>hr_maintenance</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.hr` | depends_on, extends_model_from | `agents/modules/generated/hr.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.maintenance` | depends_on, extends_model_from | `agents/modules/generated/maintenance.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.hr_maintenance`](../../../agents/modules/generated/hr_maintenance.yaml)
- Domain: `human_resources`
- Category: Human Resources
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/hr_maintenance)
- Direct dependencies: [`hr`](../hr/overview.md), [`maintenance`](../maintenance/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:hr_maintenance`](../../impact-graph.json)

## Purpose

Equipment, Assets, Internal Hardware, Allocation Tracking

## Model relationships

- Extends `hr.employee` — defined by [`hr`](../hr/overview.md)
- Extends `maintenance.equipment` — defined by [`maintenance`](../maintenance/overview.md)
- Extends `maintenance.request` — defined by [`maintenance`](../maintenance/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on, extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.maintenance`](../../../agents/modules/generated/maintenance.yaml) — depends_on, extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`hr`](../hr/overview.md), [`mail`](../mail/overview.md), [`maintenance`](../maintenance/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
