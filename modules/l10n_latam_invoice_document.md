---
layout: page
title: "LATAM Document (l10n_latam_invoice_document)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_latam_invoice_document/
nav_order: 0
---
# LATAM Document — `l10n_latam_invoice_document`

**Source:** [`agents/modules/generated/l10n_latam_invoice_document.yaml`](../../agents/modules/generated/l10n_latam_invoice_document.yaml) · **Wiki:** [`knowledge/modules/l10n_latam_invoice_document/overview.md`](../../knowledge/modules/l10n_latam_invoice_document/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_latam_invoice_document</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">LATAM Document</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_latam_invoice_document</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_latam_invoice_document"><code>126b5bd</code></a></div></div>
</div>
## Purpose

LATAM Document Types

## Direct dependencies

[`account`](account.md), [`account_debit_note`](account_debit_note.md)

## Reverse dependencies (modules that depend on this)

[`l10n_ar`](l10n_ar.md), [`l10n_br`](l10n_br.md), [`l10n_cl`](l10n_cl.md), [`l10n_ec`](l10n_ec.md), [`l10n_pe`](l10n_pe.md), [`l10n_uy`](l10n_uy.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>l10n_latam.document.type</code></div><div class="role">defined by <code>l10n_latam_invoice_document</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>l10n_latam_invoice_document</code></div></div>
<div class="model"><div class="name"><code>account.debit.note</code></div><div class="role">extended by <code>l10n_latam_invoice_document</code></div></div>
<div class="model"><div class="name"><code>account.invoice.report</code></div><div class="role">extended by <code>l10n_latam_invoice_document</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>l10n_latam_invoice_document</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_latam_invoice_document</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>l10n_latam_invoice_document</code></div></div>
<div class="model"><div class="name"><code>account.move.reversal</code></div><div class="role">extended by <code>l10n_latam_invoice_document</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>l10n_latam_invoice_document</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_debit_note` | depends_on, extends_model_from | `agents/modules/generated/account_debit_note.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_ar` | model_extended_by, required_by | `agents/modules/generated/l10n_ar.yaml` |
| `module.l10n_br` | required_by | `agents/modules/generated/l10n_br.yaml` |
| `module.l10n_cl` | model_extended_by, required_by | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_ec` | model_extended_by, required_by | `agents/modules/generated/l10n_ec.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_pe` | required_by | `agents/modules/generated/l10n_pe.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_latam_invoice_document`](../../../agents/modules/generated/l10n_latam_invoice_document.yaml)
- Domain: `localization`
- Category: Accounting/Localizations
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_latam_invoice_document)
- Direct dependencies: [`account`](../account/overview.md), [`account_debit_note`](../account_debit_note/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_ar`](../l10n_ar/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_uy`](../l10n_uy/overview.md)
- Impact graph: [`module:l10n_latam_invoice_document`](../../impact-graph.json)

## Purpose

LATAM Document Types

## Model relationships

- `l10n_latam.document.type` — extended by [`l10n_ar`](../l10n_ar/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_uy`](../l10n_uy/overview.md)
- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.debit.note` — defined by [`account_debit_note`](../account_debit_note/overview.md)
- Extends `account.invoice.report` — defined by [`account`](../account/overview.md)
- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `account.move.reversal` — defined by [`account`](../account/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.account_debit_note`](../../../agents/modules/generated/account_debit_note.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_ar`](../../../agents/modules/generated/l10n_ar.yaml) — model_extended_by, required_by
- [`module.l10n_br`](../../../agents/modules/generated/l10n_br.yaml) — required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — model_extended_by, required_by
- [`module.l10n_ec`](../../../agents/modules/generated/l10n_ec.yaml) — model_extended_by, required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_pe`](../../../agents/modules/generated/l10n_pe.yaml) — required_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.l10n_uy`](../../../agents/modules/generated/l10n_uy.yaml) — model_extended_by, required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 6 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`l10n_ar`](../l10n_ar/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_uy`](../l10n_uy/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`account_debit_note`](../account_debit_note/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
