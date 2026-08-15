---
layout: custom-page
title: "nhcl_pos_custom_tax (nhcl_pos_custom_tax)"
subtitle: "Custom addon — RetailEnterprise/Store/nhcl_pos_custom_tax"
permalink: /custom-addons/nhcl_pos_custom_tax/
nav_order: 0
nav_title: "nhcl_pos_custom_tax"
---
# nhcl_pos_custom_tax

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>nhcl_pos_custom_tax</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/nhcl_pos_custom_tax</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

nhcl_pos_custom_tax

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
{
    'name': 'NHCL POS Custom Tax',
    'summary': 'Pos Custom Tax',
    'author': 'New Horizons CyberSoft Ltd',
    "description": """ This Module is use for Tax Computation with Multi Taxes in Point of Sale, we will help you to calculation on Product Tax. """,
    'category': 'Accounting',
    'company': 'New Horizons CyberSoft Ltd',
    'maintainer': 'New Horizons CyberSoft Ltd',
    'website': "https://www.nhclindia.com",
    'depends': ['account_tax_python', 'point_of_sale', 'pos_loyalty', 'nhcl_customizations', 'pos_restaurant',
                'stock_account', 'sale'],
    'version': '1.0',
    'data': [
        'security/ir.model.access.csv',
        'views/account_tax_view.xml',
        'views/sale_order_view.xml',
        'views/loyalty_reward_view.xml',
        'reports/sale_hrs_report_views.xml',
        'reports/report_views.xml',
        'wizard/pos_analysis_views.xml',
        'reports/pos_analysis_report_views.xml',
        'reports/pos_analysis_report_templates.xml'
    ],
    'assets': {
        'point_of_sale._assets_pos': [
            'nhcl_pos_custom_tax/static/src/override/models/*',
            'nhcl_pos_custom_tax/static/src/app/control_buttons/reward_button/*',
            'nhcl_pos_custom_tax/static/src/override/screens/receiptScreen.xml',
            'nhcl_pos_custom_tax/static/src/css/*',
            'nhcl_pos_custom_tax/static/src/scss/*',
            'nhcl_pos_custom_tax/static/src/xml/*',
            "nhcl_pos_custom_tax/static/src/app/control_buttons/reward_button/highlight.js",
        ],
    },
    'images': ['static/description/background.gif'],
    'installable': True,
    'application': False,
    'auto_install': False,
    "currency": "INR",
    'license': 'LGPL-3',
}
```
