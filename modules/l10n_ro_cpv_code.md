---
layout: page
title: "Romania - CPV Code (l10n_ro_cpv_code)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_ro_cpv_code/
nav_order: 0
---
# Romania - CPV Code — `l10n_ro_cpv_code`

**Source:** [`agents/modules/generated/l10n_ro_cpv_code.yaml`](../../agents/modules/generated/l10n_ro_cpv_code.yaml) · **Wiki:** [`knowledge/modules/l10n_ro_cpv_code/overview.md`](../../knowledge/modules/l10n_ro_cpv_code/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_ro_cpv_code</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Romania - CPV Code</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_ro_cpv_code</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ro_cpv_code"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_ro_efactura`](l10n_ro_efactura.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>l10n_ro.cpv.code</code></div><div class="role">defined by <code>l10n_ro_cpv_code</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.xml.ubl_ro</code></div><div class="role">extended by <code>l10n_ro_cpv_code</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>l10n_ro_cpv_code</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_ro_edi` | extends_model_from | `agents/modules/generated/l10n_ro_edi.yaml` |
| `module.l10n_ro_efactura` | depends_on | `agents/modules/generated/l10n_ro_efactura.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product` | extends_model_from | `agents/modules/generated/product.yaml` |
| `module.purchase` | extends_model_from | `agents/modules/generated/purchase.yaml` |
| `module.purchase_stock` | extends_model_from | `agents/modules/generated/purchase_stock.yaml` |
| `module.stock_account` | extends_model_from | `agents/modules/generated/stock_account.yaml` |
| `module.website_sale` | extends_model_from | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_ro_cpv_code`](../../../agents/modules/generated/l10n_ro_cpv_code.yaml)
- Domain: `localization`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ro_cpv_code)
- Direct dependencies: [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_ro_cpv_code`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `l10n_ro.cpv.code`
- Extends `account.edi.xml.ubl_ro` — defined by [`l10n_ro_edi`](../l10n_ro_edi/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)

## Related SME agents

- [`module.l10n_ro_edi`](../../../agents/modules/generated/l10n_ro_edi.yaml) — extends_model_from
- [`module.l10n_ro_efactura`](../../../agents/modules/generated/l10n_ro_efactura.yaml) — depends_on
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
