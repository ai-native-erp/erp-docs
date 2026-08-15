---
layout: page
title: "Debit Note Sequence (account_debit_note_sequence)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_debit_note_sequence/
nav_order: 0
---
# Debit Note Sequence — `account_debit_note_sequence`

**Source:** [`agents/modules/generated/account_debit_note_sequence.yaml`](../../agents/modules/generated/account_debit_note_sequence.yaml) · **Wiki:** [`knowledge/modules/account_debit_note_sequence/overview.md`](../../knowledge/modules/account_debit_note_sequence/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_debit_note_sequence</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Debit Note Sequence</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_debit_note_sequence</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_debit_note_sequence"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Debit Note Sequence

## Direct dependencies

[`account_debit_note`](account_debit_note.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>account_debit_note_sequence</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>account_debit_note_sequence</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_debit_note` | depends_on | `agents/modules/generated/account_debit_note.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_debit_note_sequence`](../../../agents/modules/generated/account_debit_note_sequence.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_debit_note_sequence)
- Direct dependencies: [`account_debit_note`](../account_debit_note/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:account_debit_note_sequence`](../../impact-graph.json)

## Purpose

Debit Note Sequence

## Model relationships

- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_debit_note`](../../../agents/modules/generated/account_debit_note.yaml) — depends_on
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
