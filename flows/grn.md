---
layout: flow
title: "Receipt (GRN)"
subtitle: "End-to-end flow"
permalink: /flows/grn/
nav_order: 0
nav_title: "Receipt (GRN)"
---
# Receipt (GRN)

## Summary

Header (Receive From, Excess/Shortage, Stock Type, Landed Cost), per-row barcode print, Excess/Shortage reconciliation, dual barcode model, product age code, Label Click Count = one-time-print gate.

## Underpinning modules

- [`stock`](../../modules/stock/)
- [`stock_landed_costs`](../../modules/stock_landed_costs/)
- [`stock_account`](../../modules/stock_account/)
- [`dynamic_label`](../../modules/dynamic_label/)
- [`barcodes`](../../modules/barcodes/)

## Custom addons involved

- [`dynamic_label`](../../custom-addons/dynamic_label/) — Zebra/PRN barcode sheet + reprint gating.

## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
