---
layout: flow
title: "Sales Order – Packet"
subtitle: "End-to-end flow"
permalink: /flows/so-packet/
nav_order: 0
nav_title: "Sales Order – Packet"
---
# Sales Order – Packet

## Summary

Dispatch team sees store indents + available inventory. Scanning builds packets. Confirmation registers each packet as a Sales Order — formal stock reservation.

## Underpinning modules

- [`sale`](../../modules/sale/)
- [`sale_stock`](../../modules/sale_stock/)
- [`sale_order_extension`](../../modules/sale_order_extension/)

## Custom addons involved


## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
