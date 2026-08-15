---
layout: page
title: "Tax extension for UBL/CII (account_edi_ubl_cii_tax_extension)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_edi_ubl_cii_tax_extension/
nav_order: 0
---
# Tax extension for UBL/CII — `account_edi_ubl_cii_tax_extension`

**Source:** [`agents/modules/generated/account_edi_ubl_cii_tax_extension.yaml`](../../agents/modules/generated/account_edi_ubl_cii_tax_extension.yaml) · **Wiki:** [`knowledge/modules/account_edi_ubl_cii_tax_extension/overview.md`](../../knowledge/modules/account_edi_ubl_cii_tax_extension/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_edi_ubl_cii_tax_extension</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Tax extension for UBL/CII</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_edi_ubl_cii_tax_extension</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_edi_ubl_cii_tax_extension"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Tax extension for UBL/CII

## Direct dependencies

[`account_edi_ubl_cii`](account_edi_ubl_cii.md)

## Reverse dependencies (modules that depend on this)

[`l10n_anz_ubl_pint`](l10n_anz_ubl_pint.md), [`l10n_fr_pdp`](l10n_fr_pdp.md), [`l10n_sg_ubl_pint`](l10n_sg_ubl_pint.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.common</code></div><div class="role">extended by <code>account_edi_ubl_cii_tax_extension</code></div></div>
<div class="model"><div class="name"><code>account.tax</code></div><div class="role">extended by <code>account_edi_ubl_cii_tax_extension</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_edi_ubl_cii` | depends_on, extends_model_from | `agents/modules/generated/account_edi_ubl_cii.yaml` |
| `module.l10n_anz_ubl_pint` | required_by | `agents/modules/generated/l10n_anz_ubl_pint.yaml` |
| `module.l10n_fr_pdp` | required_by | `agents/modules/generated/l10n_fr_pdp.yaml` |
| `module.l10n_sg_ubl_pint` | required_by | `agents/modules/generated/l10n_sg_ubl_pint.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_edi_ubl_cii_tax_extension`](../../../agents/modules/generated/account_edi_ubl_cii_tax_extension.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_edi_ubl_cii_tax_extension)
- Direct dependencies: [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md)
- Impact graph: [`module:account_edi_ubl_cii_tax_extension`](../../impact-graph.json)

## Purpose

Tax extension for UBL/CII

## Model relationships

- Extends `account.edi.common` — defined by [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md)
- Extends `account.tax` — defined by [`account`](../account/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — depends_on, extends_model_from
- [`module.l10n_anz_ubl_pint`](../../../agents/modules/generated/l10n_anz_ubl_pint.yaml) — required_by
- [`module.l10n_fr_pdp`](../../../agents/modules/generated/l10n_fr_pdp.yaml) — required_by
- [`module.l10n_sg_ubl_pint`](../../../agents/modules/generated/l10n_sg_ubl_pint.yaml) — required_by

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
