---
layout: page
title: "Test Full Crm Flow (test_crm_full)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_crm_full/
nav_order: 0
---
# Test Full Crm Flow — `test_crm_full`

**Source:** [`agents/modules/generated/test_crm_full.yaml`](../../agents/modules/generated/test_crm_full.yaml) · **Wiki:** [`knowledge/modules/test_crm_full/overview.md`](../../knowledge/modules/test_crm_full/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_crm_full</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Test Full Crm Flow</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_crm_full</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_crm_full"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`crm`](crm.md), [`crm_iap_enrich`](crm_iap_enrich.md), [`crm_iap_mine`](crm_iap_mine.md), [`crm_sms`](crm_sms.md), [`event_crm`](event_crm.md), [`sale_crm`](sale_crm.md), [`website_crm`](website_crm.md), [`website_crm_iap_reveal`](website_crm_iap_reveal.md), [`website_crm_livechat`](website_crm_livechat.md), [`website_crm_partner_assign`](website_crm_partner_assign.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.crm` | depends_on | `agents/modules/generated/crm.yaml` |
| `module.crm_iap_enrich` | depends_on | `agents/modules/generated/crm_iap_enrich.yaml` |
| `module.crm_iap_mine` | depends_on | `agents/modules/generated/crm_iap_mine.yaml` |
| `module.crm_sms` | depends_on | `agents/modules/generated/crm_sms.yaml` |
| `module.event_crm` | depends_on | `agents/modules/generated/event_crm.yaml` |
| `module.sale_crm` | depends_on | `agents/modules/generated/sale_crm.yaml` |
| `module.website_crm` | depends_on | `agents/modules/generated/website_crm.yaml` |
| `module.website_crm_iap_reveal` | depends_on | `agents/modules/generated/website_crm_iap_reveal.yaml` |
| `module.website_crm_livechat` | depends_on | `agents/modules/generated/website_crm_livechat.yaml` |
| `module.website_crm_partner_assign` | depends_on | `agents/modules/generated/website_crm_partner_assign.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_crm_full`](../../../agents/modules/generated/test_crm_full.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_crm_full)
- Direct dependencies: [`crm`](../crm/overview.md), [`crm_iap_enrich`](../crm_iap_enrich/overview.md), [`crm_iap_mine`](../crm_iap_mine/overview.md), [`crm_sms`](../crm_sms/overview.md), [`event_crm`](../event_crm/overview.md), [`sale_crm`](../sale_crm/overview.md), [`website_crm`](../website_crm/overview.md), [`website_crm_iap_reveal`](../website_crm_iap_reveal/overview.md), [`website_crm_livechat`](../website_crm_livechat/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_crm_full`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on
- [`module.crm_iap_enrich`](../../../agents/modules/generated/crm_iap_enrich.yaml) — depends_on
- [`module.crm_iap_mine`](../../../agents/modules/generated/crm_iap_mine.yaml) — depends_on
- [`module.crm_sms`](../../../agents/modules/generated/crm_sms.yaml) — depends_on
- [`module.event_crm`](../../../agents/modules/generated/event_crm.yaml) — depends_on
- [`module.sale_crm`](../../../agents/modules/generated/sale_crm.yaml) — depends_on
- [`module.website_crm`](../../../agents/modules/generated/website_crm.yaml) — depends_on
- [`module.website_crm_iap_reveal`](../../../agents/modules/generated/website_crm_iap_reveal.yaml) — depends_on
- [`module.website_crm_livechat`](../../../agents/modules/generated/website_crm_livechat.yaml) — depends_on
- [`module.website_crm_partner_assign`](../../../agents/modules/generated/website_crm_partner_assign.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
