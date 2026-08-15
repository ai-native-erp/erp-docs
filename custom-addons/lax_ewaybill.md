---
layout: custom-page
title: "lax_ewaybill (lax_ewaybill)"
subtitle: "Custom addon — RetailEnterprise/Store/lax_ewaybill"
permalink: /custom-addons/lax_ewaybill/
nav_order: 0
nav_title: "lax_ewaybill"
---
# lax_ewaybill

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>lax_ewaybill</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/lax_ewaybill</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

LAX E-Way Bill — Indian e-way bill generation/integration for inter-state transfers, GRN-linked invoices, and batch transfer out (with intra-state consolidation).

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    'name' : 'E-Way Bill for India',
    'version' : '17.0',
    'summary': ' 5 hr support and 500 Bill credit ',
    'sequence': -100,
    'description': """ 5 hr support and 500 Bill credit """,
    'author': 'Laxicon Solution',
    'images' : ['static/description/icon.png'],
    'category': 'Invoice',
    'website': 'https://laxicon.in',
    'depends' : ['account', 'l10n_in', 'base', 'stock', 'sale_management'],
    'data': [
        'security/ir.model.access.csv',
        'data/sequence_data.xml',
        'data/error_code.xml',
        'data/ewaybill_type_data.xml',
        'views/res_company.xml',
        'views/eway_bill_view.xml',
        # 'views/stock_picking_view.xml',
        # 'views/sale_order_view.xml',
        # 'views/account_move_view.xml',
        'report/eway_bill.xml',
        'report/eway_bill_action.xml',
        'wizard/success_message.xml',
        'wizard/update_vehicle_no.xml',
        'wizard/cancel_ewbno_wiz.xml',
        'wizard/update_transporter.xml',
        'wizard/extend_ewaybill.xml',
        'wizard/regenerate_consolidated_bill.xml',
        'wizard/multi_vehicle_movement.xml',
        'wizard/add_multi_vehicle.xml',
        'wizard/change_multi_vehicle.xml',
    ],
    'installable': True,
    'application': True,
    'license': 'OPL-1',
    'price':99.0,
    'currency':'USD',
}
```
