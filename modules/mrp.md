---
layout: page
title: "Manufacturing (mrp)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mrp/
nav_order: 0
---
# Manufacturing — `mrp`

**Source:** [`agents/modules/generated/mrp.yaml`](../../agents/modules/generated/mrp.yaml) · **Wiki:** [`knowledge/modules/mrp/overview.md`](../../knowledge/modules/mrp/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mrp</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Manufacturing</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">manufacturing</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mrp</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manufacturing Orders & BOMs

## Direct dependencies

[`product`](product.md), [`resource`](resource.md), [`stock`](stock.md)

## Reverse dependencies (modules that depend on this)

[`mrp_account`](mrp_account.md), [`mrp_landed_costs`](mrp_landed_costs.md), [`mrp_product_expiry`](mrp_product_expiry.md), [`mrp_repair`](mrp_repair.md), [`mrp_subcontracting`](mrp_subcontracting.md), [`pos_mrp`](pos_mrp.md), [`purchase_mrp`](purchase_mrp.md), [`sale_mrp`](sale_mrp.md), [`test_main_flows`](test_main_flows.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>change.production.qty</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.bom</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.bom.byproduct</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.bom.line</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.consumption.warning</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.consumption.warning.line</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.document</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.production</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.production.backorder</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.production.backorder.line</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.production.split</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.production.split.line</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.production.split.multi</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.routing.workcenter</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.unbuild</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.workcenter</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.workcenter.capacity</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.workcenter.productivity</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.workcenter.productivity.loss</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.workcenter.productivity.loss.type</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.workcenter.tag</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.workorder</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>report.mrp.report_bom_structure</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>report.mrp.report_mo_overview</code></div><div class="role">defined by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.warn.insufficient.qty.unbuild</code></div><div class="role">defined by <code>mrp</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.bom</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.bom.byproduct</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.bom.line</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.production</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.routing.workcenter</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>mrp.workcenter</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>picking.label.type</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>procurement.group</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>product.product</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>product.replenish</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>product.template</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>report.stock.report_reception</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>report.stock.report_stock_rule</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>resource.mixin</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.assign.serial</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.forecasted_product_product</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.lot</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.move</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.move.line</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.picking</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.picking.type</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.quant</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.rule</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.scrap</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.traceability.report</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.warehouse</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.warehouse.orderpoint</code></div><div class="role">extended by <code>mrp</code></div></div>
<div class="model"><div class="name"><code>stock.warn.insufficient.qty</code></div><div class="role">extended by <code>mrp</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mrp_account` | extends_model_from, model_extended_by, required_by | `agents/modules/generated/mrp_account.yaml` |
| `module.mrp_landed_costs` | required_by | `agents/modules/generated/mrp_landed_costs.yaml` |
| `module.mrp_product_expiry` | model_extended_by, required_by | `agents/modules/generated/mrp_product_expiry.yaml` |
| `module.mrp_repair` | required_by | `agents/modules/generated/mrp_repair.yaml` |
| `module.mrp_subcontracting` | extends_model_from, model_extended_by, required_by | `agents/modules/generated/mrp_subcontracting.yaml` |

## Full wiki excerpt

- SME owner: [`module.mrp`](../../../agents/modules/generated/mrp.yaml)
- Domain: `manufacturing`
- Category: Manufacturing/Manufacturing
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp)
- Direct dependencies: [`product`](../product/overview.md), [`resource`](../resource/overview.md), [`stock`](../stock/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`mrp_account`](../mrp_account/overview.md), [`mrp_landed_costs`](../mrp_landed_costs/overview.md), [`mrp_product_expiry`](../mrp_product_expiry/overview.md), [`mrp_repair`](../mrp_repair/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`pos_mrp`](../pos_mrp/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md), [`sale_mrp`](../sale_mrp/overview.md), [`test_main_flows`](../test_main_flows/overview.md)
- Impact graph: [`module:mrp`](../../impact-graph.json)

## Purpose

Manufacturing Orders & BOMs

## Model relationships

- `change.production.qty` — extended by [`mrp_subcontracting`](../mrp_subcontracting/overview.md)
- `mrp.bom` — extended by [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md), [`sale_mrp`](../sale_mrp/overview.md)
- `mrp.bom.byproduct`
- `mrp.bom.line` — extended by [`purchase_mrp`](../purchase_mrp/overview.md)
- `mrp.consumption.warning` — extended by [`mrp_subcontracting`](../mrp_subcontracting/overview.md)
- `mrp.consumption.warning.line`
- `mrp.document`
- `mrp.production` — extended by [`mrp_account`](../mrp_account/overview.md), [`mrp_product_expiry`](../mrp_product_expiry/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`project_mrp`](../project_mrp/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md), [`sale_mrp`](../sale_mrp/overview.md)
- `mrp.production.backorder`
- `mrp.production.backorder.line`
- `mrp.production.split`
- `mrp.production.split.line`
- `mrp.production.split.multi`
- `mrp.routing.workcenter` — extended by [`mrp_account`](../mrp_account/overview.md)
- `mrp.unbuild`
- `mrp.workcenter` — extended by [`mrp_account`](../mrp_account/overview.md)
- `mrp.workcenter.capacity`
- `mrp.workcenter.productivity`
- `mrp.workcenter.productivity.loss`
- `mrp.workcenter.productivity.loss.type`
- `mrp.workcenter.tag`
- `mrp.workorder` — extended by [`mrp_account`](../mrp_account/overview.md)
- `report.mrp.report_bom_structure` — extended by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md)
- `report.mrp.report_mo_overview` — extended by [`mrp_account`](../mrp_account/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md)
- `stock.warn.insufficient.qty.unbuild`
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `mrp.bom` — defined by [`mrp_account`](../mrp_account/overview.md)
- Extends `mrp.bom.byproduct` — framework/dynamic owner
- Extends `mrp.bom.line` — framework/dynamic owner
- Extends `mrp.production` — defined by [`mrp_account`](../mrp_account/overview.md)
- Extends `mrp.routing.workcenter` — framework/dynamic owner
- Extends `mrp.workcenter` — defined by [`mrp_account`](../mrp_account/overview.md)
- Extends `picking.label.type` — defined by [`stock`](../stock/overview.md)
- Extends `procurement.group` — defined by [`stock`](../stock/overview.md)
- Extends `product.product` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md)
- Extends `product.replenish` — defined by [`stock`](../stock/overview.md)
- Extends `product.template` — defined by [`mrp_account`](../mrp_account/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `report.stock.report_reception` — defined by [`stock`](../stock/overview.md)
- Extends `report.stock.report_stock_rule` — defined by [`stock`](../stock/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `resource.mixin` — defined by [`resource`](../resource/overview.md)
- Extends `stock.assign.serial` — defined by [`stock`](../stock/overview.md)
- Extends `stock.forecasted_product_product` — defined by [`stock`](../stock/overview.md)
- Extends `stock.lot` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move` — defined by [`stock`](../stock/overview.md)
- Extends `stock.move.line` — defined by [`stock`](../stock/overview.md)
- Extends `stock.picking` — defined by [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`stock`](../stock/overview.md)
- Extends `stock.picking.type` — defined by [`stock`](../stock/overview.md)
- Extends `stock.quant` — defined by [`stock`](../stock/overview.md)
- Extends `stock.rule` — defined by [`stock`](../stock/overview.md)
- Extends `stock.scrap` — defined by [`stock`](../stock/overview.md)
- Extends `stock.traceability.report` — defined by [`stock`](../stock/overview.md)
- Extends `stock.warehouse` — defined by [`stock`](../stock/overview.md)
- Extends `stock.warehouse.orderpoint` — defined by [`stock`](../stock/overview.md)
- Extends `stock.warn.insufficient.qty` — defined by [`stock`](../stock/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from, model_extended_by, required_by
- [`module.mrp_landed_costs`](../../../agents/modules/generated/mrp_landed_costs.yaml) — required_by
- [`module.mrp_product_expiry`](../../../agents/modules/generated/mrp_product_expiry.yaml) — model_extended_by, required_by
- [`module.mrp_repair`](../../../agents/modules/generated/mrp_repair.yaml) — required_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — extends_model_from, model_extended_by, required_by
- [`module.mrp_subcontracting_account`](../../../agents/modules/generated/mrp_subcontracting_account.yaml) — model_extended_by
- [`module.mrp_subcontracting_purchase`](../../../agents/modules/generated/mrp_subcontracting_purchase.yaml) — model_extended_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.pos_mrp`](../../../agents/modules/generated/pos_mrp.yaml) — required_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — depends_on, extends_model_from
- [`module.project_mrp`](../../../agents/modules/generated/project_mrp.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.purchase_mrp`](../../../agents/modules/generated/purchase_mrp.yaml) — model_extended_by, required_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — extends_model_from
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — depends_on, extends_model_from
- [`module.sale_mrp`](../../../agents/modules/generated/sale_mrp.yaml) — model_extended_by, required_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — depends_on, extends_model_from
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — extends_model_from
- [`module.test_main_flows`](../../../agents/modules/generated/test_main_flows.yaml) — required_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 9 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`mrp_account`](../mrp_account/overview.md), [`mrp_product_expiry`](../mrp_product_expiry/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_account`](../mrp_subcontracting_account/overview.md), [`mrp_subcontracting_purchase`](../mrp_subcontracting_purchase/overview.md), [`project_mrp`](../project_mrp/overview.md), [`purchase_mrp`](../purchase_mrp/overview.md), [`sale_mrp`](../sale_mrp/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`mrp_account`](../mrp_account/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`product`](../product/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`resource`](../resource/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
