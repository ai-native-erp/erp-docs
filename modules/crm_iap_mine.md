---
layout: page
title: "Lead Generation (crm_iap_mine)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/crm_iap_mine/
nav_order: 0
---
# Lead Generation — `crm_iap_mine`

**Source:** [`agents/modules/generated/crm_iap_mine.yaml`](../../agents/modules/generated/crm_iap_mine.yaml) · **Wiki:** [`knowledge/modules/crm_iap_mine/overview.md`](../../knowledge/modules/crm_iap_mine/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>crm_iap_mine</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Lead Generation</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/crm_iap_mine</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/crm_iap_mine"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Generate Leads/Opportunities based on country, industries, size, etc.

## Direct dependencies

[`iap_crm`](iap_crm.md), [`iap_mail`](iap_mail.md)

## Reverse dependencies (modules that depend on this)

[`test_crm_full`](test_crm_full.md), [`website_crm_iap_reveal`](website_crm_iap_reveal.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.iap.lead.helpers</code></div><div class="role">defined by <code>crm_iap_mine</code></div></div>
<div class="model"><div class="name"><code>crm.iap.lead.industry</code></div><div class="role">defined by <code>crm_iap_mine</code></div></div>
<div class="model"><div class="name"><code>crm.iap.lead.mining.request</code></div><div class="role">defined by <code>crm_iap_mine</code></div></div>
<div class="model"><div class="name"><code>crm.iap.lead.role</code></div><div class="role">defined by <code>crm_iap_mine</code></div></div>
<div class="model"><div class="name"><code>crm.iap.lead.seniority</code></div><div class="role">defined by <code>crm_iap_mine</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.lead</code></div><div class="role">extended by <code>crm_iap_mine</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.iap_crm` | depends_on | `agents/modules/generated/iap_crm.yaml` |
| `module.iap_mail` | depends_on | `agents/modules/generated/iap_mail.yaml` |
| `module.test_crm_full` | required_by | `agents/modules/generated/test_crm_full.yaml` |
| `module.website_crm_iap_reveal` | required_by | `agents/modules/generated/website_crm_iap_reveal.yaml` |

## Full wiki excerpt

- SME owner: [`module.crm_iap_mine`](../../../agents/modules/generated/crm_iap_mine.yaml)
- Domain: `sales_crm`
- Category: Sales/CRM
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/crm_iap_mine)
- Direct dependencies: [`iap_crm`](../iap_crm/overview.md), [`iap_mail`](../iap_mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_crm_full`](../test_crm_full/overview.md), [`website_crm_iap_reveal`](../website_crm_iap_reveal/overview.md)
- Impact graph: [`module:crm_iap_mine`](../../impact-graph.json)

## Purpose

Generate Leads/Opportunities based on country, industries, size, etc.

## Model relationships

- `crm.iap.lead.helpers`
- `crm.iap.lead.industry`
- `crm.iap.lead.mining.request`
- `crm.iap.lead.role`
- `crm.iap.lead.seniority`
- Extends `crm.lead` — defined by [`crm`](../crm/overview.md)

## Related SME agents

- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.iap_crm`](../../../agents/modules/generated/iap_crm.yaml) — depends_on
- [`module.iap_mail`](../../../agents/modules/generated/iap_mail.yaml) — depends_on
- [`module.test_crm_full`](../../../agents/modules/generated/test_crm_full.yaml) — required_by
- [`module.website_crm_iap_reveal`](../../../agents/modules/generated/website_crm_iap_reveal.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`crm`](../crm/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
