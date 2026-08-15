---
layout: page
title: "Spain - TicketBAI (l10n_es_edi_tbai)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_es_edi_tbai/
nav_order: 0
---
# Spain - TicketBAI — `l10n_es_edi_tbai`

**Source:** [`agents/modules/generated/l10n_es_edi_tbai.yaml`](../../agents/modules/generated/l10n_es_edi_tbai.yaml) · **Wiki:** [`knowledge/modules/l10n_es_edi_tbai/overview.md`](../../knowledge/modules/l10n_es_edi_tbai/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_es_edi_tbai</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Spain - TicketBAI</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_es_edi_tbai</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_es_edi_tbai"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_es_edi_sii`](l10n_es_edi_sii.md)

## Reverse dependencies (modules that depend on this)

[`l10n_es_edi_tbai_multi_refund`](l10n_es_edi_tbai_multi_refund.md), [`l10n_es_pos_tbai`](l10n_es_pos_tbai.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.document</code></div><div class="role">extended by <code>l10n_es_edi_tbai</code></div></div>
<div class="model"><div class="name"><code>account.edi.format</code></div><div class="role">extended by <code>l10n_es_edi_tbai</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_es_edi_tbai</code></div></div>
<div class="model"><div class="name"><code>account.move.reversal</code></div><div class="role">extended by <code>l10n_es_edi_tbai</code></div></div>
<div class="model"><div class="name"><code>account.resequence.wizard</code></div><div class="role">extended by <code>l10n_es_edi_tbai</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>l10n_es_edi_tbai</code></div></div>
<div class="model"><div class="name"><code>l10n_es_edi.certificate</code></div><div class="role">extended by <code>l10n_es_edi_tbai</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>l10n_es_edi_tbai</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>l10n_es_edi_tbai</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_edi` | extends_model_from | `agents/modules/generated/account_edi.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_es_edi_sii` | depends_on, extends_model_from | `agents/modules/generated/l10n_es_edi_sii.yaml` |
| `module.l10n_es_edi_tbai_multi_refund` | required_by | `agents/modules/generated/l10n_es_edi_tbai_multi_refund.yaml` |
| `module.l10n_es_pos_tbai` | required_by | `agents/modules/generated/l10n_es_pos_tbai.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_es_edi_tbai`](../../../agents/modules/generated/l10n_es_edi_tbai.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/EDI
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_es_edi_tbai)
- Direct dependencies: [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_es_edi_tbai_multi_refund`](../l10n_es_edi_tbai_multi_refund/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md)
- Impact graph: [`module:l10n_es_edi_tbai`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.edi.document` — defined by [`account_edi`](../account_edi/overview.md)
- Extends `account.edi.format` — defined by [`account_edi`](../account_edi/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.reversal` — defined by [`account`](../account/overview.md)
- Extends `account.resequence.wizard` — defined by [`account`](../account/overview.md)
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)
- Extends `l10n_es_edi.certificate` — defined by [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_edi`](../../../agents/modules/generated/account_edi.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_es_edi_sii`](../../../agents/modules/generated/l10n_es_edi_sii.yaml) — depends_on, extends_model_from
- [`module.l10n_es_edi_tbai_multi_refund`](../../../agents/modules/generated/l10n_es_edi_tbai_multi_refund.yaml) — required_by
- [`module.l10n_es_pos_tbai`](../../../agents/modules/generated/l10n_es_pos_tbai.yaml) — required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`account_edi`](../account_edi/overview.md), [`base`](../base/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
