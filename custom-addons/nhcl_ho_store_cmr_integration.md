---
layout: custom-page
title: "Ho to Store Integration (nhcl_ho_store_cmr_integration)"
subtitle: "Custom addon — RetailEnterprise/HeadOffice/nhcl_ho_store_cmr_integration"
permalink: /custom-addons/nhcl_ho_store_cmr_integration/
nav_order: 0
nav_title: "Ho to Store Integration"
---
# Ho to Store Integration

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>nhcl_ho_store_cmr_integration</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/HeadOffice/nhcl_ho_store_cmr_integration</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><code>base</code>, <code>base_setup</code>, <code>cmr_customizations</code>, <code>account_accountant</code>, <code>stock_inventory_count_tus</code>, <code>product</code>, <code>stock</code>, <code>mail</code></div></div>
</div>

## Description

HO↔Store CMR integration — implements the outbox + ack pattern between Head Office and stores: replication log, ir.cron history, store-target scheduler, gift-card scheduler, loyalty programs, sale incentive, and product aging reports.

> **Deployment target:** Head Office.

## Manifest excerpt

```python
{
    "name": "Ho to Store Integration",
    "category": "Extra Tools",
    "version": "17.0",
    'sequence': 2,
    "author": "New Horizons Cybersoft Ltd",
    "website": "https://www.nhclindia.com/",
    "description": """Ho to Store CMR Integration""",
    "depends": ['base', 'base_setup', 'cmr_customizations', 'account_accountant','stock_inventory_count_tus','product','stock','mail',],
    "data": [
        'security/security.xml',
        'security/ir.model.access.csv',
        'data/sequence.xml',
        'data/store_target_sequence.xml',
        'views/product_template_view.xml',
        "views/hsn_wise_tax_report.xml",
        'views/designation_wise_incentive_report.xml',
        'views/summery_report_employee_wise.xml',
        'views/setu_sales_person_incentive_summary_report.xml',
        'views/setu_sales_person_incentive_detailed_report.xml',
        "views/nhcl_pos_order_hour_report.xml",
        'views/ho_store_transactions.xml',

        'views/product_category.xml',
        'views/product_attribute.xml',
        'views/hr_employee.xml',
        'views/product_product.xml',
        'views/contact.xml',
        'views/account_tax_view.xml',
        'views/account_account_view.xml',
        'views/loyalty_program_view.xml',
        'views/new_store_job_scheduler.xml',
        'views/gift_card_scheduler_action_view.xml',
        'views/replication_log_view.xml',
        'views/sale_incentive_view.xml',
        'views/partner_category.xml',
        'views/nhcl_product_uom.xml',
        'views/ir_cron_views.xml',
        'views/cv_ir_cron_history.xml',
        'views/product_aging_views.xml',




        'views/bulk_replication.xml',
        "views/nhcl_pos_delivery_order_hour_report.xml",
        "views/nhcl_site_wise_sale_report_view.xml",
        "views/setu_sales_person_incentive_aging_report.xml",
        "views/mop.xml",
        "views/tax_repo.xml",
        "views/lfb.xml",
        "report/mop.xml",
        "report/tax_report.xml",
        "repor
```
