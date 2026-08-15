---
layout: page
title: "Argentina - Accounting (l10n_ar)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_ar/
nav_order: 0
---
# Argentina - Accounting — `l10n_ar`

**Source:** [`agents/modules/generated/l10n_ar.yaml`](../../agents/modules/generated/l10n_ar.yaml) · **Wiki:** [`knowledge/modules/l10n_ar/overview.md`](../../knowledge/modules/l10n_ar/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_ar</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Argentina - Accounting</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_ar</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ar"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_latam_base`](l10n_latam_base.md), [`l10n_latam_invoice_document`](l10n_latam_invoice_document.md)

## Reverse dependencies (modules that depend on this)

[`l10n_ar_pos`](l10n_ar_pos.md), [`l10n_ar_website_sale`](l10n_ar_website_sale.md), [`l10n_ar_withholding`](l10n_ar_withholding.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>l10n_ar.afip.responsibility.type</code></div><div class="role">defined by <code>l10n_ar</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>account.fiscal.position</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>account.invoice.report</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>account.tax.group</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>l10n_latam.document.type</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>l10n_latam.identification.type</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>res.country</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>res.currency</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>res.partner.bank</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
<div class="model"><div class="name"><code>uom.uom</code></div><div class="role">extended by <code>l10n_ar</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.l10n_ar_pos` | required_by | `agents/modules/generated/l10n_ar_pos.yaml` |
| `module.l10n_ar_website_sale` | required_by | `agents/modules/generated/l10n_ar_website_sale.yaml` |
| `module.l10n_ar_withholding` | required_by | `agents/modules/generated/l10n_ar_withholding.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_latam_base` | depends_on, extends_model_from | `agents/modules/generated/l10n_latam_base.yaml` |
| `module.l10n_latam_invoice_document` | depends_on, extends_model_from | `agents/modules/generated/l10n_latam_invoice_document.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_ar`](../../../agents/modules/generated/l10n_ar.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Account Charts
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ar)
- Direct dependencies: [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_ar_website_sale`](../l10n_ar_website_sale/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md)
- Impact graph: [`module:l10n_ar`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `l10n_ar.afip.responsibility.type`
- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.fiscal.position` — defined by [`account`](../account/overview.md)
- Extends `account.invoice.report` — defined by [`account`](../account/overview.md)
- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `account.tax.group` — defined by [`account`](../account/overview.md)
- Extends `l10n_latam.document.type` — defined by [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md)
- Extends `l10n_latam.identification.type` — defined by [`l10n_latam_base`](../l10n_latam_base/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.country` — defined by [`base`](../base/overview.md), [`l10n_cl`](../l10n_cl/overview.md)
- Extends `res.currency` — defined by [`base`](../base/overview.md), [`l10n_cl`](../l10n_cl/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.partner.bank` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md)
- Extends `uom.uom` — defined by [`uom`](../uom/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.l10n_ar_pos`](../../../agents/modules/generated/l10n_ar_pos.yaml) — required_by
- [`module.l10n_ar_website_sale`](../../../agents/modules/generated/l10n_ar_website_sale.yaml) — required_by
- [`module.l10n_ar_withholding`](../../../agents/modules/generated/l10n_ar_withholding.yaml) — required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_latam_base`](../../../agents/modules/generated/l10n_latam_base.yaml) — depends_on, extends_model_from
- [`module.l10n_latam_invoice_document`](../../../agents/modules/generated/l10n_latam_invoice_document.yaml) — depends_on, extends_model_from
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
- [`module.uom`](../../../agents/modules/generated/uom.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sale`](../sale/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`uom`](../uom/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
