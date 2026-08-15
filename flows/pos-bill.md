---
layout: flow
title: "POS Bill"
subtitle: "End-to-end flow"
permalink: /flows/pos-bill/
nav_order: 0
nav_title: "POS Bill"
---
# POS Bill

## Summary

Bill creation/cancellation with reasons, customer creation, loyalty accrual/redemption, credit note issue vs. settlement as distinct events, server-side offer check, per-line sales incentive, equal discount apportionment, hard transactional constraints.

## Underpinning modules

- [`point_of_sale`](../../modules/point_of_sale/)
- [`pos_loyalty`](../../modules/pos_loyalty/)
- [`pos_sale`](../../modules/pos_sale/)
- [`nhcl_pos_sale`](../../modules/nhcl_pos_sale/)
- [`bi_pos_upi_payment`](../../modules/bi_pos_upi_payment/)

## Custom addons involved

- [`nhcl_pos_sale`](../../custom-addons/nhcl_pos_sale/) — POS-side extension feeding outbox + ack and credit-note flow.
- [`bi_pos_upi_payment`](../../custom-addons/bi_pos_upi_payment/) — UPI payment terminal.

## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
