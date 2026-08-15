---
layout: custom-page
title: "License Key Generater for store (user_implementation)"
subtitle: "Custom addon — RetailEnterprise/Store/user_implementation"
permalink: /custom-addons/user_implementation/
nav_order: 0
nav_title: "License Key Generater for store"
---
# License Key Generater for store

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>user_implementation</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/user_implementation</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><code>base</code>, <code>nhcl_customizations</code>, <code>hr</code>, <code>web</code></div></div>
</div>

## Description

License Key Generater for store

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    "name": "License Key Generater for store",
    "depends": [
        "base",'nhcl_customizations','hr','web'
    ],
    "data": [
        "security/ir.model.access.csv",
        "views/user_license_screen_views.xml",
        'views/res_users_views.xml',
        # 'views/login_template_view.xml',
        'data/ir_sequence_data.xml',
        'wizard/license_key_user_wizard_view.xml',
        'data/ir_cron.xml',

    ],
    'license': 'LGPL-3',


}
```
