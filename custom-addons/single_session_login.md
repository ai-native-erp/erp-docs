---
layout: custom-page
title: "Single Session Login (single_session_login)"
subtitle: "Custom addon — RetailEnterprise/HeadOffice/single_session_login"
permalink: /custom-addons/single_session_login/
nav_order: 0
nav_title: "Single Session Login"
---
# Single Session Login

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>single_session_login</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/HeadOffice/single_session_login</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v">0.1</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><code>base</code>, <code>web</code></div></div>
</div>

## Description

Single-Session Login — restricts users to one concurrent active session, tightening the access-control surface called for in retail reference §10.

> **Deployment target:** Head Office.

## Manifest excerpt

```python
{
    "name": "Single Session Login",
    "summary": "Control concurrent user logins with flexible single-session management.",
    "description": """
Single Session Login allows administrators to restrict users to a single active session
while providing the flexibility to allow multiple sessions for selected users.
Improve security, prevent account sharing, and manage user access across devices.
""",
    "version": "0.1",
    "category": "Administration",
    "license": "LGPL-3",

    "author": "Deepak Verma",
    "maintainer": "Deepak Verma",
    "company": "Deecoders",

    "website": "https://www.linkedin.com/in/deepak-verma-07144012a",

    "support": "dpakverma789@gmail.com",

    "depends": [
        "base",
        "web",
    ],

    "data": [
        "views/res_users_views.xml",
    ],

    "assets": {
        "web.assets_backend": [
            "single_session_login/static/src/js/session_checker.js",
        ],
    },

    "images": [
        "static/description/banner.png",
    ],

    "installable": True,
    "application": False,
    "auto_install": False,

}
```
