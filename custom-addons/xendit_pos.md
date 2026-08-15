---
layout: custom-page
title: "xendit_pos (xendit_pos)"
subtitle: "Custom addon — RetailEnterprise/Store/xendit_pos"
permalink: /custom-addons/xendit_pos/
nav_order: 0
nav_title: "xendit_pos"
---
# xendit_pos

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>xendit_pos</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/xendit_pos</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

xendit_pos

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
{
    'name': "Xendit POS",
    'license': 'LGPL-3',
    'summary': """
        Xendit Odoo POS payment is an official built by Xendit to allow you in accepting online payments instantly. 
        """,

    'description': """
        Xendit Odoo POS payment is an official built by Xendit to allow you in accepting online payments instantly. 
    """,

    'author': "Xendit",
    'website': "https://xendit.co",

    # Categories can be used to filter modules in modules listing
    # Check https://github.com/odoo/odoo/blob/14.0/odoo/addons/base/data/ir_module_category_data.xml
    # for the full list
    'category': 'Sales',
    'version': '0.1',

    # any module necessary for this one to work correctly
    'depends': ['base', 'point_of_sale'],

    # always loaded
    'data': [
        'views/pos_payment_method_views.xml'
    ],
    'images': [
        'static/description/cover.png'
    ],
    'application': True,
    'installable': True,
    'assets': {
        # For Odoo 16.0
        'point_of_sale.assets': [
            'xendit_pos/static/**/*',
        ],
    }
}
```
