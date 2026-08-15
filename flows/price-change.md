---
layout: flow
title: "Price Change / Correction"
subtitle: "End-to-end flow"
permalink: /flows/price-change/
nav_order: 0
nav_title: "Price Change / Correction"
---
# Price Change / Correction

## Summary

RSP/MRP change on already-inward stock revalidates against default margin. Below default → RSP approval route. Old/new value + reason + effective date. Triggers finance-visible revaluation.

## Underpinning modules

- [`product`](../../modules/product/)
- [`account`](../../modules/account/)
- [`account_accountant`](../../modules/account_accountant/)

## Custom addons involved


## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
