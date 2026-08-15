---
layout: flow
title: "Purchase Order (PO)"
subtitle: "End-to-end flow"
permalink: /flows/po/
nav_order: 0
nav_title: "Purchase Order (PO)"
---
# Purchase Order (PO)

## Summary

PI converts to PO on approval. Agent/Transporter remain editable. Configurable T&C template, PT file bulk-load for products/attributes.

## Underpinning modules

- [`purchase`](../../modules/purchase/)
- [`purchase_stock`](../../modules/purchase_stock/)

## Custom addons involved

- [`internal_purchase_indent`](../../custom-addons/internal_purchase_indent/) — native PI document type.

## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
