---
layout: page
title: "Delivery Costs (delivery)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/delivery/
nav_order: 0
---
# Delivery Costs — `delivery`

**Source:** [`agents/modules/generated/delivery.yaml`](../../agents/modules/generated/delivery.yaml) · **Wiki:** [`knowledge/modules/delivery/overview.md`](../../knowledge/modules/delivery/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>delivery</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Delivery Costs</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/delivery</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/delivery"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`sale`](sale.md)

## Reverse dependencies (modules that depend on this)

[`sale_loyalty_delivery`](sale_loyalty_delivery.md), [`stock_delivery`](stock_delivery.md), [`website_sale`](website_sale.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>choose.delivery.carrier</code></div><div class="role">defined by <code>delivery</code></div></div>
<div class="model"><div class="name"><code>delivery.carrier</code></div><div class="role">defined by <code>delivery</code></div></div>
<div class="model"><div class="name"><code>delivery.price.rule</code></div><div class="role">defined by <code>delivery</code></div></div>
<div class="model"><div class="name"><code>delivery.zip.prefix</code></div><div class="role">defined by <code>delivery</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>product.category</code></div><div class="role">extended by <code>delivery</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>delivery</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>delivery</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>delivery</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.delivery_mondialrelay` | model_extended_by | `agents/modules/generated/delivery_mondialrelay.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_ro_edi_stock` | model_extended_by | `agents/modules/generated/l10n_ro_edi_stock.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |

## Full wiki excerpt

- SME owner: [`module.delivery`](../../../agents/modules/generated/delivery.yaml)
- Domain: `inventory_purchase`
- Category: Sales/Delivery
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/delivery)
- Direct dependencies: [`sale`](../sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`sale_loyalty_delivery`](../sale_loyalty_delivery/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`website_sale`](../website_sale/overview.md)
- Impact graph: [`module:delivery`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `choose.delivery.carrier` — extended by [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`stock_delivery`](../stock_delivery/overview.md)
- `delivery.carrier` — extended by [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`l10n_ro_edi_stock`](../l10n_ro_edi_stock/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md)
- `delivery.price.rule`
- `delivery.zip.prefix`
- Extends `product.category` — defined by [`product`](../product/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.delivery_mondialrelay`](../../../agents/modules/generated/delivery_mondialrelay.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_ro_edi_stock`](../../../agents/modules/generated/l10n_ro_edi_stock.yaml) — model_extended_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — depends_on, extends_model_from
- [`module.sale_loyalty_delivery`](../../../agents/modules/generated/sale_loyalty_delivery.yaml) — required_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — model_extended_by, required_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by, required_by
- [`module.website_sale_picking`](../../../agents/modules/generated/website_sale_picking.yaml) — model_extended_by

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`l10n_ro_edi_stock`](../l10n_ro_edi_stock/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`sale`](../sale/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
