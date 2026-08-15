---
layout: flow
title: "Delivery / Delivery Adhoc"
subtitle: "End-to-end flow"
permalink: /flows/delivery/
nav_order: 0
nav_title: "Delivery / Delivery Adhoc"
---
# Delivery / Delivery Adhoc

## Summary

Confirmed packet's sales order posts as outbound delivery (`WH/OUT`). Against-indent vs. adhoc metadata.

## Underpinning modules

- [`sale_stock`](../../modules/sale_stock/)
- [`delivery`](../../modules/delivery/)

## Custom addons involved


## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
