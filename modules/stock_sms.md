---
layout: page
title: "Stock - SMS (stock_sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/stock_sms/
nav_order: 0
---
# Stock - SMS — `stock_sms`

**Source:** [`agents/modules/generated/stock_sms.yaml`](../../agents/modules/generated/stock_sms.yaml) · **Wiki:** [`knowledge/modules/stock_sms/overview.md`](../../knowledge/modules/stock_sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>stock_sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Stock - SMS</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/stock_sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock_sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Send text messages when final stock move

## Direct dependencies

[`sms`](sms.md), [`stock`](stock.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>confirm.stock.sms</code></div><div class="role">defined by <code>stock_sms</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>stock_sms</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>stock_sms</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>stock_sms</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |
| `module.sms` | depends_on | `agents/modules/generated/sms.yaml` |
| `module.stock` | depends_on, extends_model_from | `agents/modules/generated/stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.stock_sms`](../../../agents/modules/generated/stock_sms.yaml)
- Domain: `inventory_purchase`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock_sms)
- Direct dependencies: [`sms`](../sms/overview.md), [`stock`](../stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:stock_sms`](../../impact-graph.json)

## Purpose

Send text messages when final stock move

## Model relationships

- `confirm.stock.sms`
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
