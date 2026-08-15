---
layout: custom-page
title: "nhcl_customizations (nhcl_customizations)"
subtitle: "Custom addon — RetailEnterprise/Store/nhcl_customizations"
permalink: /custom-addons/nhcl_customizations/
nav_order: 0
nav_title: "nhcl_customizations"
---
# nhcl_customizations

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>nhcl_customizations</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/nhcl_customizations</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

NHCL Customizations — Store-side base customization bundle shared across the store-side deployment.

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
# Part of Odoo. See LICENSE file for full copyright and licensing details.
{
    'name': 'NHCL Customizations',
    'version': '1.0',
    'sequence': 1,
    'category': 'Purchase',
    "author": "New Horizons Cybersoft Ltd",
    "website": "https://www.nhclindia.com/",
    'summary': 'Purchase,Contact,Stock,Product Customizations',
    'description': """
This module contains all the common features of Transport and Check.
    """,
    'depends': ['purchase', 'base', 'stock', 'mail', 'base_setup', 'product', 'point_of_sale', 'hr',
                'purchase_product_matrix', 'sale',
                'purchase_stock', 'sale_stock', 'hr_expense', 'fleet', 'account', 'mrp', 'loyalty',
                'stock_picking_batch','wt_pos_fix_discount','l10n_in'],
    'external_dependencies': {
        'python': ['odf', 'openpyxl', 'xlrd', 'XlsxWriter'],
    },
    'data': [
        'security/ir.model.access.csv',
        'security/sales_incentive_security.xml',
        'security/stock_backorder_notify_security.xml',
        'data/sequence.xml',
        'data/active_promo_cron.xml',
        'data/stock_backorder_cron.xml',
         "data/stock_picking_inherit.xml",
        'views/ho_store_configuration_view.xml',
        'views/transport_menu.xml',
        'views/pos_dashboard_menu.xml',
        'views/transport_details_view.xml',
        'views/fleet_vehicle_view.xml',
        'views/routes_details_view.xml',
        'views/location_view.xml',
        'views/transport_entry_view.xml',
        'wizard/mis_reports_actions_menu.xml',
        # 'report/dev_transport_report_template.xml',
        # 'report/dev_transport_report_menu.xml',
        # 'report/delivery_slip.xml',
        'views/contact_master.xml',
        "views/purchase_approval_buttons.xml",
        "views/sale_order_view.xml",
        "views/account_move.xml",
        'views/product_template_views.xml',
        'views/stock_views.xml',
        'views/loyalty_program_view.xml',
        'views/stoc
```
