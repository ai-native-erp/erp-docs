---
layout: custom-page
title: "nhcl_pos_set_default_customer (nhcl_pos_set_default_customer)"
subtitle: "Custom addon — RetailEnterprise/Store/nhcl_pos_set_default_customer"
permalink: /custom-addons/nhcl_pos_set_default_customer/
nav_order: 0
nav_title: "nhcl_pos_set_default_customer"
---
# nhcl_pos_set_default_customer

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>nhcl_pos_set_default_customer</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/nhcl_pos_set_default_customer</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

nhcl_pos_set_default_customer

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
{
    'name': 'NHCL POS Default Customer',
    'summary': "Set Default Customer in POS",
    'description': 'Set Default Customer in POS',
    'author': 'New Horizons CyberSoft Ltd',
    'company': 'New Horizons CyberSoft Ltd',
    'maintainer': 'New Horizons CyberSoft Ltd',
    'website': "https://www.nhclindia.com",
    'category': 'Point of Sale',
    'version': '17.0.0.1.1',
    'depends': ['point_of_sale'],
    'data': [
        'views/pos_config_view.xml',
    ],
    'assets': {
        'point_of_sale._assets_pos': [
            'nhcl_pos_set_default_customer/static/src/js/get_customer.js',
        ],
    },
    'license': "OPL-1",
    'installable': True,
    'application': True,
    'images': ['static/description/banner.png'],
}
```
