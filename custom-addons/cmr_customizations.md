---
layout: custom-page
title: "cmr_customizations (cmr_customizations)"
subtitle: "Custom addon — RetailEnterprise/HeadOffice/cmr_customizations"
permalink: /custom-addons/cmr_customizations/
nav_order: 0
nav_title: "cmr_customizations"
---
# cmr_customizations

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>cmr_customizations</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/HeadOffice/cmr_customizations</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

CMR Customizations — Head-Office customization bundle covering accounting, HR, sales, and master-data behavior shared by every CMR-tenant database.

> **Deployment target:** Head Office.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
# Part of Odoo. See LICENSE file for full copyright and licensing details.


{
    'name': 'NHCL Customizations',
    'version': '1.0',
    'sequence': 1,
    'category': 'Customizations',
    "author": "New Horizons Cybersoft Ltd",
    "website": "https://www.nhclindia.com/",
    'summary': 'Purchase,Contact,Stock,Product Customizations',
    'description': """
This module contains all the common features of Transport and Check.
    """,
    'depends': ['purchase', 'base', 'stock', 'base_setup', 'product', 'hr', 'purchase_product_matrix', 'sale','l10n_in_ewaybill_stock',
                'sale_purchase_inter_company_rules', 'approvals', 'approvals_purchase', 'purchase_stock', 'sale_stock',
                'hr_expense', 'fleet', 'account', 'mrp', 'stock_picking_batch', 'l10n_in', 'stock_account', 'product','dynamic_label',
                'stock_landed_costs', 'stock_dropshipping', 'web','auth_signup','purchase_requisition','point_of_sale','loyalty','mail'],
    'external_dependencies': {
        'python': ['odf', 'openpyxl', 'xlrd', 'XlsxWriter', 'pandas'],
    },
    'data': [
        'security/ir.model.access.csv',
        'security/sales_incentive_security.xml',
        'security/purchase_order_approval_groups.xml',
        'security/approval_request_groups.xml',
        "data/sequence.xml",
        "data/email_templates.xml",
        "data/update_return_slip.xml",
        "data/cron_jobs.xml",
        "data/stock_picking_inherit.xml",
        'views/contact_master.xml',
        "views/logistic_screen_entry.xml",
        "views/transports_check_view.xml",
        'views/placement_master.xml',
        'views/logistic_status_view.xml',
        "views/delivery_check_view.xml",
        "views/open_parel.xml",
        "views/cmr_logistic_server_actions.xml",
        'wizard/import_po_lines_view.xml',
        "views/purchase_approval_buttons.xml",
        'wizard/import_approval_lines_view.xml',
        "views/approval_request_view.xml",
       
```
