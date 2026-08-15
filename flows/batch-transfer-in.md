---
layout: flow
title: "Batch Transfer In"
subtitle: "End-to-end flow"
permalink: /flows/batch-transfer-in/
nav_order: 0
nav_title: "Batch Transfer In"
---
# Batch Transfer In

## Summary

Store scans bale barcode first (destination-locked). Per-item scan. Partial match → backorder + exception report. Last-scanned report feeds the missing-stock investigation.

## Underpinning modules

- [`stock`](../../modules/stock/)
- [`stock_account`](../../modules/stock_account/)
- [`barcodes`](../../modules/barcodes/)
- [`transport_dashboard`](../../modules/transport_dashboard/)

## Custom addons involved

- [`transport_dashboard`](../../custom-addons/transport_dashboard/) — bale card kanban, last-scanned report.
- [`lax_ewaybill`](../../custom-addons/lax_ewaybill/) / [`lax_ewaybill_batch`](../../custom-addons/lax_ewaybill_batch/) — Indian e-way bill generation.
- [`nhcl_ho_store_cmr_integration`](../../custom-addons/nhcl_ho_store_cmr_integration/) — HO↔Store sync.
- [`nhcl_store_to_ho_transactions`](../../custom-addons/nhcl_store_to_ho_transactions/) — Store→HO sync.

## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
