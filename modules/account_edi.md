---
layout: page
title: "Import/Export Invoices From XML/PDF (account_edi)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_edi/
nav_order: 0
---
# Import/Export Invoices From XML/PDF — `account_edi`

**Source:** [`agents/modules/generated/account_edi.yaml`](../../agents/modules/generated/account_edi.yaml) · **Wiki:** [`knowledge/modules/account_edi/overview.md`](../../knowledge/modules/account_edi/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_edi</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Import/Export Invoices From XML/PDF</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_edi</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_edi"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md)

## Reverse dependencies (modules that depend on this)

[`l10n_eg_edi_eta`](l10n_eg_edi_eta.md), [`l10n_es_edi_sii`](l10n_es_edi_sii.md), [`l10n_in_edi`](l10n_in_edi.md), [`l10n_sa_edi`](l10n_sa_edi.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.document</code></div><div class="role">defined by <code>account_edi</code></div></div>
<div class="model"><div class="name"><code>account.edi.format</code></div><div class="role">defined by <code>account_edi</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>account_edi</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>account_edi</code></div></div>
<div class="model"><div class="name"><code>account.move.send</code></div><div class="role">extended by <code>account_edi</code></div></div>
<div class="model"><div class="name"><code>account.resequence.wizard</code></div><div class="role">extended by <code>account_edi</code></div></div>
<div class="model"><div class="name"><code>ir.actions.report</code></div><div class="role">extended by <code>account_edi</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>account_edi</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_eg_edi_eta` | model_extended_by, required_by | `agents/modules/generated/l10n_eg_edi_eta.yaml` |
| `module.l10n_es_edi_sii` | model_extended_by, required_by | `agents/modules/generated/l10n_es_edi_sii.yaml` |
| `module.l10n_es_edi_tbai` | model_extended_by | `agents/modules/generated/l10n_es_edi_tbai.yaml` |
| `module.l10n_es_edi_tbai_multi_refund` | model_extended_by | `agents/modules/generated/l10n_es_edi_tbai_multi_refund.yaml` |
| `module.l10n_in_edi` | model_extended_by, required_by | `agents/modules/generated/l10n_in_edi.yaml` |
| `module.l10n_in_edi_ewaybill` | model_extended_by | `agents/modules/generated/l10n_in_edi_ewaybill.yaml` |
| `module.l10n_in_ewaybill_port` | model_extended_by | `agents/modules/generated/l10n_in_ewaybill_port.yaml` |
| `module.l10n_sa_edi` | model_extended_by, required_by | `agents/modules/generated/l10n_sa_edi.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_edi`](../../../agents/modules/generated/account_edi.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_edi)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md)
- Impact graph: [`module:account_edi`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `account.edi.document` — extended by [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md)
- `account.edi.format` — extended by [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_tbai_multi_refund`](../l10n_es_edi_tbai_multi_refund/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_ewaybill_port`](../l10n_in_ewaybill_port/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md)
- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.send` — defined by [`account`](../account/overview.md)
- Extends `account.resequence.wizard` — defined by [`account`](../account/overview.md)
- Extends `ir.actions.report` — defined by [`base`](../base/overview.md)
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_eg_edi_eta`](../../../agents/modules/generated/l10n_eg_edi_eta.yaml) — model_extended_by, required_by
- [`module.l10n_es_edi_sii`](../../../agents/modules/generated/l10n_es_edi_sii.yaml) — model_extended_by, required_by
- [`module.l10n_es_edi_tbai`](../../../agents/modules/generated/l10n_es_edi_tbai.yaml) — model_extended_by
- [`module.l10n_es_edi_tbai_multi_refund`](../../../agents/modules/generated/l10n_es_edi_tbai_multi_refund.yaml) — model_extended_by
- [`module.l10n_in_edi`](../../../agents/modules/generated/l10n_in_edi.yaml) — model_extended_by, required_by
- [`module.l10n_in_edi_ewaybill`](../../../agents/modules/generated/l10n_in_edi_ewaybill.yaml) — model_extended_by
- [`module.l10n_in_ewaybill_port`](../../../agents/modules/generated/l10n_in_ewaybill_port.yaml) — model_extended_by
- [`module.l10n_sa_edi`](../../../agents/modules/generated/l10n_sa_edi.yaml) — model_extended_by, required_by
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_tbai_multi_refund`](../l10n_es_edi_tbai_multi_refund/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_ewaybill_port`](../l10n_in_ewaybill_port/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
