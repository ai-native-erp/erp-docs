---
layout: custom-page
title: "Custom-Header (Custom-Header)"
subtitle: "Custom addon — RetailEnterprise/Store/Custom-Header"
permalink: /custom-addons/Custom-Header/
nav_order: 0
nav_title: "Custom-Header"
---
# Custom-Header

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>Custom-Header</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/Custom-Header</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

Custom-Header

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
{
    'name': "Header Custom",

    'summary': "Short (1 phrase/line) summary of the module's purpose",

    'description': """
For creating the custom header part for general use.
    """,

    'author': "Capchi079",
    'website': "https://www.github.com/Capchi079",

    # Categories can be used to filter modules in modules listing
    # Check https://github.com/odoo/odoo/blob/15.0/odoo/addons/base/data/ir_module_category_data.xml
    # for the full list
    'category': 'Uncategorized',
    'version': '0.1',

    # any module necessary for this one to work correctly
    'depends': ['base'],

    # always loaded
    'data': [
        # 'security/ir.model.access.csv',
        'views/views.xml',
        'views/templates.xml',
    ],
    # only loaded in demonstration mode
    'demo': [
        'demo/demo.xml',
    ],
    'license': 'LGPL-3',
}
```
