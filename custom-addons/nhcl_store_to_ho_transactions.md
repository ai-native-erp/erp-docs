---
layout: custom-page
title: "Store to HO Transactions (nhcl_store_to_ho_transactions)"
subtitle: "Custom addon — RetailEnterprise/Store/nhcl_store_to_ho_transactions"
permalink: /custom-addons/nhcl_store_to_ho_transactions/
nav_order: 0
nav_title: "Store to HO Transactions"
---
# Store to HO Transactions

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>nhcl_store_to_ho_transactions</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/nhcl_store_to_ho_transactions</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><code>base</code>, <code>base_setup</code>, <code>account</code>, <code>nhcl_customizations</code>, <code>stock</code></div></div>
</div>

## Description

Store→HO transaction replication — symmetric counterpart of the HO→Store integration; uploads store-originated transactions through the same outbox + ack flow.

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    "name": "Store to HO Transactions",
    "category": "Extra Tools",
    "version": "17.0",
    "author": "New Horizons Cybersoft Ltd",
    "website": "https://www.nhclindia.com/",
    "description": """Ho to Store CMR Integration""",
    "depends": ['base', 'base_setup','account','nhcl_customizations','stock'],
    "data": [
        'security/ir.model.access.csv',
        'security/security_groups.xml',
        'data/ir_sequence.xml',
        'views/store_eod_transaction_job_view.xml',
        'views/store_job_log_view.xml',
        'views/purchase_request_view.xml',
        'views/store_replenishment_views.xml',
        'views/pos_order_view.xml',
    ],
    "demo": [],
    "application": False,
    "installable": True,
    "auto-intall": False,
    'license': 'LGPL-3',
}
```
