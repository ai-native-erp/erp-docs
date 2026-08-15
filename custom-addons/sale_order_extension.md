---
layout: custom-page
title: "Sales Order Extension Examples (sale_order_extension)"
subtitle: "Custom addon — addons/sale_order_extension"
permalink: /custom-addons/sale_order_extension/
nav_order: 0
nav_title: "Sales Order Extension Examples"
---
# Sales Order Extension Examples

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>sale_order_extension</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>addons/sale_order_extension</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v">17.0.1.0.0</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><code>sale</code>, <code>mail</code>, <code>bus</code>, <code>web</code></div></div>
</div>

## Description

Sales Order Extension — custom addon in this repo demonstrating an end-to-end vertical slice: approval workflow, REST API, scheduled actions, jobs, record-event listeners, and OWL client behavior.

## Manifest excerpt

```python
{
    "name": "Sales Order Extension Examples",
    "summary": "Approval workflow, rules, REST API, record events, jobs, and client behavior",
    "version": "17.0.1.0.0",
    "category": "Sales/Sales",
    "license": "LGPL-3",
    "depends": ["sale", "mail", "bus", "web"],
    "data": [
        "security/sale_order_extension_security.xml",
        "views/sale_order_views.xml",
        "views/sale_order_workspace_views.xml",
        "data/ir_cron.xml",
    ],
    "assets": {
        "web.assets_backend": [
            "sale_order_extension/static/src/js/sale_order_client_service.js",
            "sale_order_extension/static/src/workspace/**/*",
        ],
    },
    "installable": True,
    "application": False,
}
```
