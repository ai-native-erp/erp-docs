---
layout: page
title: "Sales and Warehouse Management (sale_stock)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_stock/
nav_order: 0
---
# Sales and Warehouse Management — `sale_stock`

**Source:** [`agents/modules/generated/sale_stock.yaml`](../../agents/modules/generated/sale_stock.yaml) · **Wiki:** [`knowledge/modules/sale_stock/overview.md`](../../knowledge/modules/sale_stock/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_stock</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sales and Warehouse Management</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_stock</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_stock"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Quotation, Sales Orders, Delivery & Invoicing Control

## Direct dependencies

[`sale`](sale.md), [`stock_account`](stock_account.md)

## Reverse dependencies (modules that depend on this)

[`l10n_in_sale_stock`](l10n_in_sale_stock.md), [`repair`](repair.md), [`sale_mrp`](sale_mrp.md), [`sale_project_stock`](sale_project_stock.md), [`sale_purchase_stock`](sale_purchase_stock.md), [`sale_stock_margin`](sale_stock_margin.md), [`stock_delivery`](stock_delivery.md), [`website_sale_stock`](website_sale_stock.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>account.move.line</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>procurement.group</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>report.stock.report_stock_rule</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>sale.order.cancel</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>sale.report</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>stock.forecasted_product_product</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>stock.lot</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>stock.move.line</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>stock.route</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>stock.rule</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>stock.rules.report</code></div><div class="role">extended by <code>sale_stock</code></div></div>
<div class="model"><div class="name"><code>stock.valuation.layer</code></div><div class="role">extended by <code>sale_stock</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.l10n_in_sale_stock` | required_by | `agents/modules/generated/l10n_in_sale_stock.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml)
- Domain: `sales_crm`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_stock)
- Direct dependencies: [`sale`](../sale/overview.md), [`stock_account`](../stock_account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md), [`repair`](../repair/overview.md), [`sale_mrp`](../sale_mrp/overview.md), [`sale_project_stock`](../sale_project_stock/overview.md), [`sale_purchase_stock`](../sale_purchase_stock/overview.md), [`sale_stock_margin`](../sale_stock_margin/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md)
- Impact graph: [`module:sale_stock`](../../impact-graph.json)

## Purpose

Quotation, Sales Orders, Delivery & Invoicing Control

## Model relationships

- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `account.move.line` — defined by [`account`](../account/overview.md)
- Extends `procurement.group` — defined by [`stock`](../stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `report.stock.report_stock_rule` — defined by [`stock`](../stock/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.cancel` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)
- Extends `sale.report` — defined by [`sale`](../sale/overview.md)
- Extends `stock.forecasted_product_product` — defined by [`stock`](../stock/overview.md)
- Extends `stock.lot` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move.line` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)
- Extends `stock.route` — defined by [`stock`](../stock/overview.md)
- Extends `stock.rule` — defined by [`stock`](../stock/overview.md)
- Extends `stock.rules.report` — defined by [`stock`](../stock/overview.md)
- Extends `stock.valuation.layer` — defined by [`stock_account`](../stock_account/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.l10n_in_sale_stock`](../../../agents/modules/generated/l10n_in_sale_stock.yaml) — required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.repair`](../../../agents/modules/generated/repair.yaml) — required_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — depends_on, extends_model_from
- [`module.sale_mrp`](../../../agents/modules/generated/sale_mrp.yaml) — required_by
- [`module.sale_project_stock`](../../../agents/modules/generated/sale_project_stock.yaml) — required_by
- [`module.sale_purchase_stock`](../../../agents/modules/generated/sale_purchase_stock.yaml) — required_by
- [`module.sale_stock_margin`](../../../agents/modules/generated/sale_stock_margin.yaml) — required_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — depends_on, extends_model_from
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — required_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from
- [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml) — required_by

## Regression impact checklist

- Review 8 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
