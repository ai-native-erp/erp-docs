---
layout: page
title: "Lead Enrichment (crm_iap_enrich)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/crm_iap_enrich/
nav_order: 0
---
# Lead Enrichment — `crm_iap_enrich`

**Source:** [`agents/modules/generated/crm_iap_enrich.yaml`](../../agents/modules/generated/crm_iap_enrich.yaml) · **Wiki:** [`knowledge/modules/crm_iap_enrich/overview.md`](../../knowledge/modules/crm_iap_enrich/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>crm_iap_enrich</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Lead Enrichment</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/crm_iap_enrich</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/crm_iap_enrich"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Enrich Leads/Opportunities using email address domain

## Direct dependencies

[`iap_crm`](iap_crm.md), [`iap_mail`](iap_mail.md)

## Reverse dependencies (modules that depend on this)

[`test_crm_full`](test_crm_full.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.lead</code></div><div class="role">extended by <code>crm_iap_enrich</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>crm_iap_enrich</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.iap_crm` | depends_on | `agents/modules/generated/iap_crm.yaml` |
| `module.iap_mail` | depends_on | `agents/modules/generated/iap_mail.yaml` |
| `module.test_crm_full` | required_by | `agents/modules/generated/test_crm_full.yaml` |

## Full wiki excerpt

- SME owner: [`module.crm_iap_enrich`](../../../agents/modules/generated/crm_iap_enrich.yaml)
- Domain: `sales_crm`
- Category: Sales/CRM
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/crm_iap_enrich)
- Direct dependencies: [`iap_crm`](../iap_crm/overview.md), [`iap_mail`](../iap_mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_crm_full`](../test_crm_full/overview.md)
- Impact graph: [`module:crm_iap_enrich`](../../impact-graph.json)

## Purpose

Enrich Leads/Opportunities using email address domain

## Model relationships

- Extends `crm.lead` — defined by [`crm`](../crm/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.iap_crm`](../../../agents/modules/generated/iap_crm.yaml) — depends_on
- [`module.iap_mail`](../../../agents/modules/generated/iap_mail.yaml) — depends_on
- [`module.test_crm_full`](../../../agents/modules/generated/test_crm_full.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`crm`](../crm/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
