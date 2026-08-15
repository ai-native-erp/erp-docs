---
layout: page
title: "Mexico - Accounting (l10n_mx)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_mx/
nav_order: 0
---
# Mexico - Accounting — `l10n_mx`

**Source:** [`agents/modules/generated/l10n_mx.yaml`](../../agents/modules/generated/l10n_mx.yaml) · **Wiki:** [`knowledge/modules/l10n_mx/overview.md`](../../knowledge/modules/l10n_mx/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_mx</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Mexico - Accounting</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_mx</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_mx"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.account</code></div><div class="role">extended by <code>l10n_mx</code></div></div>
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>l10n_mx</code></div></div>
<div class="model"><div class="name"><code>account.tax</code></div><div class="role">extended by <code>l10n_mx</code></div></div>
<div class="model"><div class="name"><code>res.bank</code></div><div class="role">extended by <code>l10n_mx</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>l10n_mx</code></div></div>
<div class="model"><div class="name"><code>res.partner.bank</code></div><div class="role">extended by <code>l10n_mx</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_mx`](../../../agents/modules/generated/l10n_mx.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Account Charts
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_mx)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_mx`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.account` — defined by [`account`](../account/overview.md)
- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.tax` — defined by [`account`](../account/overview.md)
- Extends `res.bank` — defined by [`base`](../base/overview.md), [`l10n_cl`](../l10n_cl/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner.bank` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_cl`](../l10n_cl/overview.md).
- Required specialist reviewers: security_reviewer, qa_upgrade.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
