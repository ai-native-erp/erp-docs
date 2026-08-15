---
layout: flow
title: "Conversion – Receive (Sub-Contracting)"
subtitle: "End-to-end flow"
permalink: /flows/conversion-receive/
nav_order: 0
nav_title: "Conversion – Receive (Sub-Contracting)"
---
# Conversion – Receive (Sub-Contracting)

## Summary

Receive back from job-work vendor, reconciled against the original issue document. Partial returns + wastage/yield variance + job-work charges posted to vendor ledger.

## Underpinning modules

- [`mrp`](../../modules/mrp/)
- [`mrp_subcontracting`](../../modules/mrp_subcontracting/)
- [`account`](../../modules/account/)

## Custom addons involved


## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
