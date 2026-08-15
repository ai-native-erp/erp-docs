---
layout: page
title: "Gulf Cooperation Council WMS Accounting (l10n_gcc_invoice_stock_account)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_gcc_invoice_stock_account/
nav_order: 0
---
# Gulf Cooperation Council WMS Accounting — `l10n_gcc_invoice_stock_account`

**Source:** [`agents/modules/generated/l10n_gcc_invoice_stock_account.yaml`](../../agents/modules/generated/l10n_gcc_invoice_stock_account.yaml) · **Wiki:** [`knowledge/modules/l10n_gcc_invoice_stock_account/overview.md`](../../knowledge/modules/l10n_gcc_invoice_stock_account/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_gcc_invoice_stock_account</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Gulf Cooperation Council WMS Accounting</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_gcc_invoice_stock_account</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_gcc_invoice_stock_account"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_gcc_invoice`](l10n_gcc_invoice.md), [`stock_account`](stock_account.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_gcc_invoice` | depends_on | `agents/modules/generated/l10n_gcc_invoice.yaml` |
| `module.stock_account` | depends_on | `agents/modules/generated/stock_account.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_gcc_invoice_stock_account`](../../../agents/modules/generated/l10n_gcc_invoice_stock_account.yaml)
- Domain: `localization`
- Category: Accounting/Localizations
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_gcc_invoice_stock_account)
- Direct dependencies: [`l10n_gcc_invoice`](../l10n_gcc_invoice/overview.md), [`stock_account`](../stock_account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_gcc_invoice_stock_account`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.l10n_gcc_invoice`](../../../agents/modules/generated/l10n_gcc_invoice.yaml) — depends_on
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
