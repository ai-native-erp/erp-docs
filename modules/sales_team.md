---
layout: page
title: "Sales Teams (sales_team)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sales_team/
nav_order: 0
---
# Sales Teams — `sales_team`

**Source:** [`agents/modules/generated/sales_team.yaml`](../../agents/modules/generated/sales_team.yaml) · **Wiki:** [`knowledge/modules/sales_team/overview.md`](../../knowledge/modules/sales_team/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sales_team</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sales Teams</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sales_team</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sales_team"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Sales Teams

## Direct dependencies

[`base`](base.md), [`mail`](mail.md)

## Reverse dependencies (modules that depend on this)

[`crm`](crm.md), [`sale`](sale.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.tag</code></div><div class="role">defined by <code>sales_team</code></div></div>
<div class="model"><div class="name"><code>crm.team</code></div><div class="role">defined by <code>sales_team</code></div></div>
<div class="model"><div class="name"><code>crm.team.member</code></div><div class="role">defined by <code>sales_team</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>sales_team</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>sales_team</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>sales_team</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | extends_model_from, model_extended_by, required_by | `agents/modules/generated/crm.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera.yaml` |
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |

## Full wiki excerpt

- SME owner: [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sales_team)
- Direct dependencies: [`base`](../base/overview.md), [`mail`](../mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`crm`](../crm/overview.md), [`sale`](../sale/overview.md)
- Impact graph: [`module:sales_team`](../../impact-graph.json)

## Purpose

Sales Teams

## Model relationships

- `crm.tag`
- `crm.team` — extended by [`crm`](../crm/overview.md), [`pos_sale`](../pos_sale/overview.md), [`sale`](../sale/overview.md), [`sale_crm`](../sale_crm/overview.md), [`website_sale`](../website_sale/overview.md)
- `crm.team.member` — extended by [`crm`](../crm/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from, model_extended_by, required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — model_extended_by, required_by
- [`module.sale_crm`](../../../agents/modules/generated/sale_crm.yaml) — model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`crm`](../crm/overview.md), [`pos_sale`](../pos_sale/overview.md), [`sale`](../sale/overview.md), [`sale_crm`](../sale_crm/overview.md), [`website_sale`](../website_sale/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
