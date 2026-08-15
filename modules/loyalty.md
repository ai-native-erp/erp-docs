---
layout: page
title: "Coupons & Loyalty (loyalty)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/loyalty/
nav_order: 0
---
# Coupons & Loyalty — `loyalty`

**Source:** [`agents/modules/generated/loyalty.yaml`](../../agents/modules/generated/loyalty.yaml) · **Wiki:** [`knowledge/modules/loyalty/overview.md`](../../knowledge/modules/loyalty/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>loyalty</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Coupons & Loyalty</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/loyalty</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/loyalty"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Use discounts, gift card, eWallets and loyalty programs in different sales channels

## Direct dependencies

[`product`](product.md)

## Reverse dependencies (modules that depend on this)

[`pos_loyalty`](pos_loyalty.md), [`sale_loyalty`](sale_loyalty.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>loyalty.card</code></div><div class="role">defined by <code>loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.generate.wizard</code></div><div class="role">defined by <code>loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.mail</code></div><div class="role">defined by <code>loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.program</code></div><div class="role">defined by <code>loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.reward</code></div><div class="role">defined by <code>loyalty</code></div></div>
<div class="model"><div class="name"><code>loyalty.rule</code></div><div class="role">defined by <code>loyalty</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>loyalty</code></div></div>
<div class="model"><div class="name"><code>product.pricelist</code></div><div class="role">extended by <code>loyalty</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>loyalty</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>loyalty</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>loyalty</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |

## Full wiki excerpt

- SME owner: [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml)
- Domain: `sales_crm`
- Category: Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/loyalty)
- Direct dependencies: [`product`](../product/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`pos_loyalty`](../pos_loyalty/overview.md), [`sale_loyalty`](../sale_loyalty/overview.md)
- Impact graph: [`module:loyalty`](../../impact-graph.json)

## Purpose

Use discounts, gift card, eWallets and loyalty programs in different sales channels

## Model relationships

- `loyalty.card` — extended by [`pos_loyalty`](../pos_loyalty/overview.md), [`sale_loyalty`](../sale_loyalty/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md)
- `loyalty.generate.wizard`
- `loyalty.mail` — extended by [`pos_loyalty`](../pos_loyalty/overview.md)
- `loyalty.program` — extended by [`pos_loyalty`](../pos_loyalty/overview.md), [`sale_loyalty`](../sale_loyalty/overview.md), [`sale_loyalty_delivery`](../sale_loyalty_delivery/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md)
- `loyalty.reward` — extended by [`pos_loyalty`](../pos_loyalty/overview.md), [`sale_loyalty`](../sale_loyalty/overview.md), [`sale_loyalty_delivery`](../sale_loyalty_delivery/overview.md)
- `loyalty.rule` — extended by [`pos_loyalty`](../pos_loyalty/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `product.pricelist` — defined by [`product`](../product/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.pos_loyalty`](../../../agents/modules/generated/pos_loyalty.yaml) — model_extended_by, required_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — depends_on, extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.sale_loyalty`](../../../agents/modules/generated/sale_loyalty.yaml) — model_extended_by, required_by
- [`module.sale_loyalty_delivery`](../../../agents/modules/generated/sale_loyalty_delivery.yaml) — model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from
- [`module.website_sale_loyalty`](../../../agents/modules/generated/website_sale_loyalty.yaml) — model_extended_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`pos_loyalty`](../pos_loyalty/overview.md), [`sale_loyalty`](../sale_loyalty/overview.md), [`sale_loyalty_delivery`](../sale_loyalty_delivery/overview.md), [`website_sale_loyalty`](../website_sale_loyalty/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mrp_account`](../mrp_account/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sms`](../sms/overview.md), [`stock_account`](../stock_account/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
