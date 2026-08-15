---
layout: flow
title: "Opening Balance as Adjustment"
subtitle: "End-to-end flow"
permalink: /flows/opening-balance/
nav_order: 0
nav_title: "Opening Balance as Adjustment"
---
# Opening Balance as Adjustment

## Summary

Initial stock load / new store go-live / migration from legacy. Distinct 'from zero' reason code so historical opening balances stay separable.

## Underpinning modules

- [`stock`](../../modules/stock/)
- [`stock_account`](../../modules/stock_account/)

## Custom addons involved


## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
