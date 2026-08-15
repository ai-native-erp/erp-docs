---
layout: page
title: "Saudi Arabia - E-invoicing (l10n_sa_edi)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_sa_edi/
nav_order: 0
---
# Saudi Arabia - E-invoicing — `l10n_sa_edi`

**Source:** [`agents/modules/generated/l10n_sa_edi.yaml`](../../agents/modules/generated/l10n_sa_edi.yaml) · **Wiki:** [`knowledge/modules/l10n_sa_edi/overview.md`](../../knowledge/modules/l10n_sa_edi/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_sa_edi</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Saudi Arabia - E-invoicing</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_sa_edi</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_sa_edi"><code>126b5bd</code></a></div></div>
</div>
## Purpose

E-Invoicing, Universal Business Language

## Direct dependencies

[`account_debit_note`](account_debit_note.md), [`account_edi`](account_edi.md), [`account_edi_ubl_cii`](account_edi_ubl_cii.md), [`base_vat`](base_vat.md), [`l10n_sa`](l10n_sa.md)

## Reverse dependencies (modules that depend on this)

[`l10n_sa_edi_pos`](l10n_sa_edi_pos.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.xml.ubl_21.zatca</code></div><div class="role">defined by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>l10n_sa_edi.otp.wizard</code></div><div class="role">defined by <code>l10n_sa_edi</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>account.debit.note</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>account.edi.document</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>account.edi.format</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.ubl_21</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>account.move.reversal</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>account.move.send</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>account.tax</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>l10n_sa_edi</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_debit_note` | depends_on, extends_model_from | `agents/modules/generated/account_debit_note.yaml` |
| `module.account_edi` | depends_on, extends_model_from | `agents/modules/generated/account_edi.yaml` |
| `module.account_edi_ubl_cii` | depends_on, extends_model_from | `agents/modules/generated/account_edi_ubl_cii.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_vat` | depends_on | `agents/modules/generated/base_vat.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sa` | depends_on | `agents/modules/generated/l10n_sa.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_sa_edi`](../../../agents/modules/generated/l10n_sa_edi.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/EDI
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_sa_edi)
- Direct dependencies: [`account_debit_note`](../account_debit_note/overview.md), [`account_edi`](../account_edi/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`base_vat`](../base_vat/overview.md), [`l10n_sa`](../l10n_sa/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_sa_edi_pos`](../l10n_sa_edi_pos/overview.md)
- Impact graph: [`module:l10n_sa_edi`](../../impact-graph.json)

## Purpose

E-Invoicing, Universal Business Language

## Model relationships

- `account.edi.xml.ubl_21.zatca` — extended by [`l10n_sa_edi_pos`](../l10n_sa_edi_pos/overview.md)
- `l10n_sa_edi.otp.wizard`
- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.debit.note` — defined by [`account_debit_note`](../account_debit_note/overview.md)
- Extends `account.edi.document` — defined by [`account_edi`](../account_edi/overview.md)
- Extends `account.edi.format` — defined by [`account_edi`](../account_edi/overview.md)
- Extends `account.edi.xml.ubl_21` — defined by [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md)
- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `account.move.reversal` — defined by [`account`](../account/overview.md)
- Extends `account.move.send` — defined by [`account`](../account/overview.md)
- Extends `account.tax` — defined by [`account`](../account/overview.md)
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_debit_note`](../../../agents/modules/generated/account_debit_note.yaml) — depends_on, extends_model_from
- [`module.account_edi`](../../../agents/modules/generated/account_edi.yaml) — depends_on, extends_model_from
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_vat`](../../../agents/modules/generated/base_vat.yaml) — depends_on
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sa`](../../../agents/modules/generated/l10n_sa.yaml) — depends_on
- [`module.l10n_sa_edi_pos`](../../../agents/modules/generated/l10n_sa_edi_pos.yaml) — model_extended_by, required_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`l10n_sa_edi_pos`](../l10n_sa_edi_pos/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`account_debit_note`](../account_debit_note/overview.md), [`account_edi`](../account_edi/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sale`](../sale/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl, qa_upgrade.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
