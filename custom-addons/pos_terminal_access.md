---
layout: custom-page
title: "pos_terminal_access (pos_terminal_access)"
subtitle: "Custom addon — RetailEnterprise/Store/pos_terminal_access"
permalink: /custom-addons/pos_terminal_access/
nav_order: 0
nav_title: "pos_terminal_access"
---
# pos_terminal_access

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>pos_terminal_access</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/pos_terminal_access</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

pos_terminal_access

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
{
    'name': 'POS Terminal Access',
    'summary': "Pos Terminal Access System based",
    'description': 'Pos Terminal Access System based',
    'author': 'Anil Nhcl',
    'category': 'Point of Sale',
    'version': '17.0.0.1.1',
    'depends': ['point_of_sale'],
    'data': [
        'views/pos_config_view.xml',
    ],
    'license': "OPL-1",

    'installable': True,
    'application': True,

    'images': ['static/description/banner.png'],
}
```
