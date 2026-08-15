---
layout: custom-page
title: "Odoo Rest Api (odoo_rest_nhcl)"
subtitle: "Custom addon — RetailEnterprise/Store/odoo_rest_nhcl"
permalink: /custom-addons/odoo_rest_nhcl/
nav_order: 0
nav_title: "Odoo Rest Api"
---
# Odoo Rest Api

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>odoo_rest_nhcl</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/odoo_rest_nhcl</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">Other proprietary</div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><code>base</code></div></div>
</div>

## Description

Odoo Rest Api

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    "name": "Odoo Rest Api",
    "summary": """The module create RESTful API for Odoo and allows you to access and modify data using HTTP requests to manage fetch and manage data from the Odoo.""",
    "category": "Extra Tools",
    "version": "17.0",
    "author": "New Horizons Cybersoft Ltd",
    "license": "Other proprietary",
    "website": "https://www.nhclindia.com/",
    "description": """Odoo Rest Api
Add record to database
Delete record to Database
Modify data in Odoo database
Use HTTP to modify data
RESTful API in Odoo
Use HTTP requests to fetch data in Odoo""",
    # "live_test_url"        :  "https://store.webkul.com/Odoo-REST-API.html#",
    "depends": ['base'],
    "data": [
        'security/ir.model.access.csv',
        'views/rest_api_views.xml',
        'views/templates.xml',
    ],
    "demo": ['demo/demo.xml'],
    "images": ['static/description/odoo_restapi_banner.png'],
    "application": True,
    "installable": True,
    "price": 94,
    "currency": "USD",
}
```
