---
layout: custom-page
title: "web_listview_column_width_cr (web_listview_column_width_cr)"
subtitle: "Custom addon — RetailEnterprise/Store/web_listview_column_width_cr"
permalink: /custom-addons/web_listview_column_width_cr/
nav_order: 0
nav_title: "web_listview_column_width_cr"
---
# web_listview_column_width_cr

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>web_listview_column_width_cr</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/web_listview_column_width_cr</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

web_listview_column_width_cr

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
# Part of Odoo Module Developed by CandidRoot Solutions Pvt. Ltd.
# See LICENSE file for full copyright and licensing details.
{
    'name': 'List View Column width Adjustment',
    'version': '17.0.1.0',
    'summary': 'List View Column width Adjustment',
    'author': 'CandidRoot Solutions Pvt. Ltd.',
    'description': """
			This module allows user to adjustment of any list view column width.
    """,
    'website': 'www.candidroot.com',
    'depends': ['web'],
    'category': 'Extra Tools',
    'demo': [
    ],
    'assets': {
        'web.assets_backend': [
            '/web_listview_column_width_cr/static/src/js/list_renderer.js',
            '/web_listview_column_width_cr/static/src/scss/main.scss',
        ],
    },
    'images': ['static/description/banner.jpg'],
    'installable': True,
    'live_test_url': 'https://youtu.be/gE5j17aRXG8',
    'application': True,
    'auto_install': False,
    'license': 'LGPL-3',
}
```
