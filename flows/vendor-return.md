---
layout: flow
title: "Vendor Return"
subtitle: "End-to-end flow"
permalink: /flows/vendor-return/
nav_order: 0
nav_title: "Vendor Return"
---
# Vendor Return

## Summary

Universal sell-through rule (50% in 60–90 days; thresholds configurable). Shortage-to-credit-note flow. Last-scanned report. Multi-bill credit-note dashboard. POS-originated branded return chains POS order → promotion → serial → vendor return → credit note.

## Underpinning modules

- [`purchase`](../../modules/purchase/)
- [`account`](../../modules/account/)
- [`stock`](../../modules/stock/)
- [`point_of_sale`](../../modules/point_of_sale/)

## Custom addons involved

- [`nhcl_pos_sale`](../../custom-addons/nhcl_pos_sale/) — POS-side extension feeding outbox + ack and credit-note flow.
- [`bi_pos_upi_payment`](../../custom-addons/bi_pos_upi_payment/) — UPI payment terminal.
- [`gift_voucher_custom`](../../custom-addons/gift_voucher_custom/) — credit-note/settlement separation pattern.

## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
