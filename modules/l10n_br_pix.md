---
layout: page
title: "Brazil Pix QR codes (l10n_br_pix)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_br_pix/
nav_order: 0
---
# Brazil Pix QR codes — `l10n_br_pix`

**Source:** [`agents/modules/generated/l10n_br_pix.yaml`](../../agents/modules/generated/l10n_br_pix.yaml) · **Wiki:** [`knowledge/modules/l10n_br_pix/overview.md`](../../knowledge/modules/l10n_br_pix/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_br_pix</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Brazil Pix QR codes</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_br_pix</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_br_pix"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account_qr_code_emv`](account_qr_code_emv.md), [`l10n_br`](l10n_br.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.partner.bank</code></div><div class="role">extended by <code>l10n_br_pix</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_qr_code_emv` | depends_on | `agents/modules/generated/account_qr_code_emv.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_br` | depends_on | `agents/modules/generated/l10n_br.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_br_pix`](../../../agents/modules/generated/l10n_br_pix.yaml)
- Domain: `localization`
- Category: Accounting/Localizations
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_br_pix)
- Direct dependencies: [`account_qr_code_emv`](../account_qr_code_emv/overview.md), [`l10n_br`](../l10n_br/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_br_pix`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `res.partner.bank` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_qr_code_emv`](../../../agents/modules/generated/account_qr_code_emv.yaml) — depends_on
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_br`](../../../agents/modules/generated/l10n_br.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
