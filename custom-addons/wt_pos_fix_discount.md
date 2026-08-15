---
layout: custom-page
title: "Pos Fix Discount (wt_pos_fix_discount)"
subtitle: "Custom addon — RetailEnterprise/Store/wt_pos_fix_discount"
permalink: /custom-addons/wt_pos_fix_discount/
nav_order: 0
nav_title: "Pos Fix Discount"
---
# Pos Fix Discount

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>wt_pos_fix_discount</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/wt_pos_fix_discount</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v">17.0.0.1</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">OPL-1</div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><code>base</code>, <code>point_of_sale</code></div></div>
</div>

## Description

Pos Fix Discount

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
{
    "name": "Pos Fix Discount",
    "version": "17.0.0.1",
    "category": "Sales/Point of Sale",
    "summary": "Pos Fix Discount",
    "description": """Pos Fix Discount""",
    "author": "Warlock Technologies",
    "website": "http://warlocktechnologies.com",
    "support": "info@warlocktechnologies.com",
    "depends": ['base','point_of_sale'],
    "data": [
        "views/pos_order.xml",
    ],
    'assets':{
        'point_of_sale._assets_pos': [
            "/wt_pos_fix_discount/static/src/apps/screens/product_screen/fix_discount_button/fix_discount_button.xml",
            "/wt_pos_fix_discount/static/src/apps/screens/product_screen/fix_discount_button/fix_discount_button.js",
            "/wt_pos_fix_discount/static/src/apps/store/models.js",
            "/wt_pos_fix_discount/static/src/apps/screens/product_screen/orderline/orderline.xml",
        ],
    },
    "images": ["static/images/screen_image.png"],
    "price": 0.0,
    "currency": "USD",
    'sequence': 4,
    "application": True,
    "installable": True,
    "auto_install": False,
    "image": [""],
    "license": "OPL-1",
}
```
