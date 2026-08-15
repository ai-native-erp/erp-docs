---
layout: page
title: "Lead Livechat Sessions (website_crm_livechat)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_crm_livechat/
nav_order: 0
---
# Lead Livechat Sessions — `website_crm_livechat`

**Source:** [`agents/modules/generated/website_crm_livechat.yaml`](../../agents/modules/generated/website_crm_livechat.yaml) · **Wiki:** [`knowledge/modules/website_crm_livechat/overview.md`](../../knowledge/modules/website_crm_livechat/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_crm_livechat</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Lead Livechat Sessions</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_crm_livechat</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_crm_livechat"><code>126b5bd</code></a></div></div>
</div>
## Purpose

View livechat sessions for leads

## Direct dependencies

[`website_crm`](website_crm.md), [`website_livechat`](website_livechat.md)

## Reverse dependencies (modules that depend on this)

[`test_crm_full`](test_crm_full.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>chatbot.script.step</code></div><div class="role">extended by <code>website_crm_livechat</code></div></div>
<div class="model"><div class="name"><code>crm.lead</code></div><div class="role">extended by <code>website_crm_livechat</code></div></div>
<div class="model"><div class="name"><code>discuss.channel</code></div><div class="role">extended by <code>website_crm_livechat</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.im_livechat` | extends_model_from | `agents/modules/generated/im_livechat.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.test_crm_full` | required_by | `agents/modules/generated/test_crm_full.yaml` |
| `module.website_crm` | depends_on | `agents/modules/generated/website_crm.yaml` |
| `module.website_livechat` | depends_on | `agents/modules/generated/website_livechat.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_crm_livechat`](../../../agents/modules/generated/website_crm_livechat.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_crm_livechat)
- Direct dependencies: [`website_crm`](../website_crm/overview.md), [`website_livechat`](../website_livechat/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_crm_full`](../test_crm_full/overview.md)
- Impact graph: [`module:website_crm_livechat`](../../impact-graph.json)

## Purpose

View livechat sessions for leads

## Model relationships

- Extends `chatbot.script.step` — defined by [`im_livechat`](../im_livechat/overview.md)
- Extends `crm.lead` — defined by [`crm`](../crm/overview.md)
- Extends `discuss.channel` — defined by [`im_livechat`](../im_livechat/overview.md), [`mail`](../mail/overview.md)

## Related SME agents

- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.test_crm_full`](../../../agents/modules/generated/test_crm_full.yaml) — required_by
- [`module.website_crm`](../../../agents/modules/generated/website_crm.yaml) — depends_on
- [`module.website_livechat`](../../../agents/modules/generated/website_livechat.yaml) — depends_on

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`crm`](../crm/overview.md), [`im_livechat`](../im_livechat/overview.md), [`mail`](../mail/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
