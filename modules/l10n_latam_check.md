---
layout: page
title: "Third Party and Deferred/Electronic Checks Management (l10n_latam_check)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_latam_check/
nav_order: 0
---
# Third Party and Deferred/Electronic Checks Management — `l10n_latam_check`

**Source:** [`agents/modules/generated/l10n_latam_check.yaml`](../../agents/modules/generated/l10n_latam_check.yaml) · **Wiki:** [`knowledge/modules/l10n_latam_check/overview.md`](../../knowledge/modules/l10n_latam_check/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_latam_check</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Third Party and Deferred/Electronic Checks Management</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_latam_check</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_latam_check"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Checks Management

## Direct dependencies

[`account_check_printing`](account_check_printing.md), [`base_vat`](base_vat.md)

## Reverse dependencies (modules that depend on this)

[`l10n_ar_withholding`](l10n_ar_withholding.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>l10n_latam.payment.mass.transfer</code></div><div class="role">defined by <code>l10n_latam_check</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>l10n_latam_check</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>l10n_latam_check</code></div></div>
<div class="model"><div class="name"><code>account.payment</code></div><div class="role">extended by <code>l10n_latam_check</code></div></div>
<div class="model"><div class="name"><code>account.payment.method</code></div><div class="role">extended by <code>l10n_latam_check</code></div></div>
<div class="model"><div class="name"><code>account.payment.register</code></div><div class="role">extended by <code>l10n_latam_check</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_check_printing` | depends_on | `agents/modules/generated/account_check_printing.yaml` |
| `module.base_vat` | depends_on | `agents/modules/generated/base_vat.yaml` |
| `module.l10n_ar_withholding` | required_by | `agents/modules/generated/l10n_ar_withholding.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_latam_check`](../../../agents/modules/generated/l10n_latam_check.yaml)
- Domain: `localization`
- Category: Accounting/Localizations
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_latam_check)
- Direct dependencies: [`account_check_printing`](../account_check_printing/overview.md), [`base_vat`](../base_vat/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md)
- Impact graph: [`module:l10n_latam_check`](../../impact-graph.json)

## Purpose

Checks Management

## Model relationships

- `l10n_latam.payment.mass.transfer`
- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.payment` — defined by [`account`](../account/overview.md)
- Extends `account.payment.method` — defined by [`account`](../account/overview.md)
- Extends `account.payment.register` — defined by [`account`](../account/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_check_printing`](../../../agents/modules/generated/account_check_printing.yaml) — depends_on
- [`module.base_vat`](../../../agents/modules/generated/base_vat.yaml) — depends_on
- [`module.l10n_ar_withholding`](../../../agents/modules/generated/l10n_ar_withholding.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
