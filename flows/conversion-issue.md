---
layout: flow
title: "Conversion – Issue for Job Work"
subtitle: "End-to-end flow"
permalink: /flows/conversion-issue/
nav_order: 0
nav_title: "Conversion – Issue for Job Work"
---
# Conversion – Issue for Job Work

## Summary

Raw/unfinished issued to job-work vendor. On-hand moves to 'at job worker' holding account. Expected return date + input quantity/attributes tracked.

## Underpinning modules

- [`mrp`](../../modules/mrp/)
- [`mrp_subcontracting`](../../modules/mrp_subcontracting/)
- [`stock_account`](../../modules/stock_account/)

## Custom addons involved


## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
