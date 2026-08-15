---
layout: flow
title: "Open Parcel"
subtitle: "End-to-end flow"
permalink: /flows/open-parcel/
nav_order: 0
nav_title: "Open Parcel"
---
# Open Parcel

## Summary

Kanban of bale cards before warehouse commits the GRN.

## Underpinning modules

- [`stock`](../../modules/stock/)
- [`transport_dashboard`](../../modules/transport_dashboard/)

## Custom addons involved

- [`transport_dashboard`](../../custom-addons/transport_dashboard/) — bale card kanban, last-scanned report.
- [`lax_ewaybill`](../../custom-addons/lax_ewaybill/) / [`lax_ewaybill_batch`](../../custom-addons/lax_ewaybill_batch/) — Indian e-way bill generation.

## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
