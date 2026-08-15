---
layout: page
title: "Modules"
subtitle: "Every Odoo 17 module in this repo, grouped by retail-ERP domain."
permalink: /modules/
nav_order: 5
---
This index covers **609** Odoo 17 modules pulled from `agents/modules/generated/*.yaml`. Every module has its own page with dependencies, model coverage, related agents, and conversation learnings.

## Group summary

| Group | Count |
|---|---|
| [Core](#core) | 0 |
| [Sales](#sales) | 0 |
| [Purchase](#purchase) | 7 |
| [Stock & Inventory](#stock-and-inventory) | 9 |
| [Accounting](#accounting) | 0 |
| [Point of Sale](#point-of-sale) | 0 |
| [Product / Master data](#product---master-data) | 9 |
| [Manufacturing](#manufacturing) | 0 |
| [HR / Payroll](#hr---payroll) | 27 |
| [EDI / e-Invoice / e-Way](#edi---e-invoice---e-way) | 0 |
| [Localization](#localization) | 0 |
| [Website / eCommerce](#website---ecommerce) | 59 |
| [Marketing / Events](#marketing---events) | 0 |
| [Knowledge / Helpdesk](#knowledge---helpdesk) | 1 |
| [Reporting / Spreadsheet](#reporting---spreadsheet) | 0 |
| [Other](#other) | 130 |

## Core

<a id="core"></a>

24 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="auth_ldap/"><code>auth_ldap</code></a></td><td>Authentication via LDAP</td><td>platform_core</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="auth_oauth/"><code>auth_oauth</code></a></td><td>OAuth2 Authentication</td><td>platform_core</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="auth_password_policy/"><code>auth_password_policy</code></a></td><td>Password Policy</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="auth_password_policy_portal/"><code>auth_password_policy_portal</code></a></td><td>Password Policy support for Signup</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="auth_password_policy_signup/"><code>auth_password_policy_signup</code></a></td><td>Password Policy support for Signup</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="auth_signup/"><code>auth_signup</code></a></td><td>Signup</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="auth_totp/"><code>auth_totp</code></a></td><td>Two-Factor Authentication (TOTP)</td><td>platform_core</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="auth_totp_mail/"><code>auth_totp_mail</code></a></td><td>2FA Invite mail</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="auth_totp_mail_enforce/"><code>auth_totp_mail_enforce</code></a></td><td>2FA by mail</td><td>platform_core</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="auth_totp_portal/"><code>auth_totp_portal</code></a></td><td>TOTPortal</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="base/"><code>base</code></a></td><td>Base</td><td>platform_core</td><td>LGPL-3</td><td>114</td></tr>
<tr><td><a href="base_address_extended/"><code>base_address_extended</code></a></td><td>Extended Addresses</td><td>platform_core</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="base_automation/"><code>base_automation</code></a></td><td>Automation Rules</td><td>platform_core</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="base_geolocalize/"><code>base_geolocalize</code></a></td><td>Partners Geolocation</td><td>platform_core</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="base_iban/"><code>base_iban</code></a></td><td>IBAN Bank Accounts</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="base_import/"><code>base_import</code></a></td><td>Base import</td><td>platform_core</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="base_import_module/"><code>base_import_module</code></a></td><td>Base import module</td><td>platform_core</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="base_install_request/"><code>base_install_request</code></a></td><td>Base - Module Install Request</td><td>platform_core</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="base_setup/"><code>base_setup</code></a></td><td>Initial Setup Tools</td><td>platform_core</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="base_sparse_field/"><code>base_sparse_field</code></a></td><td>Sparse Fields</td><td>platform_core</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="base_vat/"><code>base_vat</code></a></td><td>VAT Number Validation</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="bus/"><code>bus</code></a></td><td>IM Bus</td><td>platform_core</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="mail/"><code>mail</code></a></td><td>Discuss</td><td>platform_core</td><td>LGPL-3</td><td>56</td></tr>
<tr><td><a href="web/"><code>web</code></a></td><td>Web</td><td>platform_core</td><td>LGPL-3</td><td>2</td></tr>
</tbody></table>

## Sales

<a id="sales"></a>

39 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="sale/"><code>sale</code></a></td><td>Sales</td><td>sales_crm</td><td>LGPL-3</td><td>9</td></tr>
<tr><td><a href="sale_async_emails/"><code>sale_async_emails</code></a></td><td>Sales - Async Emails</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_crm/"><code>sale_crm</code></a></td><td>Opportunity to Quotation</td><td>sales_crm</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="sale_expense/"><code>sale_expense</code></a></td><td>Sales Expense</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_expense_margin/"><code>sale_expense_margin</code></a></td><td>Sales Expense Margin</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_loyalty/"><code>sale_loyalty</code></a></td><td>Sale Loyalty</td><td>sales_crm</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="sale_loyalty_delivery/"><code>sale_loyalty_delivery</code></a></td><td>Sale Loyalty - Delivery</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_management/"><code>sale_management</code></a></td><td>Sales</td><td>sales_crm</td><td>LGPL-3</td><td>4</td></tr>
<tr><td><a href="sale_margin/"><code>sale_margin</code></a></td><td>Margins in Sales Orders</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_mrp/"><code>sale_mrp</code></a></td><td>Sales and MRP Management</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_mrp_margin/"><code>sale_mrp_margin</code></a></td><td>Sale Mrp Margin</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_order_extension/"><code>sale_order_extension</code></a></td><td>Sales Order Extension Examples</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_pdf_quote_builder/"><code>sale_pdf_quote_builder</code></a></td><td>Sales PDF Quotation Builder</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_product_configurator/"><code>sale_product_configurator</code></a></td><td>Sale Product Configurator</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_product_matrix/"><code>sale_product_matrix</code></a></td><td>Sale Matrix</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_project/"><code>sale_project</code></a></td><td>Sales - Project</td><td>sales_crm</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="sale_project_stock/"><code>sale_project_stock</code></a></td><td>Sale Project - Sale Stock</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_purchase/"><code>sale_purchase</code></a></td><td>Sale Purchase</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_purchase_stock/"><code>sale_purchase_stock</code></a></td><td>MTO Sale <-> Purchase</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_service/"><code>sale_service</code></a></td><td>Sales - Service</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_sms/"><code>sale_sms</code></a></td><td>Sale - SMS</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_stock/"><code>sale_stock</code></a></td><td>Sales and Warehouse Management</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_stock_margin/"><code>sale_stock_margin</code></a></td><td>Sale Stock Margin</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sale_timesheet/"><code>sale_timesheet</code></a></td><td>Sales Timesheet</td><td>sales_crm</td><td>LGPL-3</td><td>4</td></tr>
<tr><td><a href="sale_timesheet_margin/"><code>sale_timesheet_margin</code></a></td><td>Service Margins in Sales Orders</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_account/"><code>spreadsheet_dashboard_account</code></a></td><td>Spreadsheet dashboard for accounting</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_event_sale/"><code>spreadsheet_dashboard_event_sale</code></a></td><td>Spreadsheet dashboard for events</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_hr_expense/"><code>spreadsheet_dashboard_hr_expense</code></a></td><td>Spreadsheet dashboard for expenses</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_hr_timesheet/"><code>spreadsheet_dashboard_hr_timesheet</code></a></td><td>Spreadsheet dashboard for time sheets</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_im_livechat/"><code>spreadsheet_dashboard_im_livechat</code></a></td><td>Spreadsheet dashboard for live chat</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_pos_hr/"><code>spreadsheet_dashboard_pos_hr</code></a></td><td>Spreadsheet dashboard for point of sale</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_purchase/"><code>spreadsheet_dashboard_purchase</code></a></td><td>Spreadsheet dashboard for purchases</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_purchase_stock/"><code>spreadsheet_dashboard_purchase_stock</code></a></td><td>Spreadsheet dashboard for purchases</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_sale/"><code>spreadsheet_dashboard_sale</code></a></td><td>Spreadsheet dashboard for sales</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_sale_timesheet/"><code>spreadsheet_dashboard_sale_timesheet</code></a></td><td>Spreadsheet dashboard for time sheets</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_stock_account/"><code>spreadsheet_dashboard_stock_account</code></a></td><td>Spreadsheet dashboard for stock</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_website_sale/"><code>spreadsheet_dashboard_website_sale</code></a></td><td>Spreadsheet dashboard for eCommerce</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard_website_sale_slides/"><code>spreadsheet_dashboard_website_sale_slides</code></a></td><td>Spreadsheet dashboard for eLearning</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_sale/"><code>website_sale</code></a></td><td>eCommerce</td><td>website_ecommerce</td><td>LGPL-3</td><td>8</td></tr>
</tbody></table>

## Purchase

<a id="purchase"></a>

7 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="purchase/"><code>purchase</code></a></td><td>Purchase</td><td>inventory_purchase</td><td>LGPL-3</td><td>7</td></tr>
<tr><td><a href="purchase_mrp/"><code>purchase_mrp</code></a></td><td>Purchase and MRP Management</td><td>inventory_purchase</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="purchase_product_matrix/"><code>purchase_product_matrix</code></a></td><td>Purchase Matrix</td><td>inventory_purchase</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="purchase_requisition/"><code>purchase_requisition</code></a></td><td>Purchase Agreements</td><td>inventory_purchase</td><td>LGPL-3</td><td>6</td></tr>
<tr><td><a href="purchase_requisition_sale/"><code>purchase_requisition_sale</code></a></td><td>Purchase Requisition Sale</td><td>inventory_purchase</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="purchase_requisition_stock/"><code>purchase_requisition_stock</code></a></td><td>Purchase Requisition Stock</td><td>inventory_purchase</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="purchase_stock/"><code>purchase_stock</code></a></td><td>Purchase Stock</td><td>inventory_purchase</td><td>LGPL-3</td><td>3</td></tr>
</tbody></table>

## Stock & Inventory

<a id="stock"></a>

9 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="delivery/"><code>delivery</code></a></td><td>Delivery Costs</td><td>inventory_purchase</td><td>LGPL-3</td><td>4</td></tr>
<tr><td><a href="stock/"><code>stock</code></a></td><td>Inventory</td><td>inventory_purchase</td><td>LGPL-3</td><td>53</td></tr>
<tr><td><a href="stock_account/"><code>stock_account</code></a></td><td>WMS Accounting</td><td>inventory_purchase</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="stock_delivery/"><code>stock_delivery</code></a></td><td>Delivery - Stock</td><td>inventory_purchase</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="stock_dropshipping/"><code>stock_dropshipping</code></a></td><td>Drop Shipping</td><td>inventory_purchase</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="stock_landed_costs/"><code>stock_landed_costs</code></a></td><td>WMS Landed Costs</td><td>inventory_purchase</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="stock_landed_costs_company/"><code>stock_landed_costs_company</code></a></td><td>Landed Costs for company's branches</td><td>inventory_purchase</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="stock_picking_batch/"><code>stock_picking_batch</code></a></td><td>Warehouse Management: Batch Transfer</td><td>inventory_purchase</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="stock_sms/"><code>stock_sms</code></a></td><td>Stock - SMS</td><td>inventory_purchase</td><td>LGPL-3</td><td>1</td></tr>
</tbody></table>

## Accounting

<a id="accounting"></a>

22 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="account/"><code>account</code></a></td><td>Invoicing</td><td>accounting</td><td>LGPL-3</td><td>53</td></tr>
<tr><td><a href="account_add_gln/"><code>account_add_gln</code></a></td><td>Add Partner GLN</td><td>accounting</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="account_audit_trail/"><code>account_audit_trail</code></a></td><td>Account Audit Trail</td><td>accounting</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="account_check_printing/"><code>account_check_printing</code></a></td><td>Check Printing Base</td><td>accounting</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="account_debit_note/"><code>account_debit_note</code></a></td><td>Debit Notes</td><td>accounting</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="account_debit_note_sequence/"><code>account_debit_note_sequence</code></a></td><td>Debit Note Sequence</td><td>accounting</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="account_edi/"><code>account_edi</code></a></td><td>Import/Export Invoices From XML/PDF</td><td>accounting</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="account_edi_proxy_client/"><code>account_edi_proxy_client</code></a></td><td>Proxy features for account_edi</td><td>accounting</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="account_edi_ubl_cii/"><code>account_edi_ubl_cii</code></a></td><td>Import/Export electronic invoices with UBL/CII</td><td>accounting</td><td>LGPL-3</td><td>10</td></tr>
<tr><td><a href="account_edi_ubl_cii_tax_extension/"><code>account_edi_ubl_cii_tax_extension</code></a></td><td>Tax extension for UBL/CII</td><td>accounting</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="account_fleet/"><code>account_fleet</code></a></td><td>Accounting/Fleet bridge</td><td>accounting</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="account_lock/"><code>account_lock</code></a></td><td>Irreversible Lock Date</td><td>accounting</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="account_payment/"><code>account_payment</code></a></td><td>Payment - Account</td><td>accounting</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="account_payment_term/"><code>account_payment_term</code></a></td><td>Payment Term - Days end of month on the</td><td>accounting</td><td>OEEL-1</td><td>0</td></tr>
<tr><td><a href="account_peppol/"><code>account_peppol</code></a></td><td>Peppol</td><td>accounting</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="account_peppol_response/"><code>account_peppol_response</code></a></td><td>Peppol Business Response</td><td>accounting</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="account_peppol_selfbilling/"><code>account_peppol_selfbilling</code></a></td><td>Peppol Self Billing</td><td>accounting</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="account_qr_code_emv/"><code>account_qr_code_emv</code></a></td><td>account_qr_code_emv</td><td>accounting</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="account_qr_code_sepa/"><code>account_qr_code_sepa</code></a></td><td>Account SEPA QR Code</td><td>accounting</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="account_tax_python/"><code>account_tax_python</code></a></td><td>Define Taxes as Python Code</td><td>accounting</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="account_test/"><code>account_test</code></a></td><td>Accounting Consistency Tests</td><td>accounting</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="account_update_tax_tags/"><code>account_update_tax_tags</code></a></td><td>Account - Allow updating tax grids</td><td>accounting</td><td>LGPL-3</td><td>1</td></tr>
</tbody></table>

## Point of Sale

<a id="pos"></a>

30 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="point_of_sale/"><code>point_of_sale</code></a></td><td>Point of Sale</td><td>point_of_sale</td><td>LGPL-3</td><td>19</td></tr>
<tr><td><a href="pos_adyen/"><code>pos_adyen</code></a></td><td>POS Adyen</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_discount/"><code>pos_discount</code></a></td><td>Point of Sale Discounts</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_epson_printer/"><code>pos_epson_printer</code></a></td><td>POS Epson Printer</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_hr/"><code>pos_hr</code></a></td><td>POS - HR</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_hr_restaurant/"><code>pos_hr_restaurant</code></a></td><td>POS HR Restaurant</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_loyalty/"><code>pos_loyalty</code></a></td><td>Point of Sale - Coupons & Loyalty</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_mercado_pago/"><code>pos_mercado_pago</code></a></td><td>POS Mercado Pago</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_mercury/"><code>pos_mercury</code></a></td><td>Vantiv Payment Services</td><td>point_of_sale</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="pos_mrp/"><code>pos_mrp</code></a></td><td>pos_mrp</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_online_payment/"><code>pos_online_payment</code></a></td><td>Point of Sale online payment</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_online_payment_self_order/"><code>pos_online_payment_self_order</code></a></td><td>POS Self-Order / Online Payment</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_paytm/"><code>pos_paytm</code></a></td><td>POS PayTM</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_razorpay/"><code>pos_razorpay</code></a></td><td>POS Razorpay</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_restaurant/"><code>pos_restaurant</code></a></td><td>Restaurant</td><td>point_of_sale</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="pos_restaurant_adyen/"><code>pos_restaurant_adyen</code></a></td><td>POS Restaurant Adyen</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_restaurant_loyalty/"><code>pos_restaurant_loyalty</code></a></td><td>POS - Restaurant Loyality</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_restaurant_stripe/"><code>pos_restaurant_stripe</code></a></td><td>POS Restaurant Stripe</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_sale/"><code>pos_sale</code></a></td><td>POS - Sales</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_sale_loyalty/"><code>pos_sale_loyalty</code></a></td><td>POS - Sales Loyality</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_sale_margin/"><code>pos_sale_margin</code></a></td><td>POS - Sale Margin</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_sale_product_configurator/"><code>pos_sale_product_configurator</code></a></td><td>POS - Sale Product Configurator</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_self_order/"><code>pos_self_order</code></a></td><td>POS Self Order</td><td>point_of_sale</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="pos_self_order_adyen/"><code>pos_self_order_adyen</code></a></td><td>POS Self Order Adyen</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_self_order_epson_printer/"><code>pos_self_order_epson_printer</code></a></td><td>POS Self Order Epson Printer</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_self_order_sale/"><code>pos_self_order_sale</code></a></td><td>POS Self Order Sale</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_self_order_stripe/"><code>pos_self_order_stripe</code></a></td><td>POS Self Order Stripe</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_six/"><code>pos_six</code></a></td><td>POS Six</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_stripe/"><code>pos_stripe</code></a></td><td>POS Stripe</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="pos_viva_wallet/"><code>pos_viva_wallet</code></a></td><td>POS Viva Wallet</td><td>point_of_sale</td><td>LGPL-3</td><td>0</td></tr>
</tbody></table>

## Product / Master data

<a id="product"></a>

9 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="barcodes/"><code>barcodes</code></a></td><td>Barcode</td><td>inventory_purchase</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="barcodes_gs1_nomenclature/"><code>barcodes_gs1_nomenclature</code></a></td><td>Barcode - GS1 Nomenclature</td><td>inventory_purchase</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="product/"><code>product</code></a></td><td>Products & Pricelists</td><td>sales_crm</td><td>LGPL-3</td><td>23</td></tr>
<tr><td><a href="product_email_template/"><code>product_email_template</code></a></td><td>Product Email Template</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="product_expiry/"><code>product_expiry</code></a></td><td>Products Expiration Date</td><td>sales_crm</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="product_images/"><code>product_images</code></a></td><td>Product Images</td><td>sales_crm</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="product_margin/"><code>product_margin</code></a></td><td>Margins by Products</td><td>sales_crm</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="product_matrix/"><code>product_matrix</code></a></td><td>Product Matrix</td><td>sales_crm</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="uom/"><code>uom</code></a></td><td>Units of measure</td><td>platform_core</td><td>LGPL-3</td><td>2</td></tr>
</tbody></table>

## Manufacturing

<a id="manufacturing"></a>

12 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="mrp/"><code>mrp</code></a></td><td>Manufacturing</td><td>manufacturing</td><td>LGPL-3</td><td>25</td></tr>
<tr><td><a href="mrp_account/"><code>mrp_account</code></a></td><td>Accounting - MRP</td><td>manufacturing</td><td>LGPL-3</td><td>5</td></tr>
<tr><td><a href="mrp_landed_costs/"><code>mrp_landed_costs</code></a></td><td>Landed Costs On MO</td><td>manufacturing</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mrp_product_expiry/"><code>mrp_product_expiry</code></a></td><td>Manufacturing Expiry</td><td>manufacturing</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mrp_repair/"><code>mrp_repair</code></a></td><td>Mrp Repairs</td><td>manufacturing</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mrp_subcontracting/"><code>mrp_subcontracting</code></a></td><td>MRP Subcontracting</td><td>manufacturing</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="mrp_subcontracting_account/"><code>mrp_subcontracting_account</code></a></td><td>Subcontracting Management with Stock Valuation</td><td>manufacturing</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mrp_subcontracting_dropshipping/"><code>mrp_subcontracting_dropshipping</code></a></td><td>Dropship and Subcontracting Management</td><td>manufacturing</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mrp_subcontracting_purchase/"><code>mrp_subcontracting_purchase</code></a></td><td>Purchase and Subcontracting Management</td><td>manufacturing</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mrp_subcontracting_repair/"><code>mrp_subcontracting_repair</code></a></td><td>MRP Subcontracting Repair</td><td>manufacturing</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mrp_subonctracting_landed_costs/"><code>mrp_subonctracting_landed_costs</code></a></td><td>Landed Costs With Subcontracting order</td><td>manufacturing</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="repair/"><code>repair</code></a></td><td>Repairs</td><td>manufacturing</td><td>LGPL-3</td><td>4</td></tr>
</tbody></table>

## HR / Payroll

<a id="hr"></a>

27 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="hr/"><code>hr</code></a></td><td>Employees</td><td>human_resources</td><td>LGPL-3</td><td>10</td></tr>
<tr><td><a href="hr_attendance/"><code>hr_attendance</code></a></td><td>Attendances</td><td>human_resources</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="hr_contract/"><code>hr_contract</code></a></td><td>Employee Contracts</td><td>human_resources</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="hr_expense/"><code>hr_expense</code></a></td><td>Expenses</td><td>human_resources</td><td>LGPL-3</td><td>6</td></tr>
<tr><td><a href="hr_fleet/"><code>hr_fleet</code></a></td><td>Fleet History</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="hr_gamification/"><code>hr_gamification</code></a></td><td>HR Gamification</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="hr_holidays/"><code>hr_holidays</code></a></td><td>Time Off</td><td>human_resources</td><td>LGPL-3</td><td>12</td></tr>
<tr><td><a href="hr_holidays_attendance/"><code>hr_holidays_attendance</code></a></td><td>HR Attendance Holidays</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="hr_homeworking/"><code>hr_homeworking</code></a></td><td>Remote Work</td><td>human_resources</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="hr_hourly_cost/"><code>hr_hourly_cost</code></a></td><td>Employee Hourly Wage</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="hr_livechat/"><code>hr_livechat</code></a></td><td>HR - Livechat</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="hr_maintenance/"><code>hr_maintenance</code></a></td><td>Maintenance - HR</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="hr_org_chart/"><code>hr_org_chart</code></a></td><td>HR Org Chart</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="hr_presence/"><code>hr_presence</code></a></td><td>Employee Presence Control</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="hr_recruitment/"><code>hr_recruitment</code></a></td><td>Recruitment</td><td>human_resources</td><td>LGPL-3</td><td>9</td></tr>
<tr><td><a href="hr_recruitment_skills/"><code>hr_recruitment_skills</code></a></td><td>Recruitment - Skills Management</td><td>human_resources</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="hr_recruitment_sms/"><code>hr_recruitment_sms</code></a></td><td>Recruitment - SMS</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="hr_recruitment_survey/"><code>hr_recruitment_survey</code></a></td><td>Hr Recruitment Interview Forms</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="hr_skills/"><code>hr_skills</code></a></td><td>Skills Management</td><td>human_resources</td><td>LGPL-3</td><td>10</td></tr>
<tr><td><a href="hr_skills_slides/"><code>hr_skills_slides</code></a></td><td>Skills e-learning</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="hr_skills_survey/"><code>hr_skills_survey</code></a></td><td>Skills Certification</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="hr_timesheet/"><code>hr_timesheet</code></a></td><td>Task Logs</td><td>human_resources</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="hr_timesheet_attendance/"><code>hr_timesheet_attendance</code></a></td><td>Timesheets/attendances reporting</td><td>human_resources</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="hr_work_entry/"><code>hr_work_entry</code></a></td><td>Work Entries</td><td>human_resources</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="hr_work_entry_contract/"><code>hr_work_entry_contract</code></a></td><td>Work Entries - Contract</td><td>human_resources</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="hr_work_entry_holidays/"><code>hr_work_entry_holidays</code></a></td><td>Time Off in Payslips</td><td>human_resources</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="project/"><code>project</code></a></td><td>Project</td><td>projects_services</td><td>LGPL-3</td><td>15</td></tr>
</tbody></table>

## EDI / e-Invoice / e-Way

<a id="edi"></a>

37 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="iap_crm/"><code>iap_crm</code></a></td><td>IAP / CRM</td><td>integrations</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="iap_mail/"><code>iap_mail</code></a></td><td>IAP / Mail</td><td>integrations</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_account_edi_ubl_cii_tests/"><code>l10n_account_edi_ubl_cii_tests</code></a></td><td>Testing the Import/Export invoices with UBL/CII</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_eg_edi_eta/"><code>l10n_eg_edi_eta</code></a></td><td>Egypt E-Invoicing</td><td>localization</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="l10n_es_edi_facturae/"><code>l10n_es_edi_facturae</code></a></td><td>Spain - Facturae EDI</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_es_edi_facturae_adm_centers/"><code>l10n_es_edi_facturae_adm_centers</code></a></td><td>Spain - Facturae EDI - Administrative Centers Patch</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_es_edi_facturae_invoice_period/"><code>l10n_es_edi_facturae_invoice_period</code></a></td><td>Spain - Facturae EDI - Invoice Period</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_es_edi_sii/"><code>l10n_es_edi_sii</code></a></td><td>Spain - SII EDI Suministro de Libros</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_es_edi_tbai/"><code>l10n_es_edi_tbai</code></a></td><td>Spain - TicketBAI</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_es_edi_tbai_multi_refund/"><code>l10n_es_edi_tbai_multi_refund</code></a></td><td>TicketBAI multi refund</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_es_edi_verifactu/"><code>l10n_es_edi_verifactu</code></a></td><td>Spain - Veri*Factu</td><td>localization</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="l10n_es_edi_verifactu_pos/"><code>l10n_es_edi_verifactu_pos</code></a></td><td>Spain - Veri*Factu for Point of Sale</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_hu_edi/"><code>l10n_hu_edi</code></a></td><td>Hungary - E-invoicing</td><td>localization</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="l10n_in_edi/"><code>l10n_in_edi</code></a></td><td>Indian - E-invoicing</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_in_edi_ewaybill/"><code>l10n_in_edi_ewaybill</code></a></td><td>Indian - E-waybill</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_in_ewaybill_port/"><code>l10n_in_ewaybill_port</code></a></td><td>Indian - Shipping Ports for E-waybill</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_in_ewaybill_stock/"><code>l10n_in_ewaybill_stock</code></a></td><td>Indian - E-waybill Stock</td><td>localization</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="l10n_it_edi/"><code>l10n_it_edi</code></a></td><td>Italy - E-invoicing</td><td>localization</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="l10n_it_edi_doi/"><code>l10n_it_edi_doi</code></a></td><td>Italy - Declaration of Intent</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_it_edi_ndd/"><code>l10n_it_edi_ndd</code></a></td><td>Italy - E-invoicing - Additional module to support the debit notes (nota di debito - NDD)</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_it_edi_ndd_account_dn/"><code>l10n_it_edi_ndd_account_dn</code></a></td><td>Italy - E-invoicing - Bridge module between Italy NDD and Account Debit Note</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_it_edi_sale/"><code>l10n_it_edi_sale</code></a></td><td>Italy - Sale E-invoicing</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_it_edi_website_sale/"><code>l10n_it_edi_website_sale</code></a></td><td>Italy eCommerce eInvoicing</td><td>localization</td><td>OEEL-1</td><td>0</td></tr>
<tr><td><a href="l10n_it_edi_withholding/"><code>l10n_it_edi_withholding</code></a></td><td>Italy - E-invoicing (Withholding)</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_jo_edi/"><code>l10n_jo_edi</code></a></td><td>Jordan E-Invoicing</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_jo_edi_extended/"><code>l10n_jo_edi_extended</code></a></td><td>Jordan E-Invoicing Extended Features</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ke_edi_tremol/"><code>l10n_ke_edi_tremol</code></a></td><td>Kenya Tremol Device EDI Integration</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_my_edi/"><code>l10n_my_edi</code></a></td><td>Malaysia - E-invoicing</td><td>localization</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="l10n_my_edi_extended/"><code>l10n_my_edi_extended</code></a></td><td>Malaysia - E-invoicing Extended Features</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ro_edi/"><code>l10n_ro_edi</code></a></td><td>Romania - E-invoicing</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_ro_edi_stock/"><code>l10n_ro_edi_stock</code></a></td><td>Romania - E-Transport</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ro_edi_stock_batch/"><code>l10n_ro_edi_stock_batch</code></a></td><td>Romania - E-Transport Batch Pickings</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_rs_edi/"><code>l10n_rs_edi</code></a></td><td>Serbia - eFaktura E-invoicing</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_sa_edi/"><code>l10n_sa_edi</code></a></td><td>Saudi Arabia - E-invoicing</td><td>localization</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="l10n_sa_edi_pos/"><code>l10n_sa_edi_pos</code></a></td><td>Saudi Arabia - E-invoicing (Simplified)</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_tr_nilvera_edispatch/"><code>l10n_tr_nilvera_edispatch</code></a></td><td>Türkiye - e-Irsaliye (e-Dispatch)</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_vn_edi_viettel/"><code>l10n_vn_edi_viettel</code></a></td><td>Vietnam - E-invoicing</td><td>localization</td><td>LGPL-3</td><td>3</td></tr>
</tbody></table>

## Localization

<a id="localization"></a>

176 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="l10n_ae/"><code>l10n_ae</code></a></td><td>United Arab Emirates - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_anz_ubl_pint/"><code>l10n_anz_ubl_pint</code></a></td><td>Australia & New Zealand - UBL PINT</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_ar/"><code>l10n_ar</code></a></td><td>Argentina - Accounting</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_ar_pos/"><code>l10n_ar_pos</code></a></td><td>Argentinean - Point of Sale with AR Doc</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ar_website_sale/"><code>l10n_ar_website_sale</code></a></td><td>Argentinean eCommerce</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ar_withholding/"><code>l10n_ar_withholding</code></a></td><td>Argentina - Payment Withholdings</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_at/"><code>l10n_at</code></a></td><td>Austria - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_au/"><code>l10n_au</code></a></td><td>Australia - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_bd/"><code>l10n_bd</code></a></td><td>Bangladesh - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_be/"><code>l10n_be</code></a></td><td>Belgium - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_be_pos_sale/"><code>l10n_be_pos_sale</code></a></td><td>l10n_be_pos_sale</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_bf/"><code>l10n_bf</code></a></td><td>Burkina Faso - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_bg/"><code>l10n_bg</code></a></td><td>Bulgaria - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_bh/"><code>l10n_bh</code></a></td><td>Bahrain - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_bj/"><code>l10n_bj</code></a></td><td>Benin - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_bo/"><code>l10n_bo</code></a></td><td>Bolivia - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_br/"><code>l10n_br</code></a></td><td>Brazilian - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_br_pix/"><code>l10n_br_pix</code></a></td><td>Brazil Pix QR codes</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_br_sales/"><code>l10n_br_sales</code></a></td><td>Brazil - Sale</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_br_website_sale/"><code>l10n_br_website_sale</code></a></td><td>Brazil - Website Sale</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ca/"><code>l10n_ca</code></a></td><td>Canada - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_cd/"><code>l10n_cd</code></a></td><td>Democratic Republic of the Congo - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_cf/"><code>l10n_cf</code></a></td><td>Central African Republic - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_cg/"><code>l10n_cg</code></a></td><td>Congo - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ch/"><code>l10n_ch</code></a></td><td>Switzerland - Accounting</td><td>localization</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="l10n_ch_pos/"><code>l10n_ch_pos</code></a></td><td>Swiss - Point of Sale</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_ci/"><code>l10n_ci</code></a></td><td>Ivory Coast - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_cl/"><code>l10n_cl</code></a></td><td>Chile - Accounting</td><td>localization</td><td>LGPL-3</td><td>4</td></tr>
<tr><td><a href="l10n_cm/"><code>l10n_cm</code></a></td><td>Cameroon - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_cn/"><code>l10n_cn</code></a></td><td>China - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_cn_city/"><code>l10n_cn_city</code></a></td><td>China - City Data</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_co/"><code>l10n_co</code></a></td><td>Colombia - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_co_pos/"><code>l10n_co_pos</code></a></td><td>Colombian - Point of Sale</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_cr/"><code>l10n_cr</code></a></td><td>Costa Rica - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_cy/"><code>l10n_cy</code></a></td><td>Cyprus - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_cz/"><code>l10n_cz</code></a></td><td>Czech - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_de/"><code>l10n_de</code></a></td><td>Germany - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_de_audit_trail/"><code>l10n_de_audit_trail</code></a></td><td>Germany - audit trail</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_din5008/"><code>l10n_din5008</code></a></td><td>DIN 5008</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_din5008_purchase/"><code>l10n_din5008_purchase</code></a></td><td>DIN 5008 - Purchase</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_din5008_repair/"><code>l10n_din5008_repair</code></a></td><td>DIN 5008 - Repair</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_din5008_sale/"><code>l10n_din5008_sale</code></a></td><td>DIN 5008 - Sale</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_din5008_stock/"><code>l10n_din5008_stock</code></a></td><td>DIN 5008 - Stock</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_dk/"><code>l10n_dk</code></a></td><td>Denmark - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_dk_audit_trail/"><code>l10n_dk_audit_trail</code></a></td><td>Denmark - audit trail</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_dk_bookkeeping/"><code>l10n_dk_bookkeeping</code></a></td><td>Denmark - Bookkeeping Act</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_dk_fik/"><code>l10n_dk_fik</code></a></td><td>Denmark - FIK Number</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_dk_oioubl/"><code>l10n_dk_oioubl</code></a></td><td>Denmark - E-invoicing</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_do/"><code>l10n_do</code></a></td><td>Dominican Republic - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_dz/"><code>l10n_dz</code></a></td><td>Algeria - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ec/"><code>l10n_ec</code></a></td><td>Ecuadorian Accounting</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_ec_stock/"><code>l10n_ec_stock</code></a></td><td>Ecuador - Stock</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ec_website_sale/"><code>l10n_ec_website_sale</code></a></td><td>Ecuadorian Website</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ee/"><code>l10n_ee</code></a></td><td>Estonia - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_eg/"><code>l10n_eg</code></a></td><td>Egypt - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_es/"><code>l10n_es</code></a></td><td>Spain - Accounting (PGCE 2008)</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_es_modelo130/"><code>l10n_es_modelo130</code></a></td><td>Spain - Modelo 130 Tax report</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_es_pos/"><code>l10n_es_pos</code></a></td><td>Spain - Point of Sale</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_es_pos_tbai/"><code>l10n_es_pos_tbai</code></a></td><td>Spain - POS + TicketBAI</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_et/"><code>l10n_et</code></a></td><td>Ethiopia - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_eu_oss/"><code>l10n_eu_oss</code></a></td><td>EU One Stop Shop (OSS)</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_fi/"><code>l10n_fi</code></a></td><td>Finnish Localization</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_fi_sale/"><code>l10n_fi_sale</code></a></td><td>Finland - Sale</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_fr/"><code>l10n_fr</code></a></td><td>France - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_fr_facturx_chorus_pro/"><code>l10n_fr_facturx_chorus_pro</code></a></td><td>France - Factur-X integration with Chorus Pro</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_fr_fec/"><code>l10n_fr_fec</code></a></td><td>France - FEC Export</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_fr_hr_holidays/"><code>l10n_fr_hr_holidays</code></a></td><td>France - Time Off</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_fr_hr_work_entry_holidays/"><code>l10n_fr_hr_work_entry_holidays</code></a></td><td>France - Work Entries Time Off</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_fr_invoice_addr/"><code>l10n_fr_invoice_addr</code></a></td><td>France - Adding Mandatory Invoice Mentions (Decree no. 2022-1299)</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_fr_pdp/"><code>l10n_fr_pdp</code></a></td><td>France - E-Invoicing (Approved Platform)</td><td>localization</td><td>LGPL-3</td><td>6</td></tr>
<tr><td><a href="l10n_fr_pdp_pos/"><code>l10n_fr_pdp_pos</code></a></td><td>France - E-reporting for POS</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_fr_pos_cert/"><code>l10n_fr_pos_cert</code></a></td><td>France - VAT Anti-Fraud Certification for Point of Sale (CGI 286 I-3 bis)</td><td>localization</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="l10n_ga/"><code>l10n_ga</code></a></td><td>Gabon - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_gcc_invoice/"><code>l10n_gcc_invoice</code></a></td><td>G.C.C. - Arabic/English Invoice</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_gcc_invoice_stock_account/"><code>l10n_gcc_invoice_stock_account</code></a></td><td>Gulf Cooperation Council WMS Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_gcc_pos/"><code>l10n_gcc_pos</code></a></td><td>Gulf Cooperation Council - Point of Sale</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_gn/"><code>l10n_gn</code></a></td><td>Guinea - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_gq/"><code>l10n_gq</code></a></td><td>Guinea Equatorial - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_gr/"><code>l10n_gr</code></a></td><td>Greece - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_gt/"><code>l10n_gt</code></a></td><td>Guatemala - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_gw/"><code>l10n_gw</code></a></td><td>Guinea-Bissau - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_hk/"><code>l10n_hk</code></a></td><td>Hong Kong - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_hn/"><code>l10n_hn</code></a></td><td>Honduras - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_hr/"><code>l10n_hr</code></a></td><td>Croatia - Accounting (Euro)</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_hr_kuna/"><code>l10n_hr_kuna</code></a></td><td>Croatia - Accounting (Kuna)</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_hu/"><code>l10n_hu</code></a></td><td>Hungary - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_id/"><code>l10n_id</code></a></td><td>Indonesian - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_id_efaktur/"><code>l10n_id_efaktur</code></a></td><td>Indonesia E-faktur</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_id_efaktur_coretax/"><code>l10n_id_efaktur_coretax</code></a></td><td>Indonesia E-faktur (Coretax)</td><td>localization</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="l10n_ie/"><code>l10n_ie</code></a></td><td>Ireland - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_il/"><code>l10n_il</code></a></td><td>Israel - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_in/"><code>l10n_in</code></a></td><td>Indian - Accounting</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_in_pos/"><code>l10n_in_pos</code></a></td><td>Indian - Point of Sale</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_in_purchase/"><code>l10n_in_purchase</code></a></td><td>Indian - Purchase Report(GST)</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_in_purchase_stock/"><code>l10n_in_purchase_stock</code></a></td><td>India Purchase and Warehouse Management</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_in_sale/"><code>l10n_in_sale</code></a></td><td>Indian - Sale Report(GST)</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_in_sale_stock/"><code>l10n_in_sale_stock</code></a></td><td>India Sales and Warehouse Management</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_in_stock/"><code>l10n_in_stock</code></a></td><td>Indian - Stock Report(GST)</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_in_withholding/"><code>l10n_in_withholding</code></a></td><td>Indian - TDS</td><td>localization</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="l10n_iq/"><code>l10n_iq</code></a></td><td>Iraq - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_it/"><code>l10n_it</code></a></td><td>Italy - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_it_stock_ddt/"><code>l10n_it_stock_ddt</code></a></td><td>Italy - Stock DDT</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_jo/"><code>l10n_jo</code></a></td><td>Jordan - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_jp/"><code>l10n_jp</code></a></td><td>Japan - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_jp_ubl_pint/"><code>l10n_jp_ubl_pint</code></a></td><td>Japan - UBL PINT</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_ke/"><code>l10n_ke</code></a></td><td>Kenya - Accounting</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_km/"><code>l10n_km</code></a></td><td>Comoros - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_kw/"><code>l10n_kw</code></a></td><td>Kuwait - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_kz/"><code>l10n_kz</code></a></td><td>Kazakhstan - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_latam_base/"><code>l10n_latam_base</code></a></td><td>LATAM Localization Base</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_latam_check/"><code>l10n_latam_check</code></a></td><td>Third Party and Deferred/Electronic Checks Management</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_latam_invoice_document/"><code>l10n_latam_invoice_document</code></a></td><td>LATAM Document</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_lb_account/"><code>l10n_lb_account</code></a></td><td>Lebanon - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_lt/"><code>l10n_lt</code></a></td><td>Lithuania - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_lu/"><code>l10n_lu</code></a></td><td>Luxembourg - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_lv/"><code>l10n_lv</code></a></td><td>Latvia - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ma/"><code>l10n_ma</code></a></td><td>Morocco - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ml/"><code>l10n_ml</code></a></td><td>Mali - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_mn/"><code>l10n_mn</code></a></td><td>Mongolia - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_mr/"><code>l10n_mr</code></a></td><td>Mauritania - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_mt/"><code>l10n_mt</code></a></td><td>Malta - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_mt_pos/"><code>l10n_mt_pos</code></a></td><td>Malta - Point of Sale</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_mu_account/"><code>l10n_mu_account</code></a></td><td>Mauritius - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_mx/"><code>l10n_mx</code></a></td><td>Mexico - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_mx_hr/"><code>l10n_mx_hr</code></a></td><td>Employees - Mexico</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_my/"><code>l10n_my</code></a></td><td>Malaysia - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_my_ubl_pint/"><code>l10n_my_ubl_pint</code></a></td><td>Malaysia - UBL PINT</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_mz/"><code>l10n_mz</code></a></td><td>Mozambique - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ne/"><code>l10n_ne</code></a></td><td>Niger - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ng/"><code>l10n_ng</code></a></td><td>Nigeria - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_nl/"><code>l10n_nl</code></a></td><td>Netherlands - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_no/"><code>l10n_no</code></a></td><td>Norway - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_nz/"><code>l10n_nz</code></a></td><td>New Zealand - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_pa/"><code>l10n_pa</code></a></td><td>Panama - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_pe/"><code>l10n_pe</code></a></td><td>Peru - Accounting</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_pe_pos/"><code>l10n_pe_pos</code></a></td><td>Peruvian - Point of Sale with Pe Doc</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_pe_website_sale/"><code>l10n_pe_website_sale</code></a></td><td>Peruvian eCommerce</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ph/"><code>l10n_ph</code></a></td><td>Philippines - Accounting</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_pk/"><code>l10n_pk</code></a></td><td>Pakistan - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_pl/"><code>l10n_pl</code></a></td><td>Poland - Accounting</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_pt/"><code>l10n_pt</code></a></td><td>Portugal - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_qa/"><code>l10n_qa</code></a></td><td>Qatar - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ro/"><code>l10n_ro</code></a></td><td>Romania - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ro_cpv_code/"><code>l10n_ro_cpv_code</code></a></td><td>Romania - CPV Code</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_ro_efactura/"><code>l10n_ro_efactura</code></a></td><td>Romania - Send E-Factura</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_ro_efactura_synchronize/"><code>l10n_ro_efactura_synchronize</code></a></td><td>Romania - Synchronize E-Factura</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_rs/"><code>l10n_rs</code></a></td><td>Serbia - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_rw/"><code>l10n_rw</code></a></td><td>Rwanda - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_sa/"><code>l10n_sa</code></a></td><td>Saudi Arabia - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_sa_pos/"><code>l10n_sa_pos</code></a></td><td>Saudi Arabia - Point of Sale</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_se/"><code>l10n_se</code></a></td><td>Sweden - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_sg/"><code>l10n_sg</code></a></td><td>Singapore - Accounting</td><td>localization</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="l10n_sg_ubl_pint/"><code>l10n_sg_ubl_pint</code></a></td><td>Singapore - UBL PINT</td><td>localization</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="l10n_si/"><code>l10n_si</code></a></td><td>Slovenian - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_sk/"><code>l10n_sk</code></a></td><td>Slovak - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_sn/"><code>l10n_sn</code></a></td><td>Sénégal - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_syscohada/"><code>l10n_syscohada</code></a></td><td>OHADA - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_td/"><code>l10n_td</code></a></td><td>Tchad - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_tg/"><code>l10n_tg</code></a></td><td>Togo - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_th/"><code>l10n_th</code></a></td><td>Thailand - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_tn/"><code>l10n_tn</code></a></td><td>Tunisia - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_tr/"><code>l10n_tr</code></a></td><td>Türkiye - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_tr_nilvera/"><code>l10n_tr_nilvera</code></a></td><td>Türkiye - Nilvera</td><td>localization</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="l10n_tr_nilvera_einvoice/"><code>l10n_tr_nilvera_einvoice</code></a></td><td>Türkiye - Nilvera E-Invoice</td><td>localization</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="l10n_tw/"><code>l10n_tw</code></a></td><td>Taiwan - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_tz_account/"><code>l10n_tz_account</code></a></td><td>Tanzania - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ua/"><code>l10n_ua</code></a></td><td>Ukraine - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ug/"><code>l10n_ug</code></a></td><td>Uganda - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_uk/"><code>l10n_uk</code></a></td><td>United Kingdom - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_us/"><code>l10n_us</code></a></td><td>United States - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_uy/"><code>l10n_uy</code></a></td><td>Uruguay - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_uy_website_sale/"><code>l10n_uy_website_sale</code></a></td><td>Uruguay Website</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_ve/"><code>l10n_ve</code></a></td><td>Venezuela - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_vn/"><code>l10n_vn</code></a></td><td>Vietnam - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_za/"><code>l10n_za</code></a></td><td>South Africa - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="l10n_zm_account/"><code>l10n_zm_account</code></a></td><td>Zambia - Accounting</td><td>localization</td><td>LGPL-3</td><td>0</td></tr>
</tbody></table>

## Website / eCommerce

<a id="website"></a>

59 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="portal/"><code>portal</code></a></td><td>Customer Portal</td><td>website_ecommerce</td><td>LGPL-3</td><td>4</td></tr>
<tr><td><a href="rating/"><code>rating</code></a></td><td>Customer Rating</td><td>platform_core</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="website/"><code>website</code></a></td><td>Website</td><td>website_ecommerce</td><td>LGPL-3</td><td>29</td></tr>
<tr><td><a href="website_blog/"><code>website_blog</code></a></td><td>Blog</td><td>website_ecommerce</td><td>LGPL-3</td><td>4</td></tr>
<tr><td><a href="website_cf_turnstile/"><code>website_cf_turnstile</code></a></td><td>Cloudflare Turnstile</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_crm/"><code>website_crm</code></a></td><td>Contact Form</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_crm_iap_reveal/"><code>website_crm_iap_reveal</code></a></td><td>Lead Generation From Website Visits</td><td>website_ecommerce</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="website_crm_livechat/"><code>website_crm_livechat</code></a></td><td>Lead Livechat Sessions</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_crm_partner_assign/"><code>website_crm_partner_assign</code></a></td><td>Resellers</td><td>website_ecommerce</td><td>LGPL-3</td><td>5</td></tr>
<tr><td><a href="website_crm_sms/"><code>website_crm_sms</code></a></td><td>Send SMS to Visitor with leads</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_customer/"><code>website_customer</code></a></td><td>Customer References</td><td>website_ecommerce</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="website_event/"><code>website_event</code></a></td><td>Events</td><td>website_ecommerce</td><td>LGPL-3</td><td>10</td></tr>
<tr><td><a href="website_event_booth/"><code>website_event_booth</code></a></td><td>Online Event Booths</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_event_booth_exhibitor/"><code>website_event_booth_exhibitor</code></a></td><td>Booths/Exhibitors Bridge</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_event_booth_sale/"><code>website_event_booth_sale</code></a></td><td>Online Event Booth Sale</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_event_booth_sale_exhibitor/"><code>website_event_booth_sale_exhibitor</code></a></td><td>Booths Sale/Exhibitors Bridge</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_event_crm/"><code>website_event_crm</code></a></td><td>Website Events CRM</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_event_exhibitor/"><code>website_event_exhibitor</code></a></td><td>Event Exhibitors</td><td>website_ecommerce</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="website_event_jitsi/"><code>website_event_jitsi</code></a></td><td>Event / Jitsi</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_event_meet/"><code>website_event_meet</code></a></td><td>Event Meeting / Rooms</td><td>website_ecommerce</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="website_event_meet_quiz/"><code>website_event_meet_quiz</code></a></td><td>Quiz and Meet on community</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_event_sale/"><code>website_event_sale</code></a></td><td>Online Event Ticketing</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_event_track/"><code>website_event_track</code></a></td><td>Advanced Events</td><td>website_ecommerce</td><td>LGPL-3</td><td>7</td></tr>
<tr><td><a href="website_event_track_live/"><code>website_event_track_live</code></a></td><td>Live Event Tracks</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_event_track_live_quiz/"><code>website_event_track_live_quiz</code></a></td><td>Quiz on Live Event Tracks</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_event_track_quiz/"><code>website_event_track_quiz</code></a></td><td>Quizzes on Tracks</td><td>website_ecommerce</td><td>LGPL-3</td><td>4</td></tr>
<tr><td><a href="website_form_project/"><code>website_form_project</code></a></td><td>Online Task Submission</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_forum/"><code>website_forum</code></a></td><td>Forum</td><td>website_ecommerce</td><td>LGPL-3</td><td>5</td></tr>
<tr><td><a href="website_google_map/"><code>website_google_map</code></a></td><td>Google Maps</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_hr_recruitment/"><code>website_hr_recruitment</code></a></td><td>Online Jobs</td><td>website_ecommerce</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="website_jitsi/"><code>website_jitsi</code></a></td><td>Website Jitsi</td><td>website_ecommerce</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="website_links/"><code>website_links</code></a></td><td>Link Tracker</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_livechat/"><code>website_livechat</code></a></td><td>Website Live Chat</td><td>website_ecommerce</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="website_mail/"><code>website_mail</code></a></td><td>Website Mail</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_mail_group/"><code>website_mail_group</code></a></td><td>Website Mail Group</td><td>website_ecommerce</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="website_mass_mailing/"><code>website_mass_mailing</code></a></td><td>Newsletter Subscribe Button</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_mass_mailing_sms/"><code>website_mass_mailing_sms</code></a></td><td>Newsletter Subscribe SMS Template</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_membership/"><code>website_membership</code></a></td><td>Online Members Directory</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_partner/"><code>website_partner</code></a></td><td>Website Partner</td><td>website_ecommerce</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="website_payment/"><code>website_payment</code></a></td><td>Website Payment</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_payment_authorize/"><code>website_payment_authorize</code></a></td><td>Website - Payment Authorize</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_profile/"><code>website_profile</code></a></td><td>Website profile</td><td>website_ecommerce</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="website_sale_autocomplete/"><code>website_sale_autocomplete</code></a></td><td>Google places autocompletion</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_sale_comparison/"><code>website_sale_comparison</code></a></td><td>Product Comparison</td><td>website_ecommerce</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="website_sale_comparison_wishlist/"><code>website_sale_comparison_wishlist</code></a></td><td>Product Availability Notifications</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_sale_loyalty/"><code>website_sale_loyalty</code></a></td><td>Coupons, Promotions, Gift Card and Loyalty for eCommerce</td><td>website_ecommerce</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="website_sale_mondialrelay/"><code>website_sale_mondialrelay</code></a></td><td>eCommerce Mondialrelay Delivery</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_sale_mrp/"><code>website_sale_mrp</code></a></td><td>Kit Availability</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_sale_picking/"><code>website_sale_picking</code></a></td><td>On site Payment & Picking</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_sale_product_configurator/"><code>website_sale_product_configurator</code></a></td><td>Website Sale Product Configurator</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_sale_slides/"><code>website_sale_slides</code></a></td><td>Sell Courses</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_sale_stock/"><code>website_sale_stock</code></a></td><td>Product Availability</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_sale_stock_wishlist/"><code>website_sale_stock_wishlist</code></a></td><td>Product Availability Notifications</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_sale_wishlist/"><code>website_sale_wishlist</code></a></td><td>Shopper's Wishlist</td><td>website_ecommerce</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="website_slides/"><code>website_slides</code></a></td><td>eLearning</td><td>website_ecommerce</td><td>LGPL-3</td><td>12</td></tr>
<tr><td><a href="website_slides_forum/"><code>website_slides_forum</code></a></td><td>Forum on Courses</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_slides_survey/"><code>website_slides_survey</code></a></td><td>Course Certifications</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_sms/"><code>website_sms</code></a></td><td>Send SMS to Visitor</td><td>website_ecommerce</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="website_twitter/"><code>website_twitter</code></a></td><td>Twitter Snippet</td><td>website_ecommerce</td><td>LGPL-3</td><td>1</td></tr>
</tbody></table>

## Marketing / Events

<a id="marketing"></a>

23 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="event/"><code>event</code></a></td><td>Events Organization</td><td>marketing_events</td><td>LGPL-3</td><td>11</td></tr>
<tr><td><a href="event_booth/"><code>event_booth</code></a></td><td>Events Booths</td><td>marketing_events</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="event_booth_sale/"><code>event_booth_sale</code></a></td><td>Events Booths Sales</td><td>marketing_events</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="event_crm/"><code>event_crm</code></a></td><td>Event CRM</td><td>marketing_events</td><td>LGPL-3</td><td>2</td></tr>
<tr><td><a href="event_crm_sale/"><code>event_crm_sale</code></a></td><td>Event CRM Sale</td><td>marketing_events</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="event_sale/"><code>event_sale</code></a></td><td>Events Sales</td><td>marketing_events</td><td>LGPL-3</td><td>4</td></tr>
<tr><td><a href="event_sms/"><code>event_sms</code></a></td><td>SMS on Events</td><td>marketing_events</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mass_mailing/"><code>mass_mailing</code></a></td><td>Email Marketing</td><td>marketing_events</td><td>LGPL-3</td><td>15</td></tr>
<tr><td><a href="mass_mailing_crm/"><code>mass_mailing_crm</code></a></td><td>Mass mailing on lead / opportunities</td><td>marketing_events</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="mass_mailing_crm_sms/"><code>mass_mailing_crm_sms</code></a></td><td>Mass mailing sms on lead / opportunities</td><td>marketing_events</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mass_mailing_event/"><code>mass_mailing_event</code></a></td><td>Mass mailing on attendees</td><td>marketing_events</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mass_mailing_event_sms/"><code>mass_mailing_event_sms</code></a></td><td>Event Attendees SMS Marketing</td><td>marketing_events</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mass_mailing_event_track/"><code>mass_mailing_event_track</code></a></td><td>Mass mailing on track speakers</td><td>marketing_events</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mass_mailing_event_track_sms/"><code>mass_mailing_event_track_sms</code></a></td><td>Track Speakers SMS Marketing</td><td>marketing_events</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mass_mailing_sale/"><code>mass_mailing_sale</code></a></td><td>Mass mailing on sale orders</td><td>marketing_events</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="mass_mailing_sale_sms/"><code>mass_mailing_sale_sms</code></a></td><td>Mass mailing sms on sale orders</td><td>marketing_events</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mass_mailing_slides/"><code>mass_mailing_slides</code></a></td><td>Mass mailing on course members</td><td>marketing_events</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="mass_mailing_sms/"><code>mass_mailing_sms</code></a></td><td>SMS Marketing</td><td>marketing_events</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="mass_mailing_themes/"><code>mass_mailing_themes</code></a></td><td>Mass Mailing Themes</td><td>marketing_events</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="sms/"><code>sms</code></a></td><td>SMS gateway</td><td>integrations</td><td>LGPL-3</td><td>10</td></tr>
<tr><td><a href="snailmail/"><code>snailmail</code></a></td><td>Snail Mail</td><td>platform_core</td><td>LGPL-3</td><td>3</td></tr>
<tr><td><a href="survey/"><code>survey</code></a></td><td>Surveys</td><td>marketing_events</td><td>LGPL-3</td><td>6</td></tr>
<tr><td><a href="utm/"><code>utm</code></a></td><td>UTM Trackers</td><td>platform_core</td><td>LGPL-3</td><td>7</td></tr>
</tbody></table>

## Knowledge / Helpdesk

<a id="knowledge"></a>

1 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="spreadsheet/"><code>spreadsheet</code></a></td><td>Spreadsheet</td><td>platform_core</td><td>LGPL-3</td><td>1</td></tr>
</tbody></table>

## Reporting / Spreadsheet

<a id="reporting"></a>

4 modules.

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th><th>License</th><th>Models defined</th></tr></thead>
<tbody>
<tr><td><a href="board/"><code>board</code></a></td><td>Dashboards</td><td>platform_core</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="mail_plugin/"><code>mail_plugin</code></a></td><td>Mail Plugin</td><td>platform_core</td><td>LGPL-3</td><td>1</td></tr>
<tr><td><a href="spreadsheet_account/"><code>spreadsheet_account</code></a></td><td>Spreadsheet Accounting Formulas</td><td>platform_core</td><td>LGPL-3</td><td>0</td></tr>
<tr><td><a href="spreadsheet_dashboard/"><code>spreadsheet_dashboard</code></a></td><td>Spreadsheet dashboard</td><td>platform_core</td><td>LGPL-3</td><td>3</td></tr>
</tbody></table>

## Other

<table>
<thead><tr><th>Module</th><th>Title</th><th>Domain</th></tr></thead>
<tbody>
<tr><td><a href="analytic/"><code>analytic</code></a></td><td>Analytic Accounting</td><td>accounting</td></tr>
<tr><td><a href="attachment_indexation/"><code>attachment_indexation</code></a></td><td>Attachments List and Document Indexation</td><td>platform_core</td></tr>
<tr><td><a href="calendar/"><code>calendar</code></a></td><td>Calendar</td><td>platform_core</td></tr>
<tr><td><a href="calendar_sms/"><code>calendar_sms</code></a></td><td>Calendar - SMS</td><td>platform_core</td></tr>
<tr><td><a href="contacts/"><code>contacts</code></a></td><td>Contacts</td><td>sales_crm</td></tr>
<tr><td><a href="crm/"><code>crm</code></a></td><td>CRM</td><td>sales_crm</td></tr>
<tr><td><a href="crm_iap_enrich/"><code>crm_iap_enrich</code></a></td><td>Lead Enrichment</td><td>sales_crm</td></tr>
<tr><td><a href="crm_iap_mine/"><code>crm_iap_mine</code></a></td><td>Lead Generation</td><td>sales_crm</td></tr>
<tr><td><a href="crm_livechat/"><code>crm_livechat</code></a></td><td>CRM Livechat</td><td>sales_crm</td></tr>
<tr><td><a href="crm_mail_plugin/"><code>crm_mail_plugin</code></a></td><td>CRM Mail Plugin</td><td>sales_crm</td></tr>
<tr><td><a href="crm_sms/"><code>crm_sms</code></a></td><td>SMS in CRM</td><td>sales_crm</td></tr>
<tr><td><a href="data_recycle/"><code>data_recycle</code></a></td><td>Data Recycle</td><td>platform_core</td></tr>
<tr><td><a href="delivery_mondialrelay/"><code>delivery_mondialrelay</code></a></td><td>delivery_mondialrelay</td><td>inventory_purchase</td></tr>
<tr><td><a href="delivery_stock_picking_batch/"><code>delivery_stock_picking_batch</code></a></td><td>Delivery Stock Picking Batch</td><td>inventory_purchase</td></tr>
<tr><td><a href="digest/"><code>digest</code></a></td><td>KPI Digests</td><td>platform_core</td></tr>
<tr><td><a href="fleet/"><code>fleet</code></a></td><td>Fleet</td><td>human_resources</td></tr>
<tr><td><a href="gamification/"><code>gamification</code></a></td><td>Gamification</td><td>platform_core</td></tr>
<tr><td><a href="gamification_sale_crm/"><code>gamification_sale_crm</code></a></td><td>CRM Gamification</td><td>platform_core</td></tr>
<tr><td><a href="google_account/"><code>google_account</code></a></td><td>Google Users</td><td>integrations</td></tr>
<tr><td><a href="google_calendar/"><code>google_calendar</code></a></td><td>Google Calendar</td><td>integrations</td></tr>
<tr><td><a href="google_gmail/"><code>google_gmail</code></a></td><td>Google Gmail</td><td>integrations</td></tr>
<tr><td><a href="google_recaptcha/"><code>google_recaptcha</code></a></td><td>Google reCAPTCHA integration</td><td>integrations</td></tr>
<tr><td><a href="http_routing/"><code>http_routing</code></a></td><td>Web Routing</td><td>platform_core</td></tr>
<tr><td><a href="iap/"><code>iap</code></a></td><td>In-App Purchases</td><td>integrations</td></tr>
<tr><td><a href="im_livechat/"><code>im_livechat</code></a></td><td>Live Chat</td><td>platform_core</td></tr>
<tr><td><a href="im_livechat_mail_bot/"><code>im_livechat_mail_bot</code></a></td><td>OdooBot for livechat</td><td>platform_core</td></tr>
<tr><td><a href="link_tracker/"><code>link_tracker</code></a></td><td>Link Tracker</td><td>platform_core</td></tr>
<tr><td><a href="loyalty/"><code>loyalty</code></a></td><td>Coupons & Loyalty</td><td>sales_crm</td></tr>
<tr><td><a href="lunch/"><code>lunch</code></a></td><td>Lunch</td><td>human_resources</td></tr>
<tr><td><a href="mail_bot/"><code>mail_bot</code></a></td><td>OdooBot</td><td>platform_core</td></tr>
<tr><td><a href="mail_bot_hr/"><code>mail_bot_hr</code></a></td><td>OdooBot - HR</td><td>platform_core</td></tr>
<tr><td><a href="mail_group/"><code>mail_group</code></a></td><td>Mail Group</td><td>platform_core</td></tr>
<tr><td><a href="maintenance/"><code>maintenance</code></a></td><td>Maintenance</td><td>manufacturing</td></tr>
<tr><td><a href="membership/"><code>membership</code></a></td><td>Members</td><td>platform_core</td></tr>
<tr><td><a href="microsoft_account/"><code>microsoft_account</code></a></td><td>Microsoft Users</td><td>integrations</td></tr>
<tr><td><a href="microsoft_calendar/"><code>microsoft_calendar</code></a></td><td>Outlook Calendar</td><td>integrations</td></tr>
<tr><td><a href="microsoft_outlook/"><code>microsoft_outlook</code></a></td><td>Microsoft Outlook</td><td>integrations</td></tr>
<tr><td><a href="onboarding/"><code>onboarding</code></a></td><td>Onboarding Toolbox</td><td>platform_core</td></tr>
<tr><td><a href="partner_autocomplete/"><code>partner_autocomplete</code></a></td><td>Partner Autocomplete</td><td>platform_core</td></tr>
<tr><td><a href="payment/"><code>payment</code></a></td><td>Payment Engine</td><td>accounting</td></tr>
<tr><td><a href="payment_adyen/"><code>payment_adyen</code></a></td><td>Payment Provider: Adyen</td><td>accounting</td></tr>
<tr><td><a href="payment_alipay/"><code>payment_alipay</code></a></td><td>Payment Provider: Alipay</td><td>accounting</td></tr>
<tr><td><a href="payment_aps/"><code>payment_aps</code></a></td><td>Payment Provider: Amazon Payment Services</td><td>accounting</td></tr>
<tr><td><a href="payment_asiapay/"><code>payment_asiapay</code></a></td><td>Payment Provider: AsiaPay</td><td>accounting</td></tr>
<tr><td><a href="payment_authorize/"><code>payment_authorize</code></a></td><td>Payment Provider: Authorize.Net</td><td>accounting</td></tr>
<tr><td><a href="payment_buckaroo/"><code>payment_buckaroo</code></a></td><td>Payment Provider: Buckaroo</td><td>accounting</td></tr>
<tr><td><a href="payment_custom/"><code>payment_custom</code></a></td><td>Payment Provider: Custom Payment Modes</td><td>accounting</td></tr>
<tr><td><a href="payment_demo/"><code>payment_demo</code></a></td><td>Payment Provider: Demo</td><td>accounting</td></tr>
<tr><td><a href="payment_flutterwave/"><code>payment_flutterwave</code></a></td><td>Payment Provider: Flutterwave</td><td>accounting</td></tr>
<tr><td><a href="payment_mercado_pago/"><code>payment_mercado_pago</code></a></td><td>Payment Provider: Mercado Pago</td><td>accounting</td></tr>
<tr><td><a href="payment_mollie/"><code>payment_mollie</code></a></td><td>Payment Provider: Mollie</td><td>accounting</td></tr>
<tr><td><a href="payment_ogone/"><code>payment_ogone</code></a></td><td>Payment Provider: Ogone</td><td>accounting</td></tr>
<tr><td><a href="payment_paypal/"><code>payment_paypal</code></a></td><td>Payment Provider: Paypal</td><td>accounting</td></tr>
<tr><td><a href="payment_payulatam/"><code>payment_payulatam</code></a></td><td>Payment Provider: PayU Latam</td><td>accounting</td></tr>
<tr><td><a href="payment_payumoney/"><code>payment_payumoney</code></a></td><td>Payment Provider: PayUmoney</td><td>accounting</td></tr>
<tr><td><a href="payment_razorpay/"><code>payment_razorpay</code></a></td><td>Payment Provider: Razorpay</td><td>accounting</td></tr>
<tr><td><a href="payment_razorpay_oauth/"><code>payment_razorpay_oauth</code></a></td><td>Razorpay OAuth Integration</td><td>accounting</td></tr>
<tr><td><a href="payment_sips/"><code>payment_sips</code></a></td><td>Payment Provider: Worldline SIPS</td><td>accounting</td></tr>
<tr><td><a href="payment_stripe/"><code>payment_stripe</code></a></td><td>Payment Provider: Stripe</td><td>accounting</td></tr>
<tr><td><a href="payment_worldline/"><code>payment_worldline</code></a></td><td>Payment Provider: Worldline</td><td>accounting</td></tr>
<tr><td><a href="payment_xendit/"><code>payment_xendit</code></a></td><td>Payment Provider: Xendit</td><td>accounting</td></tr>
<tr><td><a href="phone_validation/"><code>phone_validation</code></a></td><td>Phone Numbers Validation</td><td>platform_core</td></tr>
<tr><td><a href="portal_rating/"><code>portal_rating</code></a></td><td>Portal Rating</td><td>website_ecommerce</td></tr>
<tr><td><a href="privacy_lookup/"><code>privacy_lookup</code></a></td><td>Privacy</td><td>platform_core</td></tr>
<tr><td><a href="project_account/"><code>project_account</code></a></td><td>Project - Account</td><td>projects_services</td></tr>
<tr><td><a href="project_hr_expense/"><code>project_hr_expense</code></a></td><td>Project Expenses</td><td>projects_services</td></tr>
<tr><td><a href="project_mail_plugin/"><code>project_mail_plugin</code></a></td><td>Project Mail Plugin</td><td>projects_services</td></tr>
<tr><td><a href="project_mrp/"><code>project_mrp</code></a></td><td>MRP Project</td><td>projects_services</td></tr>
<tr><td><a href="project_purchase/"><code>project_purchase</code></a></td><td>Project Purchase</td><td>projects_services</td></tr>
<tr><td><a href="project_sale_expense/"><code>project_sale_expense</code></a></td><td>Project - Sale - Expense</td><td>projects_services</td></tr>
<tr><td><a href="project_sms/"><code>project_sms</code></a></td><td>Project - SMS</td><td>projects_services</td></tr>
<tr><td><a href="project_timesheet_holidays/"><code>project_timesheet_holidays</code></a></td><td>Timesheet when on Time Off</td><td>projects_services</td></tr>
<tr><td><a href="project_todo/"><code>project_todo</code></a></td><td>To-Do</td><td>projects_services</td></tr>
<tr><td><a href="resource/"><code>resource</code></a></td><td>Resource</td><td>platform_core</td></tr>
<tr><td><a href="sales_team/"><code>sales_team</code></a></td><td>Sales Teams</td><td>sales_crm</td></tr>
<tr><td><a href="sms_twilio/"><code>sms_twilio</code></a></td><td>Twilio SMS</td><td>integrations</td></tr>
<tr><td><a href="snailmail_account/"><code>snailmail_account</code></a></td><td>Snail Mail - Account</td><td>platform_core</td></tr>
<tr><td><a href="social_media/"><code>social_media</code></a></td><td>Social Media</td><td>platform_core</td></tr>
<tr><td><a href="test_access_rights/"><code>test_access_rights</code></a></td><td>test of access rights and rules</td><td>platform_core</td></tr>
<tr><td><a href="test_action_bindings/"><code>test_action_bindings</code></a></td><td>Test Action Bindings</td><td>platform_core</td></tr>
<tr><td><a href="test_apikeys/"><code>test_apikeys</code></a></td><td>Tests flow of API keys</td><td>platform_core</td></tr>
<tr><td><a href="test_assetsbundle/"><code>test_assetsbundle</code></a></td><td>test-assetsbundle</td><td>platform_core</td></tr>
<tr><td><a href="test_auth_custom/"><code>test_auth_custom</code></a></td><td>Tests that custom auth works & is not impaired by CORS</td><td>platform_core</td></tr>
<tr><td><a href="test_base_automation/"><code>test_base_automation</code></a></td><td>Test - Base Automation</td><td>platform_core</td></tr>
<tr><td><a href="test_base_import/"><code>test_base_import</code></a></td><td>Test - Base Import</td><td>platform_core</td></tr>
<tr><td><a href="test_convert/"><code>test_convert</code></a></td><td>test_convert</td><td>platform_core</td></tr>
<tr><td><a href="test_converter/"><code>test_converter</code></a></td><td>test-field-converter</td><td>platform_core</td></tr>
<tr><td><a href="test_crm_full/"><code>test_crm_full</code></a></td><td>Test Full Crm Flow</td><td>platform_core</td></tr>
<tr><td><a href="test_data_module/"><code>test_data_module</code></a></td><td>test module to test data only modules</td><td>platform_core</td></tr>
<tr><td><a href="test_data_module_install/"><code>test_data_module_install</code></a></td><td>test installation of data module</td><td>platform_core</td></tr>
<tr><td><a href="test_discuss_full/"><code>test_discuss_full</code></a></td><td>Test Discuss (full)</td><td>platform_core</td></tr>
<tr><td><a href="test_event_full/"><code>test_event_full</code></a></td><td>Test Full Event Flow</td><td>platform_core</td></tr>
<tr><td><a href="test_exceptions/"><code>test_exceptions</code></a></td><td>test-exceptions</td><td>platform_core</td></tr>
<tr><td><a href="test_html_field_history/"><code>test_html_field_history</code></a></td><td>Test - html_field_history</td><td>platform_core</td></tr>
<tr><td><a href="test_http/"><code>test_http</code></a></td><td>Test HTTP</td><td>platform_core</td></tr>
<tr><td><a href="test_impex/"><code>test_impex</code></a></td><td>test-import-export</td><td>platform_core</td></tr>
<tr><td><a href="test_inherit/"><code>test_inherit</code></a></td><td>test-inherit</td><td>platform_core</td></tr>
<tr><td><a href="test_inherit_depends/"><code>test_inherit_depends</code></a></td><td>test-inherit-depends</td><td>platform_core</td></tr>
<tr><td><a href="test_inherits/"><code>test_inherits</code></a></td><td>test-inherits</td><td>platform_core</td></tr>
<tr><td><a href="test_inherits_depends/"><code>test_inherits_depends</code></a></td><td>test-inherits-depends</td><td>platform_core</td></tr>
<tr><td><a href="test_limits/"><code>test_limits</code></a></td><td>test-limits</td><td>platform_core</td></tr>
<tr><td><a href="test_lint/"><code>test_lint</code></a></td><td>test-lint</td><td>platform_core</td></tr>
<tr><td><a href="test_mail/"><code>test_mail</code></a></td><td>Mail Tests</td><td>platform_core</td></tr>
<tr><td><a href="test_mail_full/"><code>test_mail_full</code></a></td><td>Mail Tests (Full)</td><td>platform_core</td></tr>
<tr><td><a href="test_mail_sms/"><code>test_mail_sms</code></a></td><td>SMS Tests</td><td>platform_core</td></tr>
<tr><td><a href="test_main_flows/"><code>test_main_flows</code></a></td><td>Test Main Flow</td><td>platform_core</td></tr>
<tr><td><a href="test_mass_mailing/"><code>test_mass_mailing</code></a></td><td>Mass Mail Tests</td><td>platform_core</td></tr>
<tr><td><a href="test_mimetypes/"><code>test_mimetypes</code></a></td><td>test mimetypes-guessing</td><td>platform_core</td></tr>
<tr><td><a href="test_new_api/"><code>test_new_api</code></a></td><td>Test API</td><td>platform_core</td></tr>
<tr><td><a href="test_performance/"><code>test_performance</code></a></td><td>Test Performance</td><td>platform_core</td></tr>
<tr><td><a href="test_populate/"><code>test_populate</code></a></td><td>test-populate</td><td>platform_core</td></tr>
<tr><td><a href="test_read_group/"><code>test_read_group</code></a></td><td>test read_group</td><td>platform_core</td></tr>
<tr><td><a href="test_resource/"><code>test_resource</code></a></td><td>Test - Resource</td><td>platform_core</td></tr>
<tr><td><a href="test_rpc/"><code>test_rpc</code></a></td><td>Test RPC</td><td>platform_core</td></tr>
<tr><td><a href="test_sale_product_configurators/"><code>test_sale_product_configurators</code></a></td><td>Sale Product Configurators Tests</td><td>platform_core</td></tr>
<tr><td><a href="test_search_panel/"><code>test_search_panel</code></a></td><td>test_search_panel</td><td>platform_core</td></tr>
<tr><td><a href="test_spreadsheet/"><code>test_spreadsheet</code></a></td><td>Spreadsheet Test</td><td>platform_core</td></tr>
<tr><td><a href="test_testing_utilities/"><code>test_testing_utilities</code></a></td><td>Test testing utilities</td><td>platform_core</td></tr>
<tr><td><a href="test_translation_import/"><code>test_translation_import</code></a></td><td>test-translation-import</td><td>platform_core</td></tr>
<tr><td><a href="test_uninstall/"><code>test_uninstall</code></a></td><td>test-uninstall</td><td>platform_core</td></tr>
<tr><td><a href="test_website/"><code>test_website</code></a></td><td>Website Test</td><td>platform_core</td></tr>
<tr><td><a href="test_website_modules/"><code>test_website_modules</code></a></td><td>Website Modules Test</td><td>platform_core</td></tr>
<tr><td><a href="test_website_slides_full/"><code>test_website_slides_full</code></a></td><td>Test Full eLearning Flow</td><td>platform_core</td></tr>
<tr><td><a href="test_xlsx_export/"><code>test_xlsx_export</code></a></td><td>test xlsx export</td><td>platform_core</td></tr>
<tr><td><a href="theme_default/"><code>theme_default</code></a></td><td>Default Theme</td><td>website_ecommerce</td></tr>
<tr><td><a href="transifex/"><code>transifex</code></a></td><td>Transifex integration</td><td>platform_core</td></tr>
<tr><td><a href="web_editor/"><code>web_editor</code></a></td><td>Web Editor</td><td>platform_core</td></tr>
<tr><td><a href="web_hierarchy/"><code>web_hierarchy</code></a></td><td>Web Hierarchy</td><td>platform_core</td></tr>
<tr><td><a href="web_tour/"><code>web_tour</code></a></td><td>Tours</td><td>platform_core</td></tr>
<tr><td><a href="web_unsplash/"><code>web_unsplash</code></a></td><td>Unsplash Image Library</td><td>platform_core</td></tr>
</tbody></table>
