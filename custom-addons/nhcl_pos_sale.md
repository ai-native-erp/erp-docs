---
layout: custom-page
title: "nhcl_pos_sale (nhcl_pos_sale)"
subtitle: "Custom addon — RetailEnterprise/Store/nhcl_pos_sale"
permalink: /custom-addons/nhcl_pos_sale/
nav_order: 0
nav_title: "nhcl_pos_sale"
---
# nhcl_pos_sale

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>nhcl_pos_sale</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/nhcl_pos_sale</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

NHCL POS-Sale — POS-side sales extension feeding the outbox + ack sync, loyalty integration, and credit-note flow.

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    'name': 'NHCL POS Sale',
    'Version': '17.0.1.1.0',
    'category': 'Point of Sale',
    'author': 'New Horizons CyberSoft Ltd',
    'company': 'New Horizons CyberSoft Ltd',
    'maintainer': 'New Horizons CyberSoft Ltd',
    'website': "https://www.nhclindia.com",
    'depends': ['point_of_sale','web','hr','pos_hr','stock','ultimate_pos_shortcuts','pos_discount','nhcl_store_to_ho_transactions','bi_pos_upi_payment', 'pos_sale','wt_pos_fix_discount'],
    'data': [
        'security/ir.model.access.csv',
        'views/pos_orderline_views.xml',
        'views/hr_employee_views.xml',
        'views/session_stock_check.xml',
        'views/stock_views.xml',
    ],
    'assets': {
        'point_of_sale._assets_pos': [
            'nhcl_pos_sale/static/src/**/*',
            'nhcl_pos_sale/static/src/xml/renaming_buttons.xml',
            ],
    },
    'license': 'LGPL-3',
    'installable': True,
    'auto_install': False,
    'application': False,
}
```
