---
layout: page
title: "Sale - SMS (sale_sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_sms/
nav_order: 0
---
# Sale - SMS — `sale_sms`

**Source:** [`agents/modules/generated/sale_sms.yaml`](../../agents/modules/generated/sale_sms.yaml) · **Wiki:** [`knowledge/modules/sale_sms/overview.md`](../../knowledge/modules/sale_sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sale - SMS</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Ease SMS integration with sales capabilities

## Direct dependencies

[`sale`](sale.md), [`sms`](sms.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.sale` | depends_on | `agents/modules/generated/sale.yaml` |
| `module.sms` | depends_on | `agents/modules/generated/sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_sms`](../../../agents/modules/generated/sale_sms.yaml)
- Domain: `sales_crm`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_sms)
- Direct dependencies: [`sale`](../sale/overview.md), [`sms`](../sms/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:sale_sms`](../../impact-graph.json)

## Purpose

Ease SMS integration with sales capabilities

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.sale`](../../../agents/modules/generated/sale.yaml) — depends_on
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
