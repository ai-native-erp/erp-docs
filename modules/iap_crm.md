---
layout: page
title: "IAP / CRM (iap_crm)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/iap_crm/
nav_order: 0
---
# IAP / CRM — `iap_crm`

**Source:** [`agents/modules/generated/iap_crm.yaml`](../../agents/modules/generated/iap_crm.yaml) · **Wiki:** [`knowledge/modules/iap_crm/overview.md`](../../knowledge/modules/iap_crm/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>iap_crm</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">IAP / CRM</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">integrations</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/iap_crm</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/iap_crm"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Bridge between IAP and CRM

## Direct dependencies

[`crm`](crm.md), [`iap_mail`](iap_mail.md)

## Reverse dependencies (modules that depend on this)

[`crm_iap_enrich`](crm_iap_enrich.md), [`crm_iap_mine`](crm_iap_mine.md), [`website_crm_iap_reveal`](website_crm_iap_reveal.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.lead</code></div><div class="role">extended by <code>iap_crm</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.crm` | depends_on, extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.crm_iap_enrich` | required_by | `agents/modules/generated/crm_iap_enrich.yaml` |
| `module.crm_iap_mine` | required_by | `agents/modules/generated/crm_iap_mine.yaml` |
| `module.iap_mail` | depends_on | `agents/modules/generated/iap_mail.yaml` |
| `module.website_crm_iap_reveal` | required_by | `agents/modules/generated/website_crm_iap_reveal.yaml` |

## Full wiki excerpt

- SME owner: [`module.iap_crm`](../../../agents/modules/generated/iap_crm.yaml)
- Domain: `integrations`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/iap_crm)
- Direct dependencies: [`crm`](../crm/overview.md), [`iap_mail`](../iap_mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`crm_iap_enrich`](../crm_iap_enrich/overview.md), [`crm_iap_mine`](../crm_iap_mine/overview.md), [`website_crm_iap_reveal`](../website_crm_iap_reveal/overview.md)
- Impact graph: [`module:iap_crm`](../../impact-graph.json)

## Purpose

Bridge between IAP and CRM

## Model relationships

- Extends `crm.lead` — defined by [`crm`](../crm/overview.md)

## Related SME agents

- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on, extends_model_from
- [`module.crm_iap_enrich`](../../../agents/modules/generated/crm_iap_enrich.yaml) — required_by
- [`module.crm_iap_mine`](../../../agents/modules/generated/crm_iap_mine.yaml) — required_by
- [`module.iap_mail`](../../../agents/modules/generated/iap_mail.yaml) — depends_on
- [`module.website_crm_iap_reveal`](../../../agents/modules/generated/website_crm_iap_reveal.yaml) — required_by

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`crm`](../crm/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
