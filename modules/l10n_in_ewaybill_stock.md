---
layout: page
title: "Indian - E-waybill Stock (l10n_in_ewaybill_stock)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_in_ewaybill_stock/
nav_order: 0
---
# Indian - E-waybill Stock — `l10n_in_ewaybill_stock`

**Source:** [`agents/modules/generated/l10n_in_ewaybill_stock.yaml`](../../agents/modules/generated/l10n_in_ewaybill_stock.yaml) · **Wiki:** [`knowledge/modules/l10n_in_ewaybill_stock/overview.md`](../../knowledge/modules/l10n_in_ewaybill_stock/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_in_ewaybill_stock</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Indian - E-waybill Stock</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_in_ewaybill_stock</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_in_ewaybill_stock"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_in_edi_ewaybill`](l10n_in_edi_ewaybill.md), [`l10n_in_stock`](l10n_in_stock.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>l10n.in.ewaybill</code></div><div class="role">defined by <code>l10n_in_ewaybill_stock</code></div></div>
<div class="model"><div class="name"><code>l10n.in.ewaybill.cancel</code></div><div class="role">defined by <code>l10n_in_ewaybill_stock</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>l10n_in_ewaybill_stock</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>l10n_in_ewaybill_stock</code></div></div>
<div class="model"><div class="name"><code>portal.mixin</code></div><div class="role">extended by <code>l10n_in_ewaybill_stock</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>l10n_in_ewaybill_stock</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>l10n_in_ewaybill_stock</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_in_edi_ewaybill` | depends_on | `agents/modules/generated/l10n_in_edi_ewaybill.yaml` |
| `module.l10n_in_stock` | depends_on | `agents/modules/generated/l10n_in_stock.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.portal` | extends_model_from | `agents/modules/generated/portal.yaml` |
| `module.stock` | extends_model_from | `agents/modules/generated/stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_in_ewaybill_stock`](../../../agents/modules/generated/l10n_in_ewaybill_stock.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/EDI
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_in_ewaybill_stock)
- Direct dependencies: [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_stock`](../l10n_in_stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_in_ewaybill_stock`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `l10n.in.ewaybill`
- `l10n.in.ewaybill.cancel`
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `portal.mixin` — defined by [`portal`](../portal/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)

## Related SME agents

- [`module.l10n_in_edi_ewaybill`](../../../agents/modules/generated/l10n_in_edi_ewaybill.yaml) — depends_on
- [`module.l10n_in_stock`](../../../agents/modules/generated/l10n_in_stock.yaml) — depends_on
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mail`](../mail/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`portal`](../portal/overview.md), [`stock`](../stock/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
