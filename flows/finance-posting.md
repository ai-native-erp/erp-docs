---
layout: flow
title: "Finance Posting"
subtitle: "End-to-end flow"
permalink: /flows/finance-posting/
nav_order: 0
nav_title: "Finance Posting"
---
# Finance Posting

## Summary

Every value-bearing transaction generates a journal entry against the correct vendor / customer / GL account + cost center. Async posting for backorders, excess/shortage reconciliation, conversion variance.

## Underpinning modules

- [`account`](../../modules/account/)
- [`account_accountant`](../../modules/account_accountant/)
- [`account_edi`](../../modules/account_edi/)
- [`stock_account`](../../modules/stock_account/)
- [`l10n_in_edi`](../../modules/l10n_in_edi/)
- [`l10n_in_e_invoice_lax`](../../modules/l10n_in_e_invoice_lax/)

## Custom addons involved

- [`hsn_code_automation_management`](../../custom-addons/hsn_code_automation_management/) — HSN/SAC and category-priority GST rules.
- [`l10n_in_e_invoice_lax`](../../custom-addons/l10n_in_e_invoice_lax/) — IRN alongside e-way bill.

## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
