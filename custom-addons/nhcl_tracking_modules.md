---
layout: custom-page
title: "Tracking Modules (nhcl_tracking_modules)"
subtitle: "Custom addon — RetailEnterprise/Store/nhcl_tracking_modules"
permalink: /custom-addons/nhcl_tracking_modules/
nav_order: 0
nav_title: "Tracking Modules"
---
# Tracking Modules

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>nhcl_tracking_modules</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/nhcl_tracking_modules</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v">1.0</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><code>base</code></div></div>
</div>

## Description

Tracking Modules

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
{
    "name": "Tracking Modules",
    "version": "1.0",
    "sequence": 2,
    "author": "NHCL",
    "maintainer": "NHCL",
    "depends": ['base'],
    "external_dependencies": {"python": ["bs4"]},
    "data": [
        "security/ir.model.access.csv",
        "views/module_audit_log_views.xml",
    ],
    "license": "LGPL-3",
    "installable": True,
    "application": True,
    "auto_install": False,
}
```
