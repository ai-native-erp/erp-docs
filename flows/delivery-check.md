---
layout: flow
title: "Delivery Check"
subtitle: "End-to-end flow"
permalink: /flows/delivery-check/
nav_order: 0
nav_title: "Delivery Check"
---
# Delivery Check

## Summary

Bale scan + barcode sheet, partial receipt auto-creates backorder.

## Underpinning modules

- [`stock`](../../modules/stock/)
- [`barcodes`](../../modules/barcodes/)
- [`dynamic_label`](../../modules/dynamic_label/)

## Custom addons involved

- [`dynamic_label`](../../custom-addons/dynamic_label/) — Zebra/PRN barcode sheet + reprint gating.

## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
