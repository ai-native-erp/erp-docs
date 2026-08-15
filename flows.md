---
layout: page
title: "End-to-end flows"
subtitle: "The retail pipeline — from PI through POS and returns."
permalink: /flows/
nav_order: 3
---
This is the end-to-end pipeline covered by the retail reference doc, mapped onto Odoo modules and the CMR customizations.

<table>
<thead><tr><th>Flow</th><th>Modules</th><th>Detail</th></tr></thead>
<tbody>
<tr><td><a href="#pi">Purchase Indent (PI)</a></td><td><code>purchase</code>, <code>internal_purchase_indent</code>, <code>product</code>, <code>approval</code></td><td>see below</td></tr>
<tr><td><a href="#po">Purchase Order (PO)</a></td><td><code>purchase</code>, <code>purchase_stock</code></td><td>see below</td></tr>
<tr><td><a href="#lr-entry">Logistic Entry (LR)</a></td><td><code>purchase</code>, <code>transport_dashboard</code></td><td>see below</td></tr>
<tr><td><a href="#transport-check">Transport Check</a></td><td><code>purchase</code>, <code>transport_dashboard</code></td><td>see below</td></tr>
<tr><td><a href="#delivery-check">Delivery Check</a></td><td><code>stock</code>, <code>barcodes</code>, <code>dynamic_label</code></td><td>see below</td></tr>
<tr><td><a href="#open-parcel">Open Parcel</a></td><td><code>stock</code>, <code>transport_dashboard</code></td><td>see below</td></tr>
<tr><td><a href="#grn">Receipt (GRN)</a></td><td><code>stock</code>, <code>stock_landed_costs</code>, <code>stock_account</code>, <code>dynamic_label</code>, <code>barcodes</code></td><td>see below</td></tr>
<tr><td><a href="#so-packet">Sales Order – Packet</a></td><td><code>sale</code>, <code>sale_stock</code>, <code>sale_order_extension</code></td><td>see below</td></tr>
<tr><td><a href="#delivery">Delivery / Delivery Adhoc</a></td><td><code>sale_stock</code>, <code>delivery</code></td><td>see below</td></tr>
<tr><td><a href="#batch-transfer-out">Batch Transfer Out</a></td><td><code>stock</code>, <code>lax_ewaybill</code>, <code>lax_ewaybill_batch</code>, <code>l10n_in_e_invoice_lax</code>, <code>nhcl_ho_store_cmr_integration</code></td><td>see below</td></tr>
<tr><td><a href="#batch-transfer-in">Batch Transfer In</a></td><td><code>stock</code>, <code>stock_account</code>, <code>barcodes</code>, <code>transport_dashboard</code></td><td>see below</td></tr>
<tr><td><a href="#adjustment">Physical Inventory Adjustment</a></td><td><code>stock</code>, <code>stock_account</code>, <code>stock_inventory_count_tus</code></td><td>see below</td></tr>
<tr><td><a href="#opening-balance">Opening Balance as Adjustment</a></td><td><code>stock</code>, <code>stock_account</code></td><td>see below</td></tr>
<tr><td><a href="#conversion-issue">Conversion – Issue for Job Work</a></td><td><code>mrp</code>, <code>mrp_subcontracting</code>, <code>stock_account</code></td><td>see below</td></tr>
<tr><td><a href="#conversion-receive">Conversion – Receive (Sub-Contracting)</a></td><td><code>mrp</code>, <code>mrp_subcontracting</code>, <code>account</code></td><td>see below</td></tr>
<tr><td><a href="#price-change">Price Change / Correction</a></td><td><code>product</code>, <code>account</code>, <code>account_accountant</code></td><td>see below</td></tr>
<tr><td><a href="#pos-bill">POS Bill</a></td><td><code>point_of_sale</code>, <code>pos_loyalty</code>, <code>pos_sale</code>, <code>nhcl_pos_sale</code>, <code>bi_pos_upi_payment</code></td><td>see below</td></tr>
<tr><td><a href="#promotion">Promotion Engine</a></td><td><code>sale_loyalty</code>, <code>sale_coupon</code>, <code>point_of_sale</code>, <code>pos_loyalty</code></td><td>see below</td></tr>
<tr><td><a href="#vendor-return">Vendor Return</a></td><td><code>purchase</code>, <code>account</code>, <code>stock</code>, <code>point_of_sale</code></td><td>see below</td></tr>
<tr><td><a href="#finance-posting">Finance Posting</a></td><td><code>account</code>, <code>account_accountant</code>, <code>account_edi</code>, <code>stock_account</code>, <code>l10n_in_edi</code>, <code>l10n_in_e_invoice_lax</code></td><td>see below</td></tr>
</tbody></table>
