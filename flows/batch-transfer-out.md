---
layout: flow
title: "Batch Transfer Out"
subtitle: "End-to-end flow"
permalink: /flows/batch-transfer-out/
nav_order: 0
nav_title: "Batch Transfer Out"
---
# Batch Transfer Out

## Summary

Store-scoped team selects ready packets, issues as one transaction. Intra/inter-state TO type drives E-Way Bill + E-Invoice. HO stock → in-transit. Batch transfer number syncs to destination store via outbox + ack.

## Underpinning modules

- [`stock`](../../modules/stock/)
- [`lax_ewaybill`](../../modules/lax_ewaybill/)
- [`lax_ewaybill_batch`](../../modules/lax_ewaybill_batch/)
- [`l10n_in_e_invoice_lax`](../../modules/l10n_in_e_invoice_lax/)
- [`nhcl_ho_store_cmr_integration`](../../modules/nhcl_ho_store_cmr_integration/)

## Custom addons involved

- [`transport_dashboard`](../../custom-addons/transport_dashboard/) — bale card kanban, last-scanned report.
- [`lax_ewaybill`](../../custom-addons/lax_ewaybill/) / [`lax_ewaybill_batch`](../../custom-addons/lax_ewaybill_batch/) — Indian e-way bill generation.
- [`nhcl_ho_store_cmr_integration`](../../custom-addons/nhcl_ho_store_cmr_integration/) — HO↔Store sync.
- [`nhcl_store_to_ho_transactions`](../../custom-addons/nhcl_store_to_ho_transactions/) — Store→HO sync.
- [`nhcl_ho_store_cmr_integration`](../../custom-addons/nhcl_ho_store_cmr_integration/) — outbox + ack sync to store.

## Status / approval state machine

See the wiki excerpt in the module pages above for the canonical state machine; the retail reference doc specifies the per-document status enum (Draft → In Transit → Received → Posted, with Pending/Partial/Completed sub-states for batch transfers).

## Known-flaw countermeasures

See [Reference → Known-flaw registry](/reference/#known-flaw-registry) for the production-flaw table and how each countermeasure is implemented in the modules above.
