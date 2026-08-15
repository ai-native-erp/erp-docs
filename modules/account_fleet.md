---
layout: page
title: "Accounting/Fleet bridge (account_fleet)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_fleet/
nav_order: 0
---
# Accounting/Fleet bridge — `account_fleet`

**Source:** [`agents/modules/generated/account_fleet.yaml`](../../agents/modules/generated/account_fleet.yaml) · **Wiki:** [`knowledge/modules/account_fleet/overview.md`](../../knowledge/modules/account_fleet/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_fleet</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Accounting/Fleet bridge</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_fleet</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_fleet"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage accounting with fleets

## Direct dependencies

[`account`](account.md), [`fleet`](fleet.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.automatic.entry.wizard</code></div><div class="role">extended by <code>account_fleet</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>account_fleet</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>account_fleet</code></div></div>
<div class="model"><div class="name"><code>fleet.vehicle</code></div><div class="role">extended by <code>account_fleet</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.fleet` | depends_on, extends_model_from | `agents/modules/generated/fleet.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_fleet`](../../../agents/modules/generated/account_fleet.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_fleet)
- Direct dependencies: [`account`](../account/overview.md), [`fleet`](../fleet/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:account_fleet`](../../impact-graph.json)

## Purpose

Manage accounting with fleets

## Model relationships

- Extends `account.automatic.entry.wizard` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `fleet.vehicle` — defined by [`fleet`](../fleet/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.fleet`](../../../agents/modules/generated/fleet.yaml) — depends_on, extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`fleet`](../fleet/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
