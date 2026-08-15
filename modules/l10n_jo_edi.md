---
layout: page
title: "Jordan E-Invoicing (l10n_jo_edi)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_jo_edi/
nav_order: 0
---
# Jordan E-Invoicing — `l10n_jo_edi`

**Source:** [`agents/modules/generated/l10n_jo_edi.yaml`](../../agents/modules/generated/l10n_jo_edi.yaml) · **Wiki:** [`knowledge/modules/l10n_jo_edi/overview.md`](../../knowledge/modules/l10n_jo_edi/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_jo_edi</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Jordan E-Invoicing</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_jo_edi</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_jo_edi"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Electronic Invoicing for Jordan UBL 2.1

## Direct dependencies

[`account_edi_ubl_cii`](account_edi_ubl_cii.md), [`l10n_jo`](l10n_jo.md)

## Reverse dependencies (modules that depend on this)

[`l10n_jo_edi_extended`](l10n_jo_edi_extended.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.xml.ubl_21.jo</code></div><div class="role">defined by <code>l10n_jo_edi</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.xml.ubl_21</code></div><div class="role">extended by <code>l10n_jo_edi</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_jo_edi</code></div></div>
<div class="model"><div class="name"><code>account.move.send</code></div><div class="role">extended by <code>l10n_jo_edi</code></div></div>
<div class="model"><div class="name"><code>account.tax</code></div><div class="role">extended by <code>l10n_jo_edi</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>l10n_jo_edi</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>l10n_jo_edi</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>l10n_jo_edi</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_edi_ubl_cii` | depends_on, extends_model_from | `agents/modules/generated/account_edi_ubl_cii.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_jo` | depends_on | `agents/modules/generated/l10n_jo.yaml` |
| `module.l10n_jo_edi_extended` | required_by | `agents/modules/generated/l10n_jo_edi_extended.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_jo_edi`](../../../agents/modules/generated/l10n_jo_edi.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/EDI
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_jo_edi)
- Direct dependencies: [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`l10n_jo`](../l10n_jo/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md)
- Impact graph: [`module:l10n_jo_edi`](../../impact-graph.json)

## Purpose

Electronic Invoicing for Jordan UBL 2.1

## Model relationships

- `account.edi.xml.ubl_21.jo`
- Extends `account.edi.xml.ubl_21` — defined by [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.send` — defined by [`account`](../account/overview.md)
- Extends `account.tax` — defined by [`account`](../account/overview.md)
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_jo`](../../../agents/modules/generated/l10n_jo.yaml) — depends_on
- [`module.l10n_jo_edi_extended`](../../../agents/modules/generated/l10n_jo_edi_extended.yaml) — required_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
