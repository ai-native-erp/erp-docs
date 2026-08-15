---
layout: page
title: "Account SEPA QR Code (account_qr_code_sepa)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_qr_code_sepa/
nav_order: 0
---
# Account SEPA QR Code — `account_qr_code_sepa`

**Source:** [`agents/modules/generated/account_qr_code_sepa.yaml`](../../agents/modules/generated/account_qr_code_sepa.yaml) · **Wiki:** [`knowledge/modules/account_qr_code_sepa/overview.md`](../../knowledge/modules/account_qr_code_sepa/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_qr_code_sepa</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Account SEPA QR Code</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_qr_code_sepa</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_qr_code_sepa"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md), [`base_iban`](base_iban.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.partner.bank</code></div><div class="role">extended by <code>account_qr_code_sepa</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_iban` | depends_on | `agents/modules/generated/base_iban.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_qr_code_sepa`](../../../agents/modules/generated/account_qr_code_sepa.yaml)
- Domain: `accounting`
- Category: Accounting/Payment
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_qr_code_sepa)
- Direct dependencies: [`account`](../account/overview.md), [`base_iban`](../base_iban/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:account_qr_code_sepa`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `res.partner.bank` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_iban`](../../../agents/modules/generated/base_iban.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
