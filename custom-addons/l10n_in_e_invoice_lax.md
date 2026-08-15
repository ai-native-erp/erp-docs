---
layout: custom-page
title: "l10n_in_e_invoice_lax (l10n_in_e_invoice_lax)"
subtitle: "Custom addon — RetailEnterprise/Store/l10n_in_e_invoice_lax"
permalink: /custom-addons/l10n_in_e_invoice_lax/
nav_order: 0
nav_title: "l10n_in_e_invoice_lax"
---
# l10n_in_e_invoice_lax

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>l10n_in_e_invoice_lax</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/l10n_in_e_invoice_lax</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

Indian E-Invoice (LAX) — IRN generation alongside E-Way Bill for the same transfer/sale events, with TO/GRN/PO reference carry-through.

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
##############################################################################
#
#    OpenERP, Open Source Management Solution
#    Copyright (C) 2015 Laxicon Solution (<http://www.laxicon.in>).
#
#    For Module Support : info@laxicon.in
#
##############################################################################
{
    'name' : 'E-Invoice for India with 5 hrs support and 500 E-Invoice Credit',
    'version' : '17.0',
    'summary': ' 5 hr Support and 500 E-Invoice Credit ',
    'sequence': -100,
    'description': """ 5 hr Support and 500 E-Invoice Credit """,
    'author': 'Laxicon Solution',
    'images' : ['static/description/banner.png'],
    'category': 'Invoice',
    'website': 'https://laxicon.in',
    'depends' : ['account', 'l10n_in', 'base'],
    'data': [
        'security/ir.model.access.csv',
        'data/port_code.xml',
        'report/einvoice.xml',
        'views/account_move_view.xml',
        'views/res_compnay.xml',
        'wizard/success_message.xml',
        'wizard/cancel_irn_wiz.xml',
    ],
    'installable': True,
    'application': True,
    'license': 'OPL-1',
    'price':95.0,
    'currency':'USD',
    'maintainer': 'Laxicon Solution', 
    'support': 'info@laxicon.in',
}
```
