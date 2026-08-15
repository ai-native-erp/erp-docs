---
layout: page
title: "MRP Subcontracting (mrp_subcontracting)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mrp_subcontracting/
nav_order: 0
---
# MRP Subcontracting — `mrp_subcontracting`

**Source:** [`agents/modules/generated/mrp_subcontracting.yaml`](../../agents/modules/generated/mrp_subcontracting.yaml) · **Wiki:** [`knowledge/modules/mrp_subcontracting/overview.md`](../../knowledge/modules/mrp_subcontracting/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mrp_subcontracting</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">MRP Subcontracting</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">manufacturing</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mrp_subcontracting</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_subcontracting"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Subcontract Productions

## Direct dependencies

[`mrp`](mrp.md)

## Reverse dependencies (modules that depend on this)

[`mrp_subcontracting_account`](mrp_subcontracting_account.md), [`mrp_subcontracting_dropshipping`](mrp_subcontracting_dropshipping.md), [`mrp_subcontracting_purchase`](mrp_subcontracting_purchase.md), [`mrp_subcontracting_repair`](mrp_subcontracting_repair.md), [`mrp_subonctracting_landed_costs`](mrp_subonctracting_landed_costs.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">defined by <code>mrp_subcontracting</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>change.production.qty</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>mrp.bom</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>mrp.consumption.warning</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>mrp.production</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>product.replenish</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>product.supplierinfo</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>report.mrp.report_bom_structure</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>stock.location</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>stock.move.line</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>stock.quant</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>stock.return.picking</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>stock.rule</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
<div class="model"><div class="name"><code>stock.warehouse</code></div><div class="role">extended by <code>mrp_subcontracting</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.delivery_stock_picking_batch` | model_extended_by | `agents/modules/generated/delivery_stock_picking_batch.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_din5008_stock` | model_extended_by | `agents/modules/generated/l10n_din5008_stock.yaml` |
| `module.l10n_in_ewaybill_stock` | model_extended_by | `agents/modules/generated/l10n_in_ewaybill_stock.yaml` |
| `module.l10n_in_purchase_stock` | model_extended_by | `agents/modules/generated/l10n_in_purchase_stock.yaml` |
| `module.l10n_in_sale_stock` | model_extended_by | `agents/modules/generated/l10n_in_sale_stock.yaml` |
| `module.l10n_in_stock` | model_extended_by | `agents/modules/generated/l10n_in_stock.yaml` |

## Full wiki excerpt

- SME owner: [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml)
- Domain: `manufacturing`
- Category: Manufacturing/Manufacturing
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_subcontracting)
- Direct dependencies: [`mrp`](../mrp/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`mrp_subcontracting_repair`](../mrp_subcontracting_repair/overview.md), [`mrp_subonctracting_landed_costs`](../mrp_subonctracting_landed_costs/overview.md)
- Impact graph: [`module:mrp_subcontracting`](../../impact-graph.json)

## Purpose

Subcontract Productions

## Model relationships

- `stock.picking` — extended by [`delivery_stock_picking_batch`](../delivery_stock_picking_batch/overview.md), [`l10n_din5008_stock`](../l10n_din5008_stock/overview.md), [`l10n_in_ewaybill_stock`](../l10n_in_ewaybill_stock/overview.md), [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md), [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md), [`l10n_in_stock`](../l10n_in_stock/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`l10n_ro_edi_stock_batch`](../l10n_ro_edi_stock_batch/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`mrp`](../mrp/overview.md), [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_sale`](../pos_sale/overview.md), [`product_expiry`](../product_expiry/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale_stock`](../sale_stock/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md), [`stock_sms`](../stock_sms/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md)
- Extends `change.production.qty` — defined by [`mrp`](../mrp/overview.md)
- Extends `mrp.bom` — defined by [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md)
- Extends `mrp.consumption.warning` — defined by [`mrp`](../mrp/overview.md)
- Extends `mrp.production` — defined by [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.replenish` — defined by [`stock`](../stock/overview.md)
- Extends `product.supplierinfo` — defined by [`product`](../product/overview.md)
- Extends `report.mrp.report_bom_structure` — defined by [`mrp`](../mrp/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `stock.location` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move.line` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`stock`](../stock/overview.md)
- Extends `stock.quant` — defined by [`stock`](../stock/overview.md)
- Extends `stock.return.picking` — defined by [`stock`](../stock/overview.md)
- Extends `stock.rule` — defined by [`stock`](../stock/overview.md)
- Extends `stock.warehouse` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.delivery_stock_picking_batch`](../../../agents/modules/generated/delivery_stock_picking_batch.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_din5008_stock`](../../../agents/modules/generated/l10n_din5008_stock.yaml) — model_extended_by
- [`module.l10n_in_ewaybill_stock`](../../../agents/modules/generated/l10n_in_ewaybill_stock.yaml) — model_extended_by
- [`module.l10n_in_purchase_stock`](../../../agents/modules/generated/l10n_in_purchase_stock.yaml) — model_extended_by
- [`module.l10n_in_sale_stock`](../../../agents/modules/generated/l10n_in_sale_stock.yaml) — model_extended_by
- [`module.l10n_in_stock`](../../../agents/modules/generated/l10n_in_stock.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_it_stock_ddt`](../../../agents/modules/generated/l10n_it_stock_ddt.yaml) — model_extended_by
- [`module.l10n_ro_edi_stock_batch`](../../../agents/modules/generated/l10n_ro_edi_stock_batch.yaml) — model_extended_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_edispatch`](../../../agents/modules/generated/l10n_tr_nilvera_edispatch.yaml) — model_extended_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.mrp_subcontracting_account`](../../../agents/modules/generated/mrp_subcontracting_account.yaml) — model_extended_by, required_by
- [`module.mrp_subcontracting_dropshipping`](../../../agents/modules/generated/mrp_subcontracting_dropshipping.yaml) — model_extended_by, required_by
- [`module.mrp_subcontracting_purchase`](../../../agents/modules/generated/mrp_subcontracting_purchase.yaml) — model_extended_by, required_by
- [`module.mrp_subcontracting_repair`](../../../agents/modules/generated/mrp_subcontracting_repair.yaml) — required_by
- [`module.mrp_subonctracting_landed_costs`](../../../agents/modules/generated/mrp_subonctracting_landed_costs.yaml) — required_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml) — model_extended_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — extends_model_from
- [`module.product_expiry`](../../../agents/modules/generated/product_expiry.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from, model_extended_by
- [`module.repair`](../../../agents/modules/generated/repair.yaml) — model_extended_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — extends_model_from, model_extended_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — model_extended_by
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — model_extended_by
- [`module.stock_dropshipping`](../../../agents/modules/generated/stock_dropshipping.yaml) — model_extended_by
- [`module.stock_picking_batch`](../../../agents/modules/generated/stock_picking_batch.yaml) — model_extended_by
- [`module.stock_sms`](../../../agents/modules/generated/stock_sms.yaml) — model_extended_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml) — model_extended_by

## Regression impact checklist

- Review 5 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`delivery_stock_picking_batch`](../delivery_stock_picking_batch/overview.md), [`l10n_din5008_stock`](../l10n_din5008_stock/overview.md), [`l10n_in_ewaybill_stock`](../l10n_in_ewaybill_stock/overview.md), [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md), [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md), [`l10n_in_stock`](../l10n_in_stock/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`l10n_ro_edi_stock_batch`](../l10n_ro_edi_stock_batch/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`mrp`](../mrp/overview.md), [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_sale`](../pos_sale/overview.md), [`product_expiry`](../product_expiry/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale_stock`](../sale_stock/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md), [`stock_sms`](../stock_sms/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sms`](../sms/overview.md), [`stock`](../stock/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
