---
layout: page
title: "Import/Export electronic invoices with UBL/CII (account_edi_ubl_cii)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_edi_ubl_cii/
nav_order: 0
---
# Import/Export electronic invoices with UBL/CII — `account_edi_ubl_cii`

**Source:** [`agents/modules/generated/account_edi_ubl_cii.yaml`](../../agents/modules/generated/account_edi_ubl_cii.yaml) · **Wiki:** [`knowledge/modules/account_edi_ubl_cii/overview.md`](../../knowledge/modules/account_edi_ubl_cii/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_edi_ubl_cii</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Import/Export electronic invoices with UBL/CII</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_edi_ubl_cii</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_edi_ubl_cii"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md)

## Reverse dependencies (modules that depend on this)

[`account_edi_ubl_cii_tax_extension`](account_edi_ubl_cii_tax_extension.md), [`account_peppol`](account_peppol.md), [`l10n_account_edi_ubl_cii_tests`](l10n_account_edi_ubl_cii_tests.md), [`l10n_dk_oioubl`](l10n_dk_oioubl.md), [`l10n_fr_facturx_chorus_pro`](l10n_fr_facturx_chorus_pro.md), [`l10n_jo_edi`](l10n_jo_edi.md), [`l10n_jp_ubl_pint`](l10n_jp_ubl_pint.md), [`l10n_my_ubl_pint`](l10n_my_ubl_pint.md), [`l10n_ro_edi`](l10n_ro_edi.md), [`l10n_rs_edi`](l10n_rs_edi.md), [`l10n_sa_edi`](l10n_sa_edi.md), [`l10n_tr_nilvera_einvoice`](l10n_tr_nilvera_einvoice.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.common</code></div><div class="role">defined by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.cii</code></div><div class="role">defined by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.ubl_20</code></div><div class="role">defined by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.ubl_21</code></div><div class="role">defined by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.ubl_a_nz</code></div><div class="role">defined by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.ubl_bis3</code></div><div class="role">defined by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.ubl_de</code></div><div class="role">defined by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.ubl_efff</code></div><div class="role">defined by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.ubl_nl</code></div><div class="role">defined by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.ubl_sg</code></div><div class="role">defined by <code>account_edi_ubl_cii</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.common</code></div><div class="role">extended by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.ubl_20</code></div><div class="role">extended by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.ubl_21</code></div><div class="role">extended by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.edi.xml.ubl_bis3</code></div><div class="role">extended by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>account.move.send</code></div><div class="role">extended by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>ir.actions.report</code></div><div class="role">extended by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>account_edi_ubl_cii</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>account_edi_ubl_cii</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_edi_ubl_cii_tax_extension` | model_extended_by, required_by | `agents/modules/generated/account_edi_ubl_cii_tax_extension.yaml` |
| `module.account_peppol` | required_by | `agents/modules/generated/account_peppol.yaml` |
| `module.account_peppol_selfbilling` | model_extended_by | `agents/modules/generated/account_peppol_selfbilling.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.l10n_account_edi_ubl_cii_tests` | required_by | `agents/modules/generated/l10n_account_edi_ubl_cii_tests.yaml` |
| `module.l10n_anz_ubl_pint` | model_extended_by | `agents/modules/generated/l10n_anz_ubl_pint.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_dk_oioubl` | required_by | `agents/modules/generated/l10n_dk_oioubl.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_edi_ubl_cii)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`account_edi_ubl_cii_tax_extension`](../account_edi_ubl_cii_tax_extension/overview.md), [`account_peppol`](../account_peppol/overview.md), [`l10n_account_edi_ubl_cii_tests`](../l10n_account_edi_ubl_cii_tests/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_fr_facturx_chorus_pro`](../l10n_fr_facturx_chorus_pro/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md)
- Impact graph: [`module:account_edi_ubl_cii`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `account.edi.common` — extended by [`account_edi_ubl_cii_tax_extension`](../account_edi_ubl_cii_tax_extension/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md)
- `account.edi.xml.cii` — extended by [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md)
- `account.edi.xml.ubl_20`
- `account.edi.xml.ubl_21` — extended by [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md)
- `account.edi.xml.ubl_a_nz`
- `account.edi.xml.ubl_bis3` — extended by [`account_peppol_selfbilling`](../account_peppol_selfbilling/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_fr_facturx_chorus_pro`](../l10n_fr_facturx_chorus_pro/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md)
- `account.edi.xml.ubl_de`
- `account.edi.xml.ubl_efff`
- `account.edi.xml.ubl_nl`
- `account.edi.xml.ubl_sg`
- Extends `account.edi.common` — framework/dynamic owner
- Extends `account.edi.xml.ubl_20` — framework/dynamic owner
- Extends `account.edi.xml.ubl_21` — framework/dynamic owner
- Extends `account.edi.xml.ubl_bis3` — framework/dynamic owner
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.send` — defined by [`account`](../account/overview.md)
- Extends `ir.actions.report` — defined by [`base`](../base/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.account_edi_ubl_cii_tax_extension`](../../../agents/modules/generated/account_edi_ubl_cii_tax_extension.yaml) — model_extended_by, required_by
- [`module.account_peppol`](../../../agents/modules/generated/account_peppol.yaml) — required_by
- [`module.account_peppol_selfbilling`](../../../agents/modules/generated/account_peppol_selfbilling.yaml) — model_extended_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.l10n_account_edi_ubl_cii_tests`](../../../agents/modules/generated/l10n_account_edi_ubl_cii_tests.yaml) — required_by
- [`module.l10n_anz_ubl_pint`](../../../agents/modules/generated/l10n_anz_ubl_pint.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_dk_oioubl`](../../../agents/modules/generated/l10n_dk_oioubl.yaml) — required_by
- [`module.l10n_fr_facturx_chorus_pro`](../../../agents/modules/generated/l10n_fr_facturx_chorus_pro.yaml) — model_extended_by, required_by
- [`module.l10n_fr_pdp`](../../../agents/modules/generated/l10n_fr_pdp.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_jo_edi`](../../../agents/modules/generated/l10n_jo_edi.yaml) — model_extended_by, required_by
- [`module.l10n_jp_ubl_pint`](../../../agents/modules/generated/l10n_jp_ubl_pint.yaml) — model_extended_by, required_by
- [`module.l10n_my_edi`](../../../agents/modules/generated/l10n_my_edi.yaml) — model_extended_by
- [`module.l10n_my_ubl_pint`](../../../agents/modules/generated/l10n_my_ubl_pint.yaml) — model_extended_by, required_by
- [`module.l10n_ro_edi`](../../../agents/modules/generated/l10n_ro_edi.yaml) — model_extended_by, required_by
- [`module.l10n_rs_edi`](../../../agents/modules/generated/l10n_rs_edi.yaml) — model_extended_by, required_by
- [`module.l10n_sa_edi`](../../../agents/modules/generated/l10n_sa_edi.yaml) — model_extended_by, required_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_sg_ubl_pint`](../../../agents/modules/generated/l10n_sg_ubl_pint.yaml) — model_extended_by
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from, model_extended_by, required_by
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

- Review 12 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account_edi_ubl_cii_tax_extension`](../account_edi_ubl_cii_tax_extension/overview.md), [`account_peppol_selfbilling`](../account_peppol_selfbilling/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_fr_facturx_chorus_pro`](../l10n_fr_facturx_chorus_pro/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sale`](../sale/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
