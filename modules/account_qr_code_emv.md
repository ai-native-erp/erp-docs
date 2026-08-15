---
layout: page
title: "account_qr_code_emv (account_qr_code_emv)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_qr_code_emv/
nav_order: 0
---
# account_qr_code_emv — `account_qr_code_emv`

**Source:** [`agents/modules/generated/account_qr_code_emv.yaml`](../../agents/modules/generated/account_qr_code_emv.yaml) · **Wiki:** [`knowledge/modules/account_qr_code_emv/overview.md`](../../knowledge/modules/account_qr_code_emv/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_qr_code_emv</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">account_qr_code_emv</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_qr_code_emv</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_qr_code_emv"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md)

## Reverse dependencies (modules that depend on this)

[`l10n_br_pix`](l10n_br_pix.md), [`l10n_hk`](l10n_hk.md), [`l10n_sg`](l10n_sg.md), [`l10n_th`](l10n_th.md), [`l10n_vn`](l10n_vn.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.partner.bank</code></div><div class="role">extended by <code>account_qr_code_emv</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_br_pix` | required_by | `agents/modules/generated/l10n_br_pix.yaml` |
| `module.l10n_hk` | required_by | `agents/modules/generated/l10n_hk.yaml` |
| `module.l10n_sg` | required_by | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_th` | required_by | `agents/modules/generated/l10n_th.yaml` |
| `module.l10n_vn` | required_by | `agents/modules/generated/l10n_vn.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_qr_code_emv`](../../../agents/modules/generated/account_qr_code_emv.yaml)
- Domain: `accounting`
- Category: Accounting/Payment
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_qr_code_emv)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_br_pix`](../l10n_br_pix/overview.md), [`l10n_hk`](../l10n_hk/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_vn`](../l10n_vn/overview.md)
- Impact graph: [`module:account_qr_code_emv`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `res.partner.bank` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_br_pix`](../../../agents/modules/generated/l10n_br_pix.yaml) — required_by
- [`module.l10n_hk`](../../../agents/modules/generated/l10n_hk.yaml) — required_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — required_by
- [`module.l10n_th`](../../../agents/modules/generated/l10n_th.yaml) — required_by
- [`module.l10n_vn`](../../../agents/modules/generated/l10n_vn.yaml) — required_by

## Regression impact checklist

- Review 5 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
