---
layout: page
title: "SMS in CRM (crm_sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/crm_sms/
nav_order: 0
---
# SMS in CRM — `crm_sms`

**Source:** [`agents/modules/generated/crm_sms.yaml`](../../agents/modules/generated/crm_sms.yaml) · **Wiki:** [`knowledge/modules/crm_sms/overview.md`](../../knowledge/modules/crm_sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>crm_sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">SMS in CRM</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/crm_sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/crm_sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Add SMS capabilities to CRM

## Direct dependencies

[`crm`](crm.md), [`sms`](sms.md)

## Reverse dependencies (modules that depend on this)

[`test_crm_full`](test_crm_full.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.crm` | depends_on | `agents/modules/generated/crm.yaml` |
| `module.sms` | depends_on | `agents/modules/generated/sms.yaml` |
| `module.test_crm_full` | required_by | `agents/modules/generated/test_crm_full.yaml` |

## Full wiki excerpt

- SME owner: [`module.crm_sms`](../../../agents/modules/generated/crm_sms.yaml)
- Domain: `sales_crm`
- Category: Sales/CRM
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/crm_sms)
- Direct dependencies: [`crm`](../crm/overview.md), [`sms`](../sms/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_crm_full`](../test_crm_full/overview.md)
- Impact graph: [`module:crm_sms`](../../impact-graph.json)

## Purpose

Add SMS capabilities to CRM

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on
- [`module.test_crm_full`](../../../agents/modules/generated/test_crm_full.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
