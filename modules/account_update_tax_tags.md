---
layout: page
title: "Account - Allow updating tax grids (account_update_tax_tags)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_update_tax_tags/
nav_order: 0
---
# Account - Allow updating tax grids — `account_update_tax_tags`

**Source:** [`agents/modules/generated/account_update_tax_tags.yaml`](../../agents/modules/generated/account_update_tax_tags.yaml) · **Wiki:** [`knowledge/modules/account_update_tax_tags/overview.md`](../../knowledge/modules/account_update_tax_tags/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_update_tax_tags</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Account - Allow updating tax grids</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_update_tax_tags</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_update_tax_tags"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Allow updating tax grids on existing entries

## Direct dependencies

[`account`](account.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.update.tax.tags.wizard</code></div><div class="role">defined by <code>account_update_tax_tags</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on | `agents/modules/generated/account.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_update_tax_tags`](../../../agents/modules/generated/account_update_tax_tags.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_update_tax_tags)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:account_update_tax_tags`](../../impact-graph.json)

## Purpose

Allow updating tax grids on existing entries

## Model relationships

- `account.update.tax.tags.wizard`

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
