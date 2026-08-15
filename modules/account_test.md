---
layout: page
title: "Accounting Consistency Tests (account_test)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_test/
nav_order: 0
---
# Accounting Consistency Tests — `account_test`

**Source:** [`agents/modules/generated/account_test.yaml`](../../agents/modules/generated/account_test.yaml) · **Wiki:** [`knowledge/modules/account_test/overview.md`](../../knowledge/modules/account_test/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_test</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Accounting Consistency Tests</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_test</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_test"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>accounting.assert.test</code></div><div class="role">defined by <code>account_test</code></div></div>
<div class="model"><div class="name"><code>report.account_test.report_accounttest</code></div><div class="role">defined by <code>account_test</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on | `agents/modules/generated/account.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_test`](../../../agents/modules/generated/account_test.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_test)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:account_test`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `accounting.assert.test`
- `report.account_test.report_accounttest`

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
