---
layout: custom-page
title: "logistic_screen (logistic_screen)"
subtitle: "Custom addon — RetailEnterprise/Store/logistic_screen"
permalink: /custom-addons/logistic_screen/
nav_order: 0
nav_title: "logistic_screen"
---
# logistic_screen

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>logistic_screen</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/logistic_screen</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

logistic_screen

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    'name': 'Logistic Screen',
    'version': '1.0',
    'category': 'Logistics',
    "author": "New Horizons Cybersoft Ltd",
    "website": "https://www.nhclindia.com/",
    'summary': 'Logistics',
    'description': """
This module contains all the common features of Transport and Check.
    """,
    'depends': ['purchase', 'base','nhcl_customizations','transport_dashboard'],

    'data': [
        'data/sequence.xml',
        'security/ir.model.access.csv',
        'views/logistic_screen_entry.xml',
        'views/transports_check_view.xml',
        'views/delivery_check_view.xml',
        'views/open_parel.xml',
    ],
    'assets': {
            'web.assets_backend': [
                'logistic_screen/static/src/js/logistic_dashboard.js',
                'logistic_screen/static/src/xml/logistic_dashboard.xml',
                'logistic_screen/static/src/css/logistic_dashboard.css',
            ],
        },

    'installable': True,
    'application': True,
    'auto_install': False,
    'license': 'LGPL-3',
}
```
