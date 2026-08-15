---
layout: flow
title: "Purchase Indent (PI)"
subtitle: "End-to-end flow"
permalink: /flows/pi/
nav_order: 0
nav_title: "Purchase Indent (PI)"
---
# Purchase Indent (PI)

## Summary

Header (PI Type, Vendor, Validity, Purchase Type, Agent, Transporter), MBQ + RSP approval matrix, category-team vs. brand-blanket-order paths, pricing formula (Cost + Default Margin → tax → 49/99), and Angle Number bypass.

## Underpinning modules

- [`purchase`](../../modules/purchase/)
- [`internal_purchase_indent`](../../modules/internal_purchase_indent/)
- [`product`](../../modules/product/)
- [`approval`](../../modules/approval/)

## Custom addons involved

- [`internal_purchase_indent`](../../custom-addons/internal_purchase_indent/) — native PI document type.

## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
