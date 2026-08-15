---
layout: page
title: "Reference"
subtitle: "Document numbering, journal entry mapping, known-flaw registry."
permalink: /reference/
nav_order: 9
---
## Document numbering scheme

Every document follows `{LocationCode}/{DocTypeCode}/{PeriodCode}/{Sequence}[/{SubSequence}]`:

- **LocationCode** — `HO` / `WH1` / `WH2` / `S01` / `S02` / … Guarantees global uniqueness without a central counter.
- **DocTypeCode** — short code per document type.
- **PeriodCode** — fiscal-period rolling code shared with item aging.
- **Sequence** — zero-padded counter, local to Location + DocType + Period, resets each period.
- **SubSequence** — physical sub-units (bale/packet/line barcode).

Example: `S07/BTI/H2/000482` — Store 07's 482nd Batch Transfer In in period H2. A bale within it: `S07/BTI/H2/000482/03`.

| Module | Doc type | Code |
|---|---|---|
| §3.1 | Purchase Indent | `PI` |
| §3.2 | Purchase Order | `PO` |
| §3.3 | Logistic Entry (LR) | `LG` |
| §3.4 | Transport Check | `TC` |
| §3.5 | Delivery Check | `DC` |
| §3.7 | Receipt (GRN) | `IN` |
| §3.8 | Sales Order – Packet | `SO` |
| §3.9 | Delivery / Delivery Adhoc | `OUT` |
| §3.10 | Batch Transfer Out | `BTO` |
| §3.11 | Batch Transfer In | `BTI` |
| §3.12 | Physical Inventory Adjustment | `PIA` |
| §3.13 | Opening Balance Adjustment | `OB` |
| §3.14 | Conversion Issue (Job Work) | `CIJ` |
| §3.15 | Conversion Receive (Sub-Contracting) | `CRS` |
| §8 | POS Bill | `POS` |
| §8 | Credit Note | `CN` |
| §8 | Debit Note | `DN` |
| §7 | Vendor Return | `VR` |

## Journal entry mapping

| Event | Journal entry effect |
|---|---|
| GRN (goods receipt) | Dr. Inventory, Cr. GR/IR (vendor accrual) |
| Vendor bill match | Dr. GR/IR, Cr. Accounts Payable (vendor) |
| Vendor return / debit note | Dr. Accounts Payable (vendor), Cr. Inventory; credit note received reduces payable further |
| Store transfer (intra-company) | Inventory movement between location accounts — no P&L impact, but still ledgered for valuation |
| Physical inventory adjustment | Dr./Cr. Inventory vs. Stock Adjustment/Shrinkage account, by reason code |
| Opening balance load | Dr. Inventory, Cr. Opening Balance Equity — tagged distinctly from later adjustments |
| Conversion issue (job work) | Inventory moved to an "at job worker" holding account, not expensed |
| Conversion receive (sub-contracting) | Dr. Finished Inventory, Cr. WIP/job-work holding, plus Dr. job-work charges, Cr. Accounts Payable (job-work vendor) |
| POS sale | Dr. Cash/Card/Accounts Receivable, Cr. Revenue, Cr. Tax Payable, Dr. COGS / Cr. Inventory — each posted against the bill's cost center |
| POS return | Reverse of sale entry, scoped to the specific serial/barcode |
| MOP change after session close | A correcting journal entry, never a raw edit to the original posting |

## Known-flaw registry

| Symptom | Root cause | Countermeasure in this repo |
|---|---|---|
| Batch transfer shows "integrated: Yes" at HO but store never receives it | No acknowledgment contract; one-directional write with no confirm step | Outbox + ack pattern ([architecture](/architecture/)) implemented in [`nhcl_ho_store_cmr_integration`](/custom-addons/nhcl_ho_store_cmr_integration/) + [`nhcl_store_to_ho_transactions`](/custom-addons/nhcl_store_to_ho_transactions/) |
| Promotion sync unreliable for months | Fire-and-forget | Same outbox + ack, applied to promotion distribution |
| Store-to-HO sync lags HO-to-store | Reverse direction built later, as an afterthought | Both directions built symmetrically from day one |
| GRC-with-backorder takes 30–40 min to save | Backorder creation is synchronous inside the save transaction | Backorder creation goes through async jobs/cron |
| RSP of 555 rounded to 599 | Rounding rule applied unconditionally | "Angle Number" margin type bypasses rounding |
| 5% tax applied above a boundary that should be 18% | Tax slab modeled as an untested lookup | Rule-priority tax engine with explicit boundary tests, backed by `account_tax_python` + [`hsn_code_automation_management`](/custom-addons/hsn_code_automation_management/) |
| Promotion under-applies tiered discount | Promotion engine not tested before going live | Pre-integration sample/test mode before store rollout |
| Book inventory and physical inventory disagree after a bad batch receipt | No mechanism to trace last known physical scan location | Last-scanned report ([`transport_dashboard`](/custom-addons/transport_dashboard/)) |
