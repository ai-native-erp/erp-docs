---
layout: page
title: "Testing the Import/Export invoices with UBL/CII (l10n_account_edi_ubl_cii_tests)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_account_edi_ubl_cii_tests/
nav_order: 0
---
# Testing the Import/Export invoices with UBL/CII — `l10n_account_edi_ubl_cii_tests`

**Source:** [`agents/modules/generated/l10n_account_edi_ubl_cii_tests.yaml`](../../agents/modules/generated/l10n_account_edi_ubl_cii_tests.yaml) · **Wiki:** [`knowledge/modules/l10n_account_edi_ubl_cii_tests/overview.md`](../../knowledge/modules/l10n_account_edi_ubl_cii_tests/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_account_edi_ubl_cii_tests</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Testing the Import/Export invoices with UBL/CII</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_account_edi_ubl_cii_tests</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_account_edi_ubl_cii_tests"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account_edi_ubl_cii`](account_edi_ubl_cii.md), [`l10n_au`](l10n_au.md), [`l10n_be`](l10n_be.md), [`l10n_de`](l10n_de.md), [`l10n_fr`](l10n_fr.md), [`l10n_nl`](l10n_nl.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account_edi_ubl_cii` | depends_on | `agents/modules/generated/account_edi_ubl_cii.yaml` |
| `module.l10n_au` | depends_on | `agents/modules/generated/l10n_au.yaml` |
| `module.l10n_be` | depends_on | `agents/modules/generated/l10n_be.yaml` |
| `module.l10n_de` | depends_on | `agents/modules/generated/l10n_de.yaml` |
| `module.l10n_fr` | depends_on | `agents/modules/generated/l10n_fr.yaml` |
| `module.l10n_nl` | depends_on | `agents/modules/generated/l10n_nl.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_account_edi_ubl_cii_tests`](../../../agents/modules/generated/l10n_account_edi_ubl_cii_tests.yaml)
- Domain: `localization`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_account_edi_ubl_cii_tests)
- Direct dependencies: [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`l10n_au`](../l10n_au/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_nl`](../l10n_nl/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_account_edi_ubl_cii_tests`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — depends_on
- [`module.l10n_au`](../../../agents/modules/generated/l10n_au.yaml) — depends_on
- [`module.l10n_be`](../../../agents/modules/generated/l10n_be.yaml) — depends_on
- [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml) — depends_on
- [`module.l10n_fr`](../../../agents/modules/generated/l10n_fr.yaml) — depends_on
- [`module.l10n_nl`](../../../agents/modules/generated/l10n_nl.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
