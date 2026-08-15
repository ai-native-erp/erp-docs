---
layout: page
title: "Mass mailing sms on lead / opportunities (mass_mailing_crm_sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mass_mailing_crm_sms/
nav_order: 0
---
# Mass mailing sms on lead / opportunities — `mass_mailing_crm_sms`

**Source:** [`agents/modules/generated/mass_mailing_crm_sms.yaml`](../../agents/modules/generated/mass_mailing_crm_sms.yaml) · **Wiki:** [`knowledge/modules/mass_mailing_crm_sms/overview.md`](../../knowledge/modules/mass_mailing_crm_sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mass_mailing_crm_sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Mass mailing sms on lead / opportunities</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mass_mailing_crm_sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mass_mailing_crm_sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Add lead / opportunities info on mass mailing sms

## Direct dependencies

[`mass_mailing_crm`](mass_mailing_crm.md), [`mass_mailing_sms`](mass_mailing_sms.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>utm.campaign</code></div><div class="role">extended by <code>mass_mailing_crm_sms</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mass_mailing_crm` | depends_on | `agents/modules/generated/mass_mailing_crm.yaml` |
| `module.mass_mailing_sms` | depends_on | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.utm` | extends_model_from | `agents/modules/generated/utm.yaml` |

## Full wiki excerpt

- SME owner: [`module.mass_mailing_crm_sms`](../../../agents/modules/generated/mass_mailing_crm_sms.yaml)
- Domain: `marketing_events`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mass_mailing_crm_sms)
- Direct dependencies: [`mass_mailing_crm`](../mass_mailing_crm/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:mass_mailing_crm_sms`](../../impact-graph.json)

## Purpose

Add lead / opportunities info on mass mailing sms

## Model relationships

- Extends `utm.campaign` — defined by [`utm`](../utm/overview.md)

## Related SME agents

- [`module.mass_mailing_crm`](../../../agents/modules/generated/mass_mailing_crm.yaml) — depends_on
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — depends_on
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`utm`](../utm/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
