---
layout: page
title: "CRM Gamification (gamification_sale_crm)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/gamification_sale_crm/
nav_order: 0
---
# CRM Gamification — `gamification_sale_crm`

**Source:** [`agents/modules/generated/gamification_sale_crm.yaml`](../../agents/modules/generated/gamification_sale_crm.yaml) · **Wiki:** [`knowledge/modules/gamification_sale_crm/overview.md`](../../knowledge/modules/gamification_sale_crm/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>gamification_sale_crm</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">CRM Gamification</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/gamification_sale_crm</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/gamification_sale_crm"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`gamification`](gamification.md), [`sale_crm`](sale_crm.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.gamification` | depends_on | `agents/modules/generated/gamification.yaml` |
| `module.sale_crm` | depends_on | `agents/modules/generated/sale_crm.yaml` |

## Full wiki excerpt

- SME owner: [`module.gamification_sale_crm`](../../../agents/modules/generated/gamification_sale_crm.yaml)
- Domain: `platform_core`
- Category: Sales/CRM
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/gamification_sale_crm)
- Direct dependencies: [`gamification`](../gamification/overview.md), [`sale_crm`](../sale_crm/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:gamification_sale_crm`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.gamification`](../../../agents/modules/generated/gamification.yaml) — depends_on
- [`module.sale_crm`](../../../agents/modules/generated/sale_crm.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
