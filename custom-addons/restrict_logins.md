---
layout: custom-page
title: "restrict_logins (restrict_logins)"
subtitle: "Custom addon — RetailEnterprise/HeadOffice/restrict_logins"
permalink: /custom-addons/restrict_logins/
nav_order: 0
nav_title: "restrict_logins"
---
# restrict_logins

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>restrict_logins</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/HeadOffice/restrict_logins</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

Restrict Logins — IP/user-agent based login restrictions.

> **Deployment target:** Head Office.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
###############################################################################
#
#    Cybrosys Technologies Pvt. Ltd.
#
#    Copyright (C) 2024-TODAY Cybrosys Technologies(<https://www.cybrosys.com>)
#    Author: Cybrosys Technologies (odoo@cybrosys.com)
#
#    You can modify it under the terms of the GNU LESSER
#    GENERAL PUBLIC LICENSE (LGPL v3), Version 3.
#
#    This program is distributed in the hope that it will be useful,
#    but WITHOUT ANY WARRANTY; without even the implied warranty of
#    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#    GNU LESSER GENERAL PUBLIC LICENSE (LGPL v3) for more details.
#
#    You should have received a copy of the GNU LESSER GENERAL PUBLIC LICENSE
#    (LGPL v3) along with this program.
#    If not, see <http://www.gnu.org/licenses/>.
#
###############################################################################
{
    'name': 'Restrict Concurrent User Login',
    'version': '0.1',
    'category': 'Extra Tools',
    'summary': """Ensures restricted concurrent sessions, enforces user force
    logout, and automates session expiry for enhanced security.""",
    'description': """This module ensures security by restricting concurrent
    user sessions and provides the option for forced logout, It includes
    automatic session expiry after a set duration, managing user logins
    efficiently.""",
    'author': 'Cybrosys Techno Solutions',
    'company': 'Cybrosys Techno Solutions',
    'maintainer': 'Cybrosys Techno Solutions',
    'website': 'https://www.cybrosys.com',
    'depends':['base_setup'],
    'data': [
        'data/ir_cron_data.xml',
        'views/res_users_views.xml',
        'views/login_clear_session_template.xml',
        'views/res_config_settings_views.xml',
    ],
    'images': ['static/description/banner.jpg'],
    'license': 'LGPL-3',
    'installable': True,
    'auto_install': False,
    'application': False,
}
```
