---
layout: page
title: "runtime-registry:store-missing-filestore-dashboard-repair"
subtitle: "Learning — spreadsheet_dashboard"
permalink: /decisions/2026-08-12-store-missing-filestore-dashboard-repair/
nav_order: 0
---
# runtime-registry:store-missing-filestore-dashboard-repair

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>spreadsheet_dashboard</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-12T15:09:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_scan</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">cmr_store_test ir_attachment records, Store logs, and Odoo 17 spreadsheet dashboard module data files</div></div>
</div>

## Claim

A database-only Store restore preserves ir_attachment metadata but not attachment content. Missing spreadsheet dashboard snapshot files cause spreadsheet_data to decode as an empty value and raise JSONDecodeError in get_readonly_dashboard. Standard dashboards are recoverable by rewriting spreadsheet_binary_data from each owning Odoo module's JSON file through the ORM; customer uploads and other attachments still require the matching Store filestore.

## Verification

verified_by_test

## Implementation

Store database ORM repair of eight module-provided spreadsheet_binary_data values; docs/cmr-docker-deployment.md

## Related agents

- `module.spreadsheet_dashboard`
- `module.spreadsheet_dashboard_sale`
- `module.spreadsheet_dashboard_account`
- `module.spreadsheet_dashboard_stock_account`
- `module.spreadsheet_dashboard_purchase`
- `module.spreadsheet_dashboard_purchase_stock`
- `module.spreadsheet_dashboard_pos_hr`
- `module.spreadsheet_dashboard_hr_expense`
- `platform.runtime-registry`
- `platform.upgrade-migration`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/spreadsheet_dashboard/overview.md`
- `knowledge/modules/spreadsheet_dashboard_sale/overview.md`
- `knowledge/modules/spreadsheet_dashboard_account/overview.md`
- `knowledge/modules/spreadsheet_dashboard_stock_account/overview.md`
- `knowledge/modules/spreadsheet_dashboard_purchase/overview.md`
- `knowledge/modules/spreadsheet_dashboard_purchase_stock/overview.md`
- `knowledge/modules/spreadsheet_dashboard_pos_hr/overview.md`
- `knowledge/modules/spreadsheet_dashboard_hr_expense/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/upgrade-migration.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `runtime-registry`
- `upgrade-migration`
- `testing-performance`

## Raw record

```json
{
  "id": "runtime-registry:store-missing-filestore-dashboard-repair",
  "module": "spreadsheet_dashboard",
  "claim": "A database-only Store restore preserves ir_attachment metadata but not attachment content. Missing spreadsheet dashboard snapshot files cause spreadsheet_data to decode as an empty value and raise JSONDecodeError in get_readonly_dashboard. Standard dashboards are recoverable by rewriting spreadsheet_binary_data from each owning Odoo module's JSON file through the ORM; customer uploads and other attachments still require the matching Store filestore.",
  "source_type": "local_scan",
  "source": "cmr_store_test ir_attachment records, Store logs, and Odoo 17 spreadsheet dashboard module data files",
  "odoo_version": "17.0",
  "observed_at": "2026-08-12T15:09:00Z",
  "confidence": "high",
  "verification": "verified_by_test",
  "affected_entities": [
    {
      "kind": "platform",
      "id": "runtime-registry",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "upgrade-migration",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "testing-performance",
      "impact": "direct"
    }
  ],
  "related_modules": [
    "spreadsheet_dashboard",
    "spreadsheet_dashboard_sale",
    "spreadsheet_dashboard_account",
    "spreadsheet_dashboard_stock_account",
    "spreadsheet_dashboard_purchase",
    "spreadsheet_dashboard_purchase_stock",
    "spreadsheet_dashboard_pos_hr",
    "spreadsheet_dashboard_hr_expense"
  ],
  "related_agents": [
    "module.spreadsheet_dashboard",
    "module.spreadsheet_dashboard_sale",
    "module.spreadsheet_dashboard_account",
    "module.spreadsheet_dashboard_stock_account",
    "module.spreadsheet_dashboard_purchase",
    "module.spreadsheet_dashboard_purchase_stock",
    "module.spreadsheet_dashboard_pos_hr",
    "module.spreadsheet_dashboard_hr_expense",
    "platform.runtime-registry",
    "platform.upgrade-migration",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/spreadsheet_dashboard/overview.md",
    "knowledge/modules/spreadsheet_dashboard_sale/overview.md",
    "knowledge/modules/spreadsheet_dashboard_account/overview.md",
    "knowledge/modules/spreadsheet_dashboard_stock_account/overview.md",
    "knowledge/modules/spreadsheet_dashboard_purchase/overview.md",
    "knowledge/modules/spreadsheet_dashboard_purchase_stock/overview.md",
    "knowledge/modules/spreadsheet_dashboard_pos_hr/overview.md",
    "knowledge/modules/spreadsheet_dashboard_hr_expense/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/upgrade-migration.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:cmr-backup-restore-capacity",
      "relation": "extends"
    },
    {
      "id": "runtime-registry:cmr-ho-store-isolation",
      "relation": "constrained_by"
    }
  ],
  "implementation": "Store database ORM repair of eight module-provided spreadsheet_binary_data values; docs/cmr-docker-deployment.md"
}
```