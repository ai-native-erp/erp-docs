---
layout: page
title: "Opportunity to Quotation (sale_crm)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_crm/
nav_order: 0
---
# Opportunity to Quotation — `sale_crm`

**Source:** [`agents/modules/generated/sale_crm.yaml`](../../agents/modules/generated/sale_crm.yaml) · **Wiki:** [`knowledge/modules/sale_crm/overview.md`](../../knowledge/modules/sale_crm/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_crm</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Opportunity to Quotation</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_crm</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_crm"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`crm`](crm.md), [`sale`](sale.md)

## Reverse dependencies (modules that depend on this)

[`gamification_sale_crm`](gamification_sale_crm.md), [`test_crm_full`](test_crm_full.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.quotation.partner</code></div><div class="role">defined by <code>sale_crm</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.lead</code></div><div class="role">extended by <code>sale_crm</code></div></div>
<div class="model"><div class="name"><code>crm.team</code></div><div class="role">extended by <code>sale_crm</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>sale_crm</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_crm</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | depends_on, extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.gamification_sale_crm` | required_by | `agents/modules/generated/gamification_sale_crm.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.sale` | depends_on, extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.sales_team` | extends_model_from | `agents/modules/generated/sales_team.yaml` |
| `module.test_crm_full` | required_by | `agents/modules/generated/test_crm_full.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_crm`](../../../agents/modules/generated/sale_crm.yaml)
- Domain: `sales_crm`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_crm)
- Direct dependencies: [`crm`](../crm/overview.md), [`sale`](../sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`gamification_sale_crm`](../gamification_sale_crm/overview.md), [`test_crm_full`](../test_crm_full/overview.md)
- Impact graph: [`module:sale_crm`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `crm.quotation.partner`
- Extends `crm.lead` — defined by [`crm`](../crm/overview.md)
- Extends `crm.team` — defined by [`crm`](../crm/overview.md), [`sales_team`](../sales_team/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on, extends_model_from
- [`module.gamification_sale_crm`](../../../agents/modules/generated/gamification_sale_crm.yaml) — required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — depends_on, extends_model_from
- [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml) — extends_model_from
- [`module.test_crm_full`](../../../agents/modules/generated/test_crm_full.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`sale`](../sale/overview.md), [`sales_team`](../sales_team/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
