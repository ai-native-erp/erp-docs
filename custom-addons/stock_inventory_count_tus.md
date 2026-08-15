---
layout: custom-page
title: "Stock Inventory Counting (stock_inventory_count_tus)"
subtitle: "Custom addon — RetailEnterprise/Store/stock_inventory_count_tus"
permalink: /custom-addons/stock_inventory_count_tus/
nav_order: 0
nav_title: "Stock Inventory Counting"
---
# Stock Inventory Counting

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>stock_inventory_count_tus</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/stock_inventory_count_tus</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">OPL-1</div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><code>stock</code>, <code>product_expiry</code>, <code>nhcl_customizations</code></div></div>
</div>

## Description

Stock Inventory Count (TUS) — physical-inventory count sheet for stock-take reconciliation; events post into the stock ledger, not direct on-hand edits.

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    "name": "Stock Inventory Counting",
    "version": "17.0",
    "author": "TechUltra Solutions Private Limited",
    'company': 'TechUltra Solutions Private Limited',
    "website": "https://www.techultrasolutions.com/",
    "category": "Inventory",
    "summary": """
        Inventory counting is a major operation in inventory management as daily basis for 3PL warehouse and
        Normal warehouse, Odoo provides this feature with
        limited functionality. Using the tech-ultra "Advance Inventory Counting" app, you may simplify
        inventory count with the responsible person. Scroll down to know more about our app.
    """,
    "description": """
        Stock inventory count
        Inventory counting
        Stock Count
        Inventory counting Report
        Stock Inventory Report
        Odoo Erp Stock Report
        Stock Report.
    """,
    "depends": ["stock", "product_expiry","nhcl_customizations"],
    "data": [
        "security/ir.model.access.csv",
        "views/stock_adjustment_view.xml",
        "views/stock_inventory_views.xml",
        "views/inventory_scan_report_views.xml",
        "views/stock_inventory_audit_plan_log_view.xml",
    ],
    "images": ["static/description/main_screen.gif"],
    "price": 28.99,
    "currency": "USD",
    "installable": True,
    "application": True,
    "license": "OPL-1",
}
```
