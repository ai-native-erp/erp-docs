---
layout: flow
title: "Promotion Engine"
subtitle: "End-to-end flow"
permalink: /flows/promotion/
nav_order: 0
nav_title: "Promotion Engine"
---
# Promotion Engine

## Summary

Multiple simultaneous promotion logics, assortment pool with include/exclude, value-based or qty-based slabs, slab-independent benefit (flat discount / X from buy pool / X from get pool), lowest-price-first ranking for freebies.

## Underpinning modules

- [`sale_loyalty`](../../modules/sale_loyalty/)
- [`sale_coupon`](../../modules/sale_coupon/)
- [`point_of_sale`](../../modules/point_of_sale/)
- [`pos_loyalty`](../../modules/pos_loyalty/)

## Custom addons involved

- [`nhcl_pos_sale`](../../custom-addons/nhcl_pos_sale/) — POS-side extension feeding outbox + ack and credit-note flow.
- [`bi_pos_upi_payment`](../../custom-addons/bi_pos_upi_payment/) — UPI payment terminal.

## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
