---
layout: page
title: "CRM Mail Plugin (crm_mail_plugin)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/crm_mail_plugin/
nav_order: 0
---
# CRM Mail Plugin — `crm_mail_plugin`

**Source:** [`agents/modules/generated/crm_mail_plugin.yaml`](../../agents/modules/generated/crm_mail_plugin.yaml) · **Wiki:** [`knowledge/modules/crm_mail_plugin/overview.md`](../../knowledge/modules/crm_mail_plugin/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>crm_mail_plugin</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">CRM Mail Plugin</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/crm_mail_plugin</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/crm_mail_plugin"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Turn emails received in your mailbox into leads and log their content as internal notes.

## Direct dependencies

[`crm`](crm.md), [`mail_plugin`](mail_plugin.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.lead</code></div><div class="role">extended by <code>crm_mail_plugin</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.crm` | depends_on, extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.mail_plugin` | depends_on | `agents/modules/generated/mail_plugin.yaml` |

## Full wiki excerpt

- SME owner: [`module.crm_mail_plugin`](../../../agents/modules/generated/crm_mail_plugin.yaml)
- Domain: `sales_crm`
- Category: Sales/CRM
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/crm_mail_plugin)
- Direct dependencies: [`crm`](../crm/overview.md), [`mail_plugin`](../mail_plugin/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:crm_mail_plugin`](../../impact-graph.json)

## Purpose

Turn emails received in your mailbox into leads and log their content as internal notes.

## Model relationships

- Extends `crm.lead` — defined by [`crm`](../crm/overview.md)

## Related SME agents

- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on, extends_model_from
- [`module.mail_plugin`](../../../agents/modules/generated/mail_plugin.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`crm`](../crm/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
