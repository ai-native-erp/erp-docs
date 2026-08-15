---
layout: custom-page
title: "transport_dashboard (transport_dashboard)"
subtitle: "Custom addon — RetailEnterprise/Store/transport_dashboard"
permalink: /custom-addons/transport_dashboard/
nav_order: 0
nav_title: "transport_dashboard"
---
# transport_dashboard

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>transport_dashboard</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/transport_dashboard</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

Transport Dashboard — kanban of bale cards and Open Parcel tracking, feeding the last-scanned report requirement from retail reference §7.

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    'name': 'NHCL Transport Dashboard',
    'Version': '1.0',
    'category': 'Transport of Dashboard',
    'author': 'New Horizons CyberSoft Ltd',
    'company': 'New Horizons CyberSoft Ltd',
    'maintainer': 'New Horizons CyberSoft Ltd',
    'website': "https://www.nhclindia.com",
    'depends': [ 'web', 'stock','product'],
    'data': [
        # 'security/ir.model.access.csv',
        'views/stock.xml',
        'views/transport_dashboard_menu.xml',
    ],
    'assets': {
        'web.assets_backend': [
            'transport_dashboard/static/src/js/Transport_dashboard.js',
            'transport_dashboard/static/src/js/multiselect.js',
            'transport_dashboard/static/src/xml/Transport_dashboard.xml',
            'transport_dashboard/static/src/css/style.css',
        ],
    },
    'license': 'LGPL-3',
    'installable': True,
    'auto_install': False,
    'application': False,
}
```
