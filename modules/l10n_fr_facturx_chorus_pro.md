---
layout: page
title: "France - Factur-X integration with Chorus Pro (l10n_fr_facturx_chorus_pro)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_fr_facturx_chorus_pro/
nav_order: 0
---
# France - Factur-X integration with Chorus Pro — `l10n_fr_facturx_chorus_pro`

**Source:** [`agents/modules/generated/l10n_fr_facturx_chorus_pro.yaml`](../../agents/modules/generated/l10n_fr_facturx_chorus_pro.yaml) · **Wiki:** [`knowledge/modules/l10n_fr_facturx_chorus_pro/overview.md`](../../knowledge/modules/l10n_fr_facturx_chorus_pro/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_fr_facturx_chorus_pro</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">France - Factur-X integration with Chorus Pro</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_fr_facturx_chorus_pro</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_fr_facturx_chorus_pro"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md), [`account_edi_ubl_cii`](account_edi_ubl_cii.md), [`l10n_fr`](l10n_fr.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.xml.ubl_bis3</code></div><div class="role">extended by <code>l10n_fr_facturx_chorus_pro</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_fr_facturx_chorus_pro</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_edi_ubl_cii` | depends_on, extends_model_from | `agents/modules/generated/account_edi_ubl_cii.yaml` |
| `module.l10n_fr` | depends_on | `agents/modules/generated/l10n_fr.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_fr_facturx_chorus_pro`](../../../agents/modules/generated/l10n_fr_facturx_chorus_pro.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/EDI
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_fr_facturx_chorus_pro)
- Direct dependencies: [`account`](../account/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`l10n_fr`](../l10n_fr/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_fr_facturx_chorus_pro`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.edi.xml.ubl_bis3` — defined by [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — depends_on, extends_model_from
- [`module.l10n_fr`](../../../agents/modules/generated/l10n_fr.yaml) — depends_on
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
