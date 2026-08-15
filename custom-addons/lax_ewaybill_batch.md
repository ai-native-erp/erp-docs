---
layout: custom-page
title: "lax_ewaybill_batch (lax_ewaybill_batch)"
subtitle: "Custom addon — RetailEnterprise/Store/lax_ewaybill_batch"
permalink: /custom-addons/lax_ewaybill_batch/
nav_order: 0
nav_title: "lax_ewaybill_batch"
---
# lax_ewaybill_batch

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>lax_ewaybill_batch</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/lax_ewaybill_batch</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

LAX E-Way Bill batch — batch-level e-way bill consolidation for intra-state batch transfers (closing the gap noted in the retail reference doc §4.1).

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    'name': 'E-Way Bill Batch and Actions',
    'version': '17.0',
    'summary': 'Batch creation and server actions for E-Way Bill',
    'sequence': -99,
    'description': """Batch creation and server actions for E-Way Bill""",
    'author': 'Laxicon Solution',
    'category': 'Warehouse',
    'website': 'https://laxicon.in',
    'depends': ['lax_ewaybill', 'stock_picking_batch'],
    'data': [
        'views/stock_picking_view.xml',
    ],
    'installable': True,
    'application': False,
    'license': 'OPL-1',
}
```
