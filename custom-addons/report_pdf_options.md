---
layout: custom-page
title: "report_pdf_options (report_pdf_options)"
subtitle: "Custom addon — RetailEnterprise/Store/report_pdf_options"
permalink: /custom-addons/report_pdf_options/
nav_order: 0
nav_title: "report_pdf_options"
---
# report_pdf_options

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>report_pdf_options</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/report_pdf_options</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

report_pdf_options

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
{
    'name': 'NHCL report options',
    'summary': """shows a modal window with options for printing, downloading or opening pdf reports""",
    'description': """
        Choose one of the following options when printing a pdf report:
        - print. print the pdf report directly with the browser
        - download. download the pdf report on your computer
        - open. open the pdf report in a new tab
        You can also set a default options for each report
    """,
    'author': 'Luis Rodrigo Mejia Mateus',
    'category': 'Productivity',
    'depends': ['web'],
    'data': [
        'views/ir_actions_report.xml',
    ],
    'installable': True,
    'auto_install': False,
    'license': 'LGPL-3',
    'assets': {
        'web.assets_backend': [
            'report_pdf_options/static/src/js/PdfOptionsModal.js',
            'report_pdf_options/static/src/js/qwebactionmanager.js',
            'report_pdf_options/static/src/**/*.xml'
        ]
    }
}
```
