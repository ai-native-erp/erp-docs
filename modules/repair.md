---
layout: page
title: "Repairs (repair)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/repair/
nav_order: 0
---
# Repairs — `repair`

**Source:** [`agents/modules/generated/repair.yaml`](../../agents/modules/generated/repair.yaml) · **Wiki:** [`knowledge/modules/repair/overview.md`](../../knowledge/modules/repair/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>repair</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Repairs</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">manufacturing</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/repair</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/repair"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Repair damaged products

## Direct dependencies

[`sale_management`](sale_management.md), [`sale_stock`](sale_stock.md)

## Reverse dependencies (modules that depend on this)

[`l10n_din5008_repair`](l10n_din5008_repair.md), [`mrp_repair`](mrp_repair.md), [`mrp_subcontracting_repair`](mrp_subcontracting_repair.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>repair.order</code></div><div class="role">defined by <code>repair</code></div></div>
<div class="model"><div class="name"><code>repair.tags</code></div><div class="role">defined by <code>repair</code></div></div>
<div class="model"><div class="name"><code>repair.warn.uncomplete.move</code></div><div class="role">defined by <code>repair</code></div></div>
<div class="model"><div class="name"><code>stock.warn.insufficient.qty.repair</code></div><div class="role">defined by <code>repair</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>mail.compose.message</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>stock.forecasted_product_product</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>stock.lot</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>stock.move.line</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>stock.picking.type</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>stock.traceability.report</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>stock.warehouse</code></div><div class="role">extended by <code>repair</code></div></div>
<div class="model"><div class="name"><code>stock.warn.insufficient.qty</code></div><div class="role">extended by <code>repair</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_din5008_repair` | model_extended_by, required_by | `agents/modules/generated/l10n_din5008_repair.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.mrp_repair` | model_extended_by, required_by | `agents/modules/generated/mrp_repair.yaml` |
| `module.mrp_subcontracting` | extends_model_from | `agents/modules/generated/mrp_subcontracting.yaml` |
| `module.mrp_subcontracting_repair` | required_by | `agents/modules/generated/mrp_subcontracting_repair.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.repair`](../../../agents/modules/generated/repair.yaml)
- Domain: `manufacturing`
- Category: Inventory/Inventory
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/repair)
- Direct dependencies: [`sale_management`](../sale_management/overview.md), [`sale_stock`](../sale_stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_din5008_repair`](../l10n_din5008_repair/overview.md), [`mrp_repair`](../mrp_repair/overview.md), [`mrp_subcontracting_repair`](../mrp_subcontracting_repair/overview.md)
- Impact graph: [`module:repair`](../../impact-graph.json)

## Purpose

Repair damaged products

## Model relationships

- `repair.order` — extended by [`l10n_din5008_repair`](../l10n_din5008_repair/overview.md), [`mrp_repair`](../mrp_repair/overview.md)
- `repair.tags`
- `repair.warn.uncomplete.move`
- `stock.warn.insufficient.qty.repair`
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.compose.message` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)
- Extends `stock.forecasted_product_product` — defined by [`stock`](../stock/overview.md)
- Extends `stock.lot` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move.line` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)
- Extends `stock.picking.type` — defined by [`stock`](../stock/overview.md)
- Extends `stock.traceability.report` — defined by [`stock`](../stock/overview.md)
- Extends `stock.warehouse` — defined by [`stock`](../stock/overview.md)
- Extends `stock.warn.insufficient.qty` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.l10n_din5008_repair`](../../../agents/modules/generated/l10n_din5008_repair.yaml) — model_extended_by, required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.mrp_repair`](../../../agents/modules/generated/mrp_repair.yaml) — model_extended_by, required_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.mrp_subcontracting_repair`](../../../agents/modules/generated/mrp_subcontracting_repair.yaml) — required_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — depends_on
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — depends_on
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`l10n_din5008_repair`](../l10n_din5008_repair/overview.md), [`mrp_repair`](../mrp_repair/overview.md).
- Review model owners used by this module: [`mail`](../mail/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
