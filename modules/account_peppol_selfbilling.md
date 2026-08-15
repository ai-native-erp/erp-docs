---
layout: page
title: "Peppol Self Billing (account_peppol_selfbilling)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_peppol_selfbilling/
nav_order: 0
---
# Peppol Self Billing — `account_peppol_selfbilling`

**Source:** [`agents/modules/generated/account_peppol_selfbilling.yaml`](../../agents/modules/generated/account_peppol_selfbilling.yaml) · **Wiki:** [`knowledge/modules/account_peppol_selfbilling/overview.md`](../../knowledge/modules/account_peppol_selfbilling/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_peppol_selfbilling</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Peppol Self Billing</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_peppol_selfbilling</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_peppol_selfbilling"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Send and receive self-billing invoices on PEPPOL

## Direct dependencies

[`account_peppol`](account_peppol.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.xml.ubl_bis3</code></div><div class="role">extended by <code>account_peppol_selfbilling</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>account_peppol_selfbilling</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>account_peppol_selfbilling</code></div></div>
<div class="model"><div class="name"><code>account.move.send</code></div><div class="role">extended by <code>account_peppol_selfbilling</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_edi_ubl_cii` | extends_model_from | `agents/modules/generated/account_edi_ubl_cii.yaml` |
| `module.account_peppol` | depends_on | `agents/modules/generated/account_peppol.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_peppol_selfbilling`](../../../agents/modules/generated/account_peppol_selfbilling.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_peppol_selfbilling)
- Direct dependencies: [`account_peppol`](../account_peppol/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:account_peppol_selfbilling`](../../impact-graph.json)

## Purpose

Send and receive self-billing invoices on PEPPOL

## Model relationships

- Extends `account.edi.xml.ubl_bis3` — defined by [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md)
- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.send` — defined by [`account`](../account/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — extends_model_from
- [`module.account_peppol`](../../../agents/modules/generated/account_peppol.yaml) — depends_on
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
