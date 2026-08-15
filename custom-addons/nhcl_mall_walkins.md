---
layout: custom-page
title: "nhcl_mall_walkins (nhcl_mall_walkins)"
subtitle: "Custom addon — RetailEnterprise/Store/nhcl_mall_walkins"
permalink: /custom-addons/nhcl_mall_walkins/
nav_order: 0
nav_title: "nhcl_mall_walkins"
---
# nhcl_mall_walkins

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>nhcl_mall_walkins</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/nhcl_mall_walkins</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

nhcl_mall_walkins

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
# Part of Odoo. See LICENSE file for full copyright and licensing details.

{
    'name': 'NHCL Walkin Report',
    'version': '1.0',
    'category': 'Point of Sale',
    'summary': 'Walkin report and Slot Master management for POS',
    'author': 'New Horizons CyberSoft Ltd',
    'company': 'New Horizons CyberSoft Ltd',
    'maintainer': 'New Horizons CyberSoft Ltd',
    'website': "https://www.nhclindia.com",
    'license': 'AGPL-3',
    'depends': ['point_of_sale'],
    'data': [
        'security/ir.model.access.csv',
        'views/menu.xml',
        'views/year_master_views.xml',
        'views/walkin_screen_views.xml',
        'views/walkin_sequence.xml',
        'views/day_reporting_views.xml',
        'views/hour_reporting_views.xml',
    ],
    'installable': True,
    'auto_install': False,
    'application': True,
}
```
