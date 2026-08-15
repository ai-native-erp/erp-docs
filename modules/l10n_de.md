---
layout: page
title: "Germany - Accounting (l10n_de)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_de/
nav_order: 0
---
# Germany - Accounting — `l10n_de`

**Source:** [`agents/modules/generated/l10n_de.yaml`](../../agents/modules/generated/l10n_de.yaml) · **Wiki:** [`knowledge/modules/l10n_de/overview.md`](../../knowledge/modules/l10n_de/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_de</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Germany - Accounting</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_de</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_de"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base_iban`](base_iban.md), [`base_vat`](base_vat.md), [`l10n_din5008`](l10n_din5008.md)

## Reverse dependencies (modules that depend on this)

[`l10n_account_edi_ubl_cii_tests`](l10n_account_edi_ubl_cii_tests.md), [`l10n_de_audit_trail`](l10n_de_audit_trail.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.account</code></div><div class="role">extended by <code>l10n_de</code></div></div>
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>l10n_de</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>l10n_de</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_de</code></div></div>
<div class="model"><div class="name"><code>account.tax</code></div><div class="role">extended by <code>l10n_de</code></div></div>
<div class="model"><div class="name"><code>ir.actions.report</code></div><div class="role">extended by <code>l10n_de</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>l10n_de</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>l10n_de</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>l10n_de</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_iban` | depends_on | `agents/modules/generated/base_iban.yaml` |
| `module.base_vat` | depends_on | `agents/modules/generated/base_vat.yaml` |
| `module.l10n_account_edi_ubl_cii_tests` | required_by | `agents/modules/generated/l10n_account_edi_ubl_cii_tests.yaml` |
| `module.l10n_de_audit_trail` | required_by | `agents/modules/generated/l10n_de_audit_trail.yaml` |
| `module.l10n_din5008` | depends_on | `agents/modules/generated/l10n_din5008.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Account Charts
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_de)
- Direct dependencies: [`base_iban`](../base_iban/overview.md), [`base_vat`](../base_vat/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_account_edi_ubl_cii_tests`](../l10n_account_edi_ubl_cii_tests/overview.md), [`l10n_de_audit_trail`](../l10n_de_audit_trail/overview.md)
- Impact graph: [`module:l10n_de`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.account` — defined by [`account`](../account/overview.md)
- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.tax` — defined by [`account`](../account/overview.md)
- Extends `ir.actions.report` — defined by [`base`](../base/overview.md)
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_iban`](../../../agents/modules/generated/base_iban.yaml) — depends_on
- [`module.base_vat`](../../../agents/modules/generated/base_vat.yaml) — depends_on
- [`module.l10n_account_edi_ubl_cii_tests`](../../../agents/modules/generated/l10n_account_edi_ubl_cii_tests.yaml) — required_by
- [`module.l10n_de_audit_trail`](../../../agents/modules/generated/l10n_de_audit_trail.yaml) — required_by
- [`module.l10n_din5008`](../../../agents/modules/generated/l10n_din5008.yaml) — depends_on
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`mrp_account`](../mrp_account/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: qa_upgrade.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
