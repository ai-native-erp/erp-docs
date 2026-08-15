---
layout: page
title: "Austria - Accounting (l10n_at)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_at/
nav_order: 0
---
# Austria - Accounting — `l10n_at`

**Source:** [`agents/modules/generated/l10n_at.yaml`](../../agents/modules/generated/l10n_at.yaml) · **Wiki:** [`knowledge/modules/l10n_at/overview.md`](../../knowledge/modules/l10n_at/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_at</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Austria - Accounting</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_at</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_at"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Austrian Standardized Charts & Tax

## Direct dependencies

[`account`](account.md), [`base_iban`](base_iban.md), [`base_vat`](base_vat.md), [`l10n_din5008`](l10n_din5008.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>l10n_at</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>l10n_at</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base_iban` | depends_on | `agents/modules/generated/base_iban.yaml` |
| `module.base_vat` | depends_on | `agents/modules/generated/base_vat.yaml` |
| `module.l10n_din5008` | depends_on | `agents/modules/generated/l10n_din5008.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_at`](../../../agents/modules/generated/l10n_at.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Account Charts
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_at)
- Direct dependencies: [`account`](../account/overview.md), [`base_iban`](../base_iban/overview.md), [`base_vat`](../base_vat/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_at`](../../impact-graph.json)

## Purpose

Austrian Standardized Charts & Tax

## Model relationships

- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.journal` — defined by [`account`](../account/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.base_iban`](../../../agents/modules/generated/base_iban.yaml) — depends_on
- [`module.base_vat`](../../../agents/modules/generated/base_vat.yaml) — depends_on
- [`module.l10n_din5008`](../../../agents/modules/generated/l10n_din5008.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md).
- Required specialist reviewers: qa_upgrade.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
