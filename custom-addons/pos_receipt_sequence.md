---
layout: custom-page
title: "pos_receipt_sequence (pos_receipt_sequence)"
subtitle: "Custom addon — RetailEnterprise/Store/pos_receipt_sequence"
permalink: /custom-addons/pos_receipt_sequence/
nav_order: 0
nav_title: "pos_receipt_sequence"
---
# pos_receipt_sequence

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>pos_receipt_sequence</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/pos_receipt_sequence</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

pos_receipt_sequence

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    'name': "POS Receipt Sequence",
    'version': '17.0.0.0',
    'depends': ['base', 'point_of_sale'],
    'data': [
        'views/res_config_settings.xml',
    ],
    'assets': {
        'point_of_sale._assets_pos': [
            'pos_receipt_sequence/static/src/app/db.js',
            'pos_receipt_sequence/static/src/app/pos_store.js',
            'pos_receipt_sequence/static/src/app/receipt/models.js',
            'pos_receipt_sequence/static/src/app/receipt/orderreceipt.js',
            'pos_receipt_sequence/static/src/app/receipt/paymentscreen.js',
            'pos_receipt_sequence/static/src/app/receipt/save_button.js',
        ],
    },
    'installable': True,
    'auto_install': False,
}
```
