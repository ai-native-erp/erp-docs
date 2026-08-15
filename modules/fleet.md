---
layout: page
title: "Fleet (fleet)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/fleet/
nav_order: 0
---
# Fleet — `fleet`

**Source:** [`agents/modules/generated/fleet.yaml`](../../agents/modules/generated/fleet.yaml) · **Wiki:** [`knowledge/modules/fleet/overview.md`](../../knowledge/modules/fleet/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>fleet</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Fleet</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">human_resources</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/fleet</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/fleet"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage your fleet and track car costs

## Direct dependencies

[`base`](base.md), [`mail`](mail.md)

## Reverse dependencies (modules that depend on this)

[`account_fleet`](account_fleet.md), [`hr_fleet`](hr_fleet.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>fleet.service.type</code></div><div class="role">defined by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle</code></div><div class="role">defined by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.assignation.log</code></div><div class="role">defined by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.cost.report</code></div><div class="role">defined by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.log.contract</code></div><div class="role">defined by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.log.services</code></div><div class="role">defined by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.model</code></div><div class="role">defined by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.model.brand</code></div><div class="role">defined by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.model.category</code></div><div class="role">defined by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.odometer</code></div><div class="role">defined by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.state</code></div><div class="role">defined by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle.tag</code></div><div class="role">defined by <code>fleet</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>avatar.mixin</code></div><div class="role">extended by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>mail.activity.type</code></div><div class="role">extended by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>fleet</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>fleet</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_fleet` | model_extended_by, required_by | `agents/modules/generated/account_fleet.yaml` |
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.hr_fleet` | model_extended_by, required_by | `agents/modules/generated/hr_fleet.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera.yaml` |
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |

## Full wiki excerpt

- SME owner: [`module.fleet`](../../../agents/modules/generated/fleet.yaml)
- Domain: `human_resources`
- Category: Human Resources/Fleet
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/fleet)
- Direct dependencies: [`base`](../base/overview.md), [`mail`](../mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`account_fleet`](../account_fleet/overview.md), [`hr_fleet`](../hr_fleet/overview.md)
- Impact graph: [`module:fleet`](../../impact-graph.json)

## Purpose

Manage your fleet and track car costs

## Model relationships

- `fleet.service.type`
- `fleet.vehicle` — extended by [`account_fleet`](../account_fleet/overview.md), [`hr_fleet`](../hr_fleet/overview.md)
- `fleet.vehicle.assignation.log` — extended by [`hr_fleet`](../hr_fleet/overview.md)
- `fleet.vehicle.cost.report`
- `fleet.vehicle.log.contract` — extended by [`hr_fleet`](../hr_fleet/overview.md)
- `fleet.vehicle.log.services` — extended by [`hr_fleet`](../hr_fleet/overview.md)
- `fleet.vehicle.model`
- `fleet.vehicle.model.brand`
- `fleet.vehicle.model.category`
- `fleet.vehicle.odometer` — extended by [`hr_fleet`](../hr_fleet/overview.md)
- `fleet.vehicle.state`
- `fleet.vehicle.tag`
- Extends `avatar.mixin` — defined by [`base`](../base/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.activity.type` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_fleet`](../../../agents/modules/generated/account_fleet.yaml) — model_extended_by, required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.hr_fleet`](../../../agents/modules/generated/hr_fleet.yaml) — model_extended_by, required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account_fleet`](../account_fleet/overview.md), [`hr_fleet`](../hr_fleet/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
