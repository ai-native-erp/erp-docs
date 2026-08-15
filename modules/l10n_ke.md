---
layout: page
title: "Kenya - Accounting (l10n_ke)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_ke/
nav_order: 0
---
# Kenya - Accounting — `l10n_ke`

**Source:** [`agents/modules/generated/l10n_ke.yaml`](../../agents/modules/generated/l10n_ke.yaml) · **Wiki:** [`knowledge/modules/l10n_ke/overview.md`](../../knowledge/modules/l10n_ke/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_ke</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Kenya - Accounting</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_ke</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ke"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md)

## Reverse dependencies (modules that depend on this)

[`l10n_ke_edi_tremol`](l10n_ke_edi_tremol.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>l10n_ke.item.code</code></div><div class="role">defined by <code>l10n_ke</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>l10n_ke</code></div></div>
<div class="model"><div class="name"><code>account.tax</code></div><div class="role">extended by <code>l10n_ke</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>l10n_ke</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_ke_edi_tremol` | required_by | `agents/modules/generated/l10n_ke_edi_tremol.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_ke`](../../../agents/modules/generated/l10n_ke.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Account Charts
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ke)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md)
- Impact graph: [`module:l10n_ke`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `l10n_ke.item.code`
- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.tax` — defined by [`account`](../account/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_ke_edi_tremol`](../../../agents/modules/generated/l10n_ke_edi_tremol.yaml) — required_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
