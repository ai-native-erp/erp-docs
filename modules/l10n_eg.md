---
layout: page
title: "Egypt - Accounting (l10n_eg)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_eg/
nav_order: 0
---
# Egypt - Accounting — `l10n_eg`

**Source:** [`agents/modules/generated/l10n_eg.yaml`](../../agents/modules/generated/l10n_eg.yaml) · **Wiki:** [`knowledge/modules/l10n_eg/overview.md`](../../knowledge/modules/l10n_eg/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_eg</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Egypt - Accounting</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_eg</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_eg"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md)

## Reverse dependencies (modules that depend on this)

[`l10n_eg_edi_eta`](l10n_eg_edi_eta.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>l10n_eg</code></div></div>
<div class="model"><div class="name"><code>account.tax</code></div><div class="role">extended by <code>l10n_eg</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.l10n_eg_edi_eta` | required_by | `agents/modules/generated/l10n_eg_edi_eta.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_eg`](../../../agents/modules/generated/l10n_eg.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Account Charts
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_eg)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md)
- Impact graph: [`module:l10n_eg`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.tax` — defined by [`account`](../account/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.l10n_eg_edi_eta`](../../../agents/modules/generated/l10n_eg_edi_eta.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
