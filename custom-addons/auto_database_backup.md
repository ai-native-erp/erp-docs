---
layout: custom-page
title: "auto_database_backup (auto_database_backup)"
subtitle: "Custom addon — vendor-addons/auto_database_backup"
permalink: /custom-addons/auto_database_backup/
nav_order: 0
nav_title: "auto_database_backup"
---
# auto_database_backup

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>auto_database_backup</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>vendor-addons/auto_database_backup</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

Auto Database Backup — third-party vendor addon (`vendor-addons/auto_database_backup`) for scheduled PostgreSQL backups and restore procedures.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
###############################################################################
#
#    Cybrosys Technologies Pvt. Ltd.
#
#    Copyright (C) 2023-TODAY Cybrosys Technologies(<https://www.cybrosys.com>)
#    Author: Cybrosys Techno Solutions (odoo@cybrosys.com)
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
    'name': "Automatic Database Backup To Local Server, Remote Server,"
            "Google Drive, Dropbox, Onedrive, Nextcloud and Amazon S3 Odoo17",
    'version': '17.0.6.0.1',
    'live_test_url': 'https://youtu.be/Q2yMZyYjuTI',
    'category': 'Extra Tools',
    'summary': 'Odoo Database Backup, Automatic Backup, Database Backup, Automatic Backup,Database auto-backup, odoo backup'
               'google drive, dropbox, nextcloud, amazon S3, onedrive or '
               'remote server, Odoo17, Backup, Database, Odoo Apps',
    'description': 'Odoo Database Backup, Database Backup, Automatic Backup, automatic database backup, odoo17, odoo apps,backup, automatic backup,odoo17 automatic database backup,backup google drive,backup dropbox, backup nextcloud, backup amazon S3, backup onedrive',
    'author': "Cybrosys Techno Solutions",
    'company': 'Cybrosys Techno Solutions',
    'maintainer': 'Cybrosys Techno Solutions',
    'website': "https://www.cybrosys.com",
    'depends': ['base', 'mail'],
    'data': [
        'security/ir.model.access.csv',
        'data/
```
