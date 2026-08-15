---
layout: page
title: "Debit Notes (account_debit_note)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_debit_note/
nav_order: 0
---
# Debit Notes — `account_debit_note`

**Source:** [`agents/modules/generated/account_debit_note.yaml`](../../agents/modules/generated/account_debit_note.yaml) · **Wiki:** [`knowledge/modules/account_debit_note/overview.md`](../../knowledge/modules/account_debit_note/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_debit_note</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Debit Notes</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_debit_note</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_debit_note"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Debit Notes

## Direct dependencies

[`account`](account.md)

## Reverse dependencies (modules that depend on this)

[`account_debit_note_sequence`](account_debit_note_sequence.md), [`l10n_co`](l10n_co.md), [`l10n_ec`](l10n_ec.md), [`l10n_hu_edi`](l10n_hu_edi.md), [`l10n_it_edi_ndd_account_dn`](l10n_it_edi_ndd_account_dn.md), [`l10n_latam_invoice_document`](l10n_latam_invoice_document.md), [`l10n_pe`](l10n_pe.md), [`l10n_sa_edi`](l10n_sa_edi.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.debit.note</code></div><div class="role">defined by <code>account_debit_note</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>account_debit_note</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_debit_note_sequence` | required_by | `agents/modules/generated/account_debit_note_sequence.yaml` |
| `module.l10n_co` | required_by | `agents/modules/generated/l10n_co.yaml` |
| `module.l10n_ec` | required_by | `agents/modules/generated/l10n_ec.yaml` |
| `module.l10n_hu_edi` | model_extended_by, required_by | `agents/modules/generated/l10n_hu_edi.yaml` |
| `module.l10n_it_edi_ndd_account_dn` | required_by | `agents/modules/generated/l10n_it_edi_ndd_account_dn.yaml` |
| `module.l10n_latam_invoice_document` | model_extended_by, required_by | `agents/modules/generated/l10n_latam_invoice_document.yaml` |
| `module.l10n_pe` | required_by | `agents/modules/generated/l10n_pe.yaml` |
| `module.l10n_sa_edi` | model_extended_by, required_by | `agents/modules/generated/l10n_sa_edi.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_debit_note`](../../../agents/modules/generated/account_debit_note.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_debit_note)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`account_debit_note_sequence`](../account_debit_note_sequence/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_it_edi_ndd_account_dn`](../l10n_it_edi_ndd_account_dn/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md)
- Impact graph: [`module:account_debit_note`](../../impact-graph.json)

## Purpose

Debit Notes

## Model relationships

- `account.debit.note` — extended by [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.account_debit_note_sequence`](../../../agents/modules/generated/account_debit_note_sequence.yaml) — required_by
- [`module.l10n_co`](../../../agents/modules/generated/l10n_co.yaml) — required_by
- [`module.l10n_ec`](../../../agents/modules/generated/l10n_ec.yaml) — required_by
- [`module.l10n_hu_edi`](../../../agents/modules/generated/l10n_hu_edi.yaml) — model_extended_by, required_by
- [`module.l10n_it_edi_ndd_account_dn`](../../../agents/modules/generated/l10n_it_edi_ndd_account_dn.yaml) — required_by
- [`module.l10n_latam_invoice_document`](../../../agents/modules/generated/l10n_latam_invoice_document.yaml) — model_extended_by, required_by
- [`module.l10n_pe`](../../../agents/modules/generated/l10n_pe.yaml) — required_by
- [`module.l10n_sa_edi`](../../../agents/modules/generated/l10n_sa_edi.yaml) — model_extended_by, required_by
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 8 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
