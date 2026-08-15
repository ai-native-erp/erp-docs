---
layout: custom-page
title: "HSN Code Automation Management (hsn_code_automation_management)"
subtitle: "Custom addon — RetailEnterprise/Store/hsn_code_automation_management"
permalink: /custom-addons/hsn_code_automation_management/
nav_order: 0
nav_title: "HSN Code Automation Management"
---
# HSN Code Automation Management

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>hsn_code_automation_management</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/hsn_code_automation_management</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v">1.0</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><code>account</code>, <code>sale_management</code>, <code>purchase</code>, <code>l10n_in</code>, <code>l10n_in_edi</code>, <code>product</code></div></div>
</div>

## Description

HSN Code Automation — HSN/SAC master and tax-engine automation, providing the data-driven GST rule layer the retail reference §5.5 calls for.

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
{
    "name": "HSN Code Automation Management",
    "version": "1.0",
    "summary": "Simplify HSN code and GST integration for seamless product application and automated tax calculation, tailored to company categories and state regulations.",
    "sequence": 2,
    "category": "Account",
    "website": "https://www.vperfectcs.com",
    "author": "VperfectCS",
    "maintainer": "VperfectCS",
    "images": ["static/description/banner.jpg"],
    "depends": ["account", "sale_management", "purchase", "l10n_in", "l10n_in_edi",'product'],
    "external_dependencies": {"python": ["bs4"]},
    "data": [
        "security/ir.model.access.csv",
        "views/hsn_code_master_view.xml",
        "views/hsn_category_view.xml",
        "views/res_company_view.xml",
        "views/menu.xml",
    ],
    "license": "LGPL-3",
    "installable": True,
    "application": True,
    "auto_install": False,
    "price": 99,
    "currency": "USD",
}
```
