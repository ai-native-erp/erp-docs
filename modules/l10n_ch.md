---
layout: page
title: "Switzerland - Accounting (l10n_ch)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_ch/
nav_order: 0
---
# Switzerland - Accounting — `l10n_ch`

**Source:** [`agents/modules/generated/l10n_ch.yaml`](../../agents/modules/generated/l10n_ch.yaml) · **Wiki:** [`knowledge/modules/l10n_ch/overview.md`](../../knowledge/modules/l10n_ch/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_ch</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Switzerland - Accounting</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_ch</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ch"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md), [`base_iban`](base_iban.md), [`l10n_din5008`](l10n_din5008.md)

## Reverse dependencies (modules that depend on this)

[`l10n_ch_pos`](l10n_ch_pos.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>l10n_ch.qr_invoice.wizard</code></div><div class="role">defined by <code>l10n_ch</code></div></div>
<div class="model"><div class="name"><code>report.l10n_ch.qr_report_main</code></div><div class="role">defined by <code>l10n_ch</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.chart.template</code></div><div class="role">extended by <code>l10n_ch</code></div></div>
<div class="model"><div class="name"><code>account.journal</code></div><div class="role">extended by <code>l10n_ch</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_ch</code></div></div>
<div class="model"><div class="name"><code>account.payment</code></div><div class="role">extended by <code>l10n_ch</code></div></div>
<div class="model"><div class="name"><code>account.setup.bank.manual.config</code></div><div class="role">extended by <code>l10n_ch</code></div></div>
<div class="model"><div class="name"><code>ir.actions.report</code></div><div class="role">extended by <code>l10n_ch</code></div></div>
<div class="model"><div class="name"><code>res.partner.bank</code></div><div class="role">extended by <code>l10n_ch</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_iban` | depends_on | `agents/modules/generated/base_iban.yaml` |
| `module.l10n_ch_pos` | required_by | `agents/modules/generated/l10n_ch_pos.yaml` |
| `module.l10n_din5008` | depends_on | `agents/modules/generated/l10n_din5008.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_ch`](../../../agents/modules/generated/l10n_ch.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Account Charts
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ch)
- Direct dependencies: [`account`](../account/overview.md), [`base_iban`](../base_iban/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_ch_pos`](../l10n_ch_pos/overview.md)
- Impact graph: [`module:l10n_ch`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `l10n_ch.qr_invoice.wizard`
- `report.l10n_ch.qr_report_main`
- Extends `account.chart.template` — framework/dynamic owner
- Extends `account.journal` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.payment` — defined by [`account`](../account/overview.md)
- Extends `account.setup.bank.manual.config` — defined by [`account`](../account/overview.md)
- Extends `ir.actions.report` — defined by [`base`](../base/overview.md)
- Extends `res.partner.bank` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_iban`](../../../agents/modules/generated/base_iban.yaml) — depends_on
- [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml) — required_by
- [`module.l10n_din5008`](../../../agents/modules/generated/l10n_din5008.yaml) — depends_on
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl, qa_upgrade.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
