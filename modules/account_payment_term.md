---
layout: page
title: "Payment Term - Days end of month on the (account_payment_term)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_payment_term/
nav_order: 0
---
# Payment Term - Days end of month on the — `account_payment_term`

**Source:** [`agents/modules/generated/account_payment_term.yaml`](../../agents/modules/generated/account_payment_term.yaml) · **Wiki:** [`knowledge/modules/account_payment_term/overview.md`](../../knowledge/modules/account_payment_term/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_payment_term</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Payment Term - Days end of month on the</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">OEEL-1</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_payment_term</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_payment_term"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.payment.term.line</code></div><div class="role">extended by <code>account_payment_term</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_payment_term`](../../../agents/modules/generated/account_payment_term.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_payment_term)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `OEEL-1`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:account_payment_term`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.payment.term.line` — defined by [`account`](../account/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
