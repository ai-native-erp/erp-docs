---
layout: page
title: "CRM Livechat (crm_livechat)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/crm_livechat/
nav_order: 0
---
# CRM Livechat — `crm_livechat`

**Source:** [`agents/modules/generated/crm_livechat.yaml`](../../agents/modules/generated/crm_livechat.yaml) · **Wiki:** [`knowledge/modules/crm_livechat/overview.md`](../../knowledge/modules/crm_livechat/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>crm_livechat</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">CRM Livechat</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/crm_livechat</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/crm_livechat"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Create lead from livechat conversation

## Direct dependencies

[`crm`](crm.md), [`im_livechat`](im_livechat.md)

## Reverse dependencies (modules that depend on this)

[`test_discuss_full`](test_discuss_full.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>chatbot.script</code></div><div class="role">extended by <code>crm_livechat</code></div></div>
<div class="model"><div class="name"><code>chatbot.script.step</code></div><div class="role">extended by <code>crm_livechat</code></div></div>
<div class="model"><div class="name"><code>discuss.channel</code></div><div class="role">extended by <code>crm_livechat</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.crm` | depends_on | `agents/modules/generated/crm.yaml` |
| `module.im_livechat` | depends_on, extends_model_from | `agents/modules/generated/im_livechat.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.test_discuss_full` | required_by | `agents/modules/generated/test_discuss_full.yaml` |

## Full wiki excerpt

- SME owner: [`module.crm_livechat`](../../../agents/modules/generated/crm_livechat.yaml)
- Domain: `sales_crm`
- Category: Sales/CRM
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/crm_livechat)
- Direct dependencies: [`crm`](../crm/overview.md), [`im_livechat`](../im_livechat/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_discuss_full`](../test_discuss_full/overview.md)
- Impact graph: [`module:crm_livechat`](../../impact-graph.json)

## Purpose

Create lead from livechat conversation

## Model relationships

- Extends `chatbot.script` — defined by [`im_livechat`](../im_livechat/overview.md)
- Extends `chatbot.script.step` — defined by [`im_livechat`](../im_livechat/overview.md)
- Extends `discuss.channel` — defined by [`im_livechat`](../im_livechat/overview.md), [`mail`](../mail/overview.md)

## Related SME agents

- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — depends_on, extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.test_discuss_full`](../../../agents/modules/generated/test_discuss_full.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`im_livechat`](../im_livechat/overview.md), [`mail`](../mail/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
