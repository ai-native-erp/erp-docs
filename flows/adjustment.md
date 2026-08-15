---
layout: flow
title: "Physical Inventory Adjustment"
subtitle: "End-to-end flow"
permalink: /flows/adjustment/
nav_order: 0
nav_title: "Physical Inventory Adjustment"
---
# Physical Inventory Adjustment

## Summary

Counted vs. book. Delta posted as adjustment event into stock ledger. Reason code + value-threshold approval.

## Underpinning modules

- [`stock`](../../modules/stock/)
- [`stock_account`](../../modules/stock_account/)
- [`stock_inventory_count_tus`](../../modules/stock_inventory_count_tus/)

## Custom addons involved

- [`stock_inventory_count_tus`](../../custom-addons/stock_inventory_count_tus/) — count sheet.

## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
