---
layout: page
title: "IBAN Bank Accounts (base_iban)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/base_iban/
nav_order: 0
---
# IBAN Bank Accounts — `base_iban`

**Source:** [`agents/modules/generated/base_iban.yaml`](../../agents/modules/generated/base_iban.yaml) · **Wiki:** [`knowledge/modules/base_iban/overview.md`](../../knowledge/modules/base_iban/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base_iban</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">IBAN Bank Accounts</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/base_iban</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base_iban"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md), [`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`account_qr_code_sepa`](account_qr_code_sepa.md), [`l10n_at`](l10n_at.md), [`l10n_be`](l10n_be.md), [`l10n_ca`](l10n_ca.md), [`l10n_ch`](l10n_ch.md), [`l10n_cz`](l10n_cz.md), [`l10n_de`](l10n_de.md), [`l10n_dk`](l10n_dk.md), [`l10n_do`](l10n_do.md), [`l10n_ec`](l10n_ec.md), [`l10n_es`](l10n_es.md), [`l10n_fi`](l10n_fi.md), [`l10n_fr`](l10n_fr.md), [`l10n_gr`](l10n_gr.md), [`l10n_hu_edi`](l10n_hu_edi.md), [`l10n_id`](l10n_id.md), [`l10n_ie`](l10n_ie.md), [`l10n_it`](l10n_it.md), [`l10n_lu`](l10n_lu.md), [`l10n_nl`](l10n_nl.md), [`l10n_no`](l10n_no.md), [`l10n_pl`](l10n_pl.md), [`l10n_sk`](l10n_sk.md), [`l10n_uk`](l10n_uk.md), [`l10n_vn`](l10n_vn.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.partner.bank</code></div><div class="role">extended by <code>base_iban</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_qr_code_sepa` | required_by | `agents/modules/generated/account_qr_code_sepa.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_at` | required_by | `agents/modules/generated/l10n_at.yaml` |
| `module.l10n_be` | required_by | `agents/modules/generated/l10n_be.yaml` |
| `module.l10n_ca` | required_by | `agents/modules/generated/l10n_ca.yaml` |
| `module.l10n_ch` | required_by | `agents/modules/generated/l10n_ch.yaml` |
| `module.l10n_cz` | required_by | `agents/modules/generated/l10n_cz.yaml` |
| `module.l10n_de` | required_by | `agents/modules/generated/l10n_de.yaml` |
| `module.l10n_dk` | required_by | `agents/modules/generated/l10n_dk.yaml` |

## Full wiki excerpt

- SME owner: [`module.base_iban`](../../../agents/modules/generated/base_iban.yaml)
- Domain: `platform_core`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base_iban)
- Direct dependencies: [`account`](../account/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`account_qr_code_sepa`](../account_qr_code_sepa/overview.md), [`l10n_at`](../l10n_at/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_do`](../l10n_do/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_fi`](../l10n_fi/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_gr`](../l10n_gr/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id`](../l10n_id/overview.md), [`l10n_ie`](../l10n_ie/overview.md), [`l10n_it`](../l10n_it/overview.md), [`l10n_lu`](../l10n_lu/overview.md), [`l10n_nl`](../l10n_nl/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_uk`](../l10n_uk/overview.md), [`l10n_vn`](../l10n_vn/overview.md)
- Impact graph: [`module:base_iban`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `res.partner.bank` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.account_qr_code_sepa`](../../../agents/modules/generated/account_qr_code_sepa.yaml) — required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_at`](../../../agents/modules/generated/l10n_at.yaml) — required_by
- [`module.l10n_be`](../../../agents/modules/generated/l10n_be.yaml) — required_by
- [`module.l10n_ca`](../../../agents/modules/generated/l10n_ca.yaml) — required_by
- [`module.l10n_ch`](../../../agents/modules/generated/l10n_ch.yaml) — required_by
- [`module.l10n_cz`](../../../agents/modules/generated/l10n_cz.yaml) — required_by
- [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml) — required_by
- [`module.l10n_dk`](../../../agents/modules/generated/l10n_dk.yaml) — required_by
- [`module.l10n_do`](../../../agents/modules/generated/l10n_do.yaml) — required_by
- [`module.l10n_ec`](../../../agents/modules/generated/l10n_ec.yaml) — required_by
- [`module.l10n_es`](../../../agents/modules/generated/l10n_es.yaml) — required_by
- [`module.l10n_fi`](../../../agents/modules/generated/l10n_fi.yaml) — required_by
- [`module.l10n_fr`](../../../agents/modules/generated/l10n_fr.yaml) — required_by
- [`module.l10n_gr`](../../../agents/modules/generated/l10n_gr.yaml) — required_by
- [`module.l10n_hu_edi`](../../../agents/modules/generated/l10n_hu_edi.yaml) — required_by
- [`module.l10n_id`](../../../agents/modules/generated/l10n_id.yaml) — required_by
- [`module.l10n_ie`](../../../agents/modules/generated/l10n_ie.yaml) — required_by
- [`module.l10n_it`](../../../agents/modules/generated/l10n_it.yaml) — required_by
- [`module.l10n_lu`](../../../agents/modules/generated/l10n_lu.yaml) — required_by
- [`module.l10n_nl`](../../../agents/modules/generated/l10n_nl.yaml) — required_by
- [`module.l10n_no`](../../../agents/modules/generated/l10n_no.yaml) — required_by
- [`module.l10n_pl`](../../../agents/modules/generated/l10n_pl.yaml) — required_by
- [`module.l10n_sk`](../../../agents/modules/generated/l10n_sk.yaml) — required_by
- [`module.l10n_uk`](../../../agents/modules/generated/l10n_uk.yaml) — required_by
- [`module.l10n_vn`](../../../agents/modules/generated/l10n_vn.yaml) — required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 25 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
