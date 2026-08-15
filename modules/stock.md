---
layout: page
title: "Inventory (stock)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/stock/
nav_order: 0
---
# Inventory — `stock`

**Source:** [`agents/modules/generated/stock.yaml`](../../agents/modules/generated/stock.yaml) · **Wiki:** [`knowledge/modules/stock/overview.md`](../../knowledge/modules/stock/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>stock</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Inventory</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/stock</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage your stock and logistics activities

## Direct dependencies

[`barcodes_gs1_nomenclature`](barcodes_gs1_nomenclature.md), [`digest`](digest.md), [`product`](product.md)

## Reverse dependencies (modules that depend on this)

[`l10n_din5008_stock`](l10n_din5008_stock.md), [`l10n_ec_stock`](l10n_ec_stock.md), [`l10n_in_stock`](l10n_in_stock.md), [`l10n_tr_nilvera_edispatch`](l10n_tr_nilvera_edispatch.md), [`mrp`](mrp.md), [`product_expiry`](product_expiry.md), [`stock_account`](stock_account.md), [`stock_picking_batch`](stock_picking_batch.md), [`stock_sms`](stock_sms.md), [`website_sale_picking`](website_sale_picking.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>lot.label.layout</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>picking.label.type</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>procurement.group</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>product.removal</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>product.replenish</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>report.stock.label_lot_template_view</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>report.stock.label_product_product_view</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>report.stock.quantity</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>report.stock.report_reception</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>report.stock.report_stock_rule</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.assign.serial</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.backorder.confirmation</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.backorder.confirmation.line</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.change.product.qty</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.forecasted_product_product</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.forecasted_product_template</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.inventory.adjustment.name</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.inventory.conflict</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.inventory.warning</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.location</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.lot</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.move.line</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.orderpoint.snooze</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.package.destination</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.package.type</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.package_level</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.picking.type</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.putaway.rule</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.quant</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.quant.package</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.quant.relocate</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.quantity.history</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.replenishment.info</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.replenishment.option</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.request.count</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.return.picking</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.return.picking.line</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.route</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.rule</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.rules.report</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.scheduler.compute</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.scrap</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.storage.category</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.storage.category.capacity</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.traceability.report</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.track.confirmation</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.track.line</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.warehouse</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.warehouse.orderpoint</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.warn.insufficient.qty</code></div><div class="role">defined by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.warn.insufficient.qty.scrap</code></div><div class="role">defined by <code>stock</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>barcode.rule</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>ir.actions.report</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>product.category</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>product.label.layout</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>product.packaging</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.forecasted_product_product</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.location</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.picking.type</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.putaway.rule</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.quant</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.storage.category</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.warehouse</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.warehouse.orderpoint</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>stock.warn.insufficient.qty</code></div><div class="role">extended by <code>stock</code></div></div>
<div class="model"><div class="name"><code>uom.uom</code></div><div class="role">extended by <code>stock</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.barcodes` | extends_model_from | `agents/modules/generated/barcodes.yaml` |
| `module.barcodes_gs1_nomenclature` | depends_on | `agents/modules/generated/barcodes_gs1_nomenclature.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.delivery_stock_picking_batch` | model_extended_by | `agents/modules/generated/delivery_stock_picking_batch.yaml` |
| `module.digest` | depends_on | `agents/modules/generated/digest.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_din5008_stock` | model_extended_by, required_by | `agents/modules/generated/l10n_din5008_stock.yaml` |

## Conversation learnings

- [`2026-08-12-cmr-backup-restore-capacity`](../../knowledge/conversations/2026-08-12-cmr-backup-restore-capacity.json)
- [`2026-08-12-cmr-endpoint-bootstrap-enterprise-gate`](../../knowledge/conversations/2026-08-12-cmr-endpoint-bootstrap-enterprise-gate.json)
- [`2026-08-12-cmr-ho-store-isolation`](../../knowledge/conversations/2026-08-12-cmr-ho-store-isolation.json)
- [`2026-08-14-ho-customer-schema-drift-upgrade`](../../knowledge/conversations/2026-08-14-ho-customer-schema-drift-upgrade.json)

## Full wiki excerpt

- SME owner: [`module.stock`](../../../agents/modules/generated/stock.yaml)
- Domain: `inventory_purchase`
- Category: Inventory/Inventory
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/stock)
- Direct dependencies: [`barcodes_gs1_nomenclature`](../barcodes_gs1_nomenclature/overview.md), [`digest`](../digest/overview.md), [`product`](../product/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_din5008_stock`](../l10n_din5008_stock/overview.md), [`l10n_ec_stock`](../l10n_ec_stock/overview.md), [`l10n_in_stock`](../l10n_in_stock/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`mrp`](../mrp/overview.md), [`product_expiry`](../product_expiry/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md), [`stock_sms`](../stock_sms/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md)
- Impact graph: [`module:stock`](../../impact-graph.json)

## Purpose

Manage your stock and logistics activities

## Model relationships

- `lot.label.layout`
- `picking.label.type` — extended by [`mrp`](../mrp/overview.md)
- `procurement.group` — extended by [`mrp`](../mrp/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`product_expiry`](../product_expiry/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale_stock`](../sale_stock/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md)
- `product.removal`
- `product.replenish` — extended by [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md)
- `report.stock.label_lot_template_view`
- `report.stock.label_product_product_view`
- `report.stock.quantity`
- `report.stock.report_reception` — extended by [`mrp`](../mrp/overview.md)
- `report.stock.report_stock_rule` — extended by [`mrp`](../mrp/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale_stock`](../sale_stock/overview.md)
- `stock.assign.serial` — extended by [`mrp`](../mrp/overview.md)
- `stock.backorder.confirmation`
- `stock.backorder.confirmation.line`
- `stock.change.product.qty`
- `stock.forecasted_product_product` — extended by [`mrp`](../mrp/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale_stock`](../sale_stock/overview.md), [`stock_account`](../stock_account/overview.md)
- `stock.forecasted_product_template`
- `stock.inventory.adjustment.name`
- `stock.inventory.conflict`
- `stock.inventory.warning`
- `stock.location` — extended by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock_account`](../stock_account/overview.md)
- `stock.lot` — extended by [`mrp`](../mrp/overview.md), [`product_expiry`](../product_expiry/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale_stock`](../sale_stock/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md)
- `stock.move` — extended by [`l10n_in_ewaybill_stock`](../l10n_in_ewaybill_stock/overview.md), [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md), [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md), [`l10n_in_stock`](../l10n_in_stock/overview.md), [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_repair`](../mrp_repair/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_mrp`](../pos_mrp/overview.md), [`product_expiry`](../product_expiry/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md), [`purchase_requisition_stock`](../purchase_requisition_stock/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale_mrp`](../sale_mrp/overview.md), [`sale_stock`](../sale_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md)
- `stock.move.line` — extended by [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`product_expiry`](../product_expiry/overview.md), [`repair`](../repair/overview.md), [`sale_mrp`](../sale_mrp/overview.md), [`sale_stock`](../sale_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md)
- `stock.orderpoint.snooze`
- `stock.package.destination` — extended by [`stock_picking_batch`](../stock_picking_batch/overview.md)
- `stock.package.type` — extended by [`stock_delivery`](../stock_delivery/overview.md)
- `stock.package_level`
- `stock.picking` — extended by [`delivery_stock_picking_batch`](../delivery_stock_picking_batch/overview.md), [`l10n_din5008_stock`](../l10n_din5008_stock/overview.md), [`l10n_in_ewaybill_stock`](../l10n_in_ewaybill_stock/overview.md), [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md), [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md), [`l10n_in_stock`](../l10n_in_stock/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`l10n_ro_edi_stock_batch`](../l10n_ro_edi_stock_batch/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_sale`](../pos_sale/overview.md), [`product_expiry`](../product_expiry/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale_stock`](../sale_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md), [`stock_sms`](../stock_sms/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md)
- `stock.picking.type` — extended by [`delivery_stock_picking_batch`](../delivery_stock_picking_batch/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`mrp`](../mrp/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`repair`](../repair/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md)
- `stock.putaway.rule`
- `stock.quant` — extended by [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`product_expiry`](../product_expiry/overview.md), [`stock_account`](../stock_account/overview.md)
- `stock.quant.package` — extended by [`stock_delivery`](../stock_delivery/overview.md)
- `stock.quant.relocate`
- `stock.quantity.history` — extended by [`stock_account`](../stock_account/overview.md)
- `stock.replenishment.info` — extended by [`purchase_stock`](../purchase_stock/overview.md)
- `stock.replenishment.option` — extended by [`purchase_stock`](../purchase_stock/overview.md)
- `stock.request.count` — extended by [`stock_account`](../stock_account/overview.md)
- `stock.return.picking` — extended by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md)
- `stock.return.picking.line` — extended by [`stock_account`](../stock_account/overview.md)
- `stock.route` — extended by [`sale_stock`](../sale_stock/overview.md), [`stock_delivery`](../stock_delivery/overview.md)
- `stock.rule` — extended by [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`purchase_requisition_stock`](../purchase_requisition_stock/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale_stock`](../sale_stock/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md)
- `stock.rules.report` — extended by [`sale_stock`](../sale_stock/overview.md)
- `stock.scheduler.compute`
- `stock.scrap` — extended by [`mrp`](../mrp/overview.md)
- `stock.storage.category`
- `stock.storage.category.capacity`
- `stock.traceability.report` — extended by [`mrp`](../mrp/overview.md), [`repair`](../repair/overview.md)
- `stock.track.confirmation`
- `stock.track.line`
- `stock.warehouse` — extended by [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md)
- `stock.warehouse.orderpoint` — extended by [`mrp`](../mrp/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`purchase_requisition_stock`](../purchase_requisition_stock/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- `stock.warn.insufficient.qty` — extended by [`mrp`](../mrp/overview.md), [`repair`](../repair/overview.md)
- `stock.warn.insufficient.qty.scrap`
- Extends `barcode.rule` — defined by [`barcodes`](../barcodes/overview.md)
- Extends `ir.actions.report` — defined by [`base`](../base/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `product.category` — defined by [`product`](../product/overview.md)
- Extends `product.label.layout` — defined by [`product`](../product/overview.md)
- Extends `product.packaging` — defined by [`product`](../product/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `stock.forecasted_product_product` — framework/dynamic owner
- Extends `stock.location` — framework/dynamic owner
- Extends `stock.move` — framework/dynamic owner
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md)
- Extends `stock.picking.type` — framework/dynamic owner
- Extends `stock.putaway.rule` — framework/dynamic owner
- Extends `stock.quant` — framework/dynamic owner
- Extends `stock.storage.category` — framework/dynamic owner
- Extends `stock.warehouse` — framework/dynamic owner
- Extends `stock.warehouse.orderpoint` — framework/dynamic owner
- Extends `stock.warn.insufficient.qty` — framework/dynamic owner
- Extends `uom.uom` — defined by [`uom`](../uom/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.barcodes`](../../../agents/modules/generated/barcodes.yaml) — extends_model_from
- [`module.barcodes_gs1_nomenclature`](../../../agents/modules/generated/barcodes_gs1_nomenclature.yaml) — depends_on
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.delivery_stock_picking_batch`](../../../agents/modules/generated/delivery_stock_picking_batch.yaml) — model_extended_by
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — depends_on
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_din5008_stock`](../../../agents/modules/generated/l10n_din5008_stock.yaml) — model_extended_by, required_by
- [`module.l10n_ec_stock`](../../../agents/modules/generated/l10n_ec_stock.yaml) — required_by
- [`module.l10n_in_ewaybill_stock`](../../../agents/modules/generated/l10n_in_ewaybill_stock.yaml) — model_extended_by
- [`module.l10n_in_purchase_stock`](../../../agents/modules/generated/l10n_in_purchase_stock.yaml) — model_extended_by
- [`module.l10n_in_sale_stock`](../../../agents/modules/generated/l10n_in_sale_stock.yaml) — model_extended_by
- [`module.l10n_in_stock`](../../../agents/modules/generated/l10n_in_stock.yaml) — model_extended_by, required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_it_stock_ddt`](../../../agents/modules/generated/l10n_it_stock_ddt.yaml) — model_extended_by
- [`module.l10n_ro_edi_stock_batch`](../../../agents/modules/generated/l10n_ro_edi_stock_batch.yaml) — model_extended_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_edispatch`](../../../agents/modules/generated/l10n_tr_nilvera_edispatch.yaml) — model_extended_by, required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — model_extended_by, required_by
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from, model_extended_by
- [`module.mrp_repair`](../../../agents/modules/generated/mrp_repair.yaml) — model_extended_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from, model_extended_by
- [`module.mrp_subcontracting_account`](../../../agents/modules/generated/mrp_subcontracting_account.yaml) — model_extended_by
- [`module.mrp_subcontracting_dropshipping`](../../../agents/modules/generated/mrp_subcontracting_dropshipping.yaml) — model_extended_by
- [`module.mrp_subcontracting_purchase`](../../../agents/modules/generated/mrp_subcontracting_purchase.yaml) — model_extended_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.pos_mrp`](../../../agents/modules/generated/pos_mrp.yaml) — model_extended_by
- [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml) — model_extended_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — depends_on, extends_model_from
- [`module.product_expiry`](../../../agents/modules/generated/product_expiry.yaml) — model_extended_by, required_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_mrp`](../../../agents/modules/generated/purchase_mrp.yaml) — model_extended_by
- [`module.purchase_requisition_stock`](../../../agents/modules/generated/purchase_requisition_stock.yaml) — model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from, model_extended_by
- [`module.repair`](../../../agents/modules/generated/repair.yaml) — model_extended_by
- [`module.sale_mrp`](../../../agents/modules/generated/sale_mrp.yaml) — model_extended_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from, model_extended_by, required_by
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — model_extended_by
- [`module.stock_dropshipping`](../../../agents/modules/generated/stock_dropshipping.yaml) — model_extended_by
- [`module.stock_picking_batch`](../../../agents/modules/generated/stock_picking_batch.yaml) — model_extended_by, required_by
- [`module.stock_sms`](../../../agents/modules/generated/stock_sms.yaml) — model_extended_by, required_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.uom`](../../../agents/modules/generated/uom.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from
- [`module.website_sale_picking`](../../../agents/modules/generated/website_sale_picking.yaml) — required_by
- [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml) — model_extended_by

## Regression impact checklist

- Review 10 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`delivery_stock_picking_batch`](../delivery_stock_picking_batch/overview.md), [`l10n_din5008_stock`](../l10n_din5008_stock/overview.md), [`l10n_in_ewaybill_stock`](../l10n_in_ewaybill_stock/overview.md), [`l10n_in_purchase_stock`](../l10n_in_purchase_stock/overview.md), [`l10n_in_sale_stock`](../l10n_in_sale_stock/overview.md), [`l10n_in_stock`](../l10n_in_stock/overview.md), [`l10n_it_stock_ddt`](../l10n_it_stock_ddt/overview.md), [`l10n_ro_edi_stock_batch`](../l10n_ro_edi_stock_batch/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_repair`](../mrp_repair/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`pos_mrp`](../pos_mrp/overview.md), [`pos_sale`](../pos_sale/overview.md), [`product_expiry`](../product_expiry/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md), [`purchase_requisition_stock`](../purchase_requisition_stock/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`repair`](../repair/overview.md), [`sale_mrp`](../sale_mrp/overview.md), [`sale_stock`](../sale_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_delivery`](../stock_delivery/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_picking_batch`](../stock_picking_batch/overview.md), [`stock_sms`](../stock_sms/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`barcodes`](../barcodes/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sms`](../sms/overview.md), [`stock_account`](../stock_account/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`uom`](../uom/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-12-cmr-backup-restore-capacity`](../../conversations/2026-08-12-cmr-backup-restore-capacity.json)
- [`2026-08-12-cmr-endpoint-bootstrap-enterprise-gate`](../../conversations/2026-08-12-cmr-endpoint-bootstrap-enterprise-gate.json)
- [`2026-08-12-cmr-ho-store-isolation`](../../conversations/2026-08-12-cmr-ho-store-isolation.json)
- [`2026-08-14-ho-customer-schema-drift-upgrade`](../../conversations/2026-08-14-ho-customer-schema-drift-upgrade.json)
