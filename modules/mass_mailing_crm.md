---
layout: page
title: "Mass mailing on lead / opportunities (mass_mailing_crm)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mass_mailing_crm/
nav_order: 0
---
# Mass mailing on lead / opportunities — `mass_mailing_crm`

**Source:** [`agents/modules/generated/mass_mailing_crm.yaml`](../../agents/modules/generated/mass_mailing_crm.yaml) · **Wiki:** [`knowledge/modules/mass_mailing_crm/overview.md`](../../knowledge/modules/mass_mailing_crm/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mass_mailing_crm</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Mass mailing on lead / opportunities</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mass_mailing_crm</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mass_mailing_crm"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Add lead / opportunities UTM info on mass mailing

## Direct dependencies

[`crm`](crm.md), [`mass_mailing`](mass_mailing.md)

## Reverse dependencies (modules that depend on this)

[`mass_mailing_crm_sms`](mass_mailing_crm_sms.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>mailing.mailing</code></div><div class="role">defined by <code>mass_mailing_crm</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.lead</code></div><div class="role">extended by <code>mass_mailing_crm</code></div></div>
<div class="model"><div class="name"><code>mailing.mailing</code></div><div class="role">extended by <code>mass_mailing_crm</code></div></div>
<div class="model"><div class="name"><code>utm.campaign</code></div><div class="role">extended by <code>mass_mailing_crm</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.crm` | depends_on, extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.mass_mailing` | depends_on, extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_crm_sms` | required_by | `agents/modules/generated/mass_mailing_crm_sms.yaml` |
| `module.mass_mailing_sale` | extends_model_from, model_extended_by | `agents/modules/generated/mass_mailing_sale.yaml` |
| `module.mass_mailing_sms` | model_extended_by | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.utm` | extends_model_from | `agents/modules/generated/utm.yaml` |

## Full wiki excerpt

- SME owner: [`module.mass_mailing_crm`](../../../agents/modules/generated/mass_mailing_crm.yaml)
- Domain: `marketing_events`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mass_mailing_crm)
- Direct dependencies: [`crm`](../crm/overview.md), [`mass_mailing`](../mass_mailing/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`mass_mailing_crm_sms`](../mass_mailing_crm_sms/overview.md)
- Impact graph: [`module:mass_mailing_crm`](../../impact-graph.json)

## Purpose

Add lead / opportunities UTM info on mass mailing

## Model relationships

- `mailing.mailing` — extended by [`mass_mailing_sale`](../mass_mailing_sale/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `crm.lead` — defined by [`crm`](../crm/overview.md)
- Extends `mailing.mailing` — defined by [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sale`](../mass_mailing_sale/overview.md)
- Extends `utm.campaign` — defined by [`utm`](../utm/overview.md)

## Related SME agents

- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on, extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — depends_on, extends_model_from
- [`module.mass_mailing_crm_sms`](../../../agents/modules/generated/mass_mailing_crm_sms.yaml) — required_by
- [`module.mass_mailing_sale`](../../../agents/modules/generated/mass_mailing_sale.yaml) — extends_model_from, model_extended_by
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — model_extended_by
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`mass_mailing_sale`](../mass_mailing_sale/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Review model owners used by this module: [`crm`](../crm/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sale`](../mass_mailing_sale/overview.md), [`utm`](../utm/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
