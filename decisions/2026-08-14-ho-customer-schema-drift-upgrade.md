---
layout: page
title: "upgrade-migration:ho-customer-schema-drift-upgrade"
subtitle: "Learning — base"
permalink: /decisions/2026-08-14-ho-customer-schema-drift-upgrade/
nav_order: 0
---
# upgrade-migration:ho-customer-schema-drift-upgrade

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-14T02:34:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">cmr_ho_test and disposable clone cmr_ho_upgrade_test_20260814; Odoo 17 module upgrade and registry schema scan</div></div>
</div>

## Claim

After restoring the HO Odoo 17 database against a newer customer-addon source tree, a normal registry load can expose stored Python fields that are absent from PostgreSQL. The observed purchase.order.line.descrip_8 failure was part of 49 missing stored columns or transient-table columns owned by cmr_customizations, nhcl_ho_store_cmr_integration, and internal_purchase_indent. Upgrading those three modules on a disposable database clone first, then applying the identical upgrade to HO, reduced the registry-to-schema mismatch count to zero and restored the stock-picking compute/read path. A one-column ALTER would not have repaired the wider drift.

## Verification

verified_by_test

## Related agents

- `module.base`
- `module.purchase`
- `module.stock`
- `platform.upgrade-migration`
- `platform.runtime-registry`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/modules/purchase/overview.md`
- `knowledge/modules/stock/overview.md`
- `knowledge/base-platform/upgrade-migration.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `purchase.order.line`
- `stock.picking`
- `cmr_customizations`
- `nhcl_ho_store_cmr_integration`
- `internal_purchase_indent`
- `upgrade-migration`
- `runtime-registry`
- `testing-performance`

## Raw record

```json
{
  "id": "upgrade-migration:ho-customer-schema-drift-upgrade",
  "module": "base",
  "claim": "After restoring the HO Odoo 17 database against a newer customer-addon source tree, a normal registry load can expose stored Python fields that are absent from PostgreSQL. The observed purchase.order.line.descrip_8 failure was part of 49 missing stored columns or transient-table columns owned by cmr_customizations, nhcl_ho_store_cmr_integration, and internal_purchase_indent. Upgrading those three modules on a disposable database clone first, then applying the identical upgrade to HO, reduced the registry-to-schema mismatch count to zero and restored the stock-picking compute/read path. A one-column ALTER would not have repaired the wider drift.",
  "source_type": "local_test",
  "source": "cmr_ho_test and disposable clone cmr_ho_upgrade_test_20260814; Odoo 17 module upgrade and registry schema scan",
  "odoo_version": "17.0",
  "observed_at": "2026-08-14T02:34:00Z",
  "confidence": "high",
  "verification": "verified_by_test",
  "affected_entities": [
    {
      "kind": "model",
      "id": "purchase.order.line",
      "impact": "direct"
    },
    {
      "kind": "model",
      "id": "stock.picking",
      "impact": "direct"
    },
    {
      "kind": "module",
      "id": "cmr_customizations",
      "impact": "direct"
    },
    {
      "kind": "module",
      "id": "nhcl_ho_store_cmr_integration",
      "impact": "direct"
    },
    {
      "kind": "module",
      "id": "internal_purchase_indent",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "upgrade-migration",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "runtime-registry",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "testing-performance",
      "impact": "direct"
    }
  ],
  "related_modules": [
    "base",
    "purchase",
    "stock"
  ],
  "related_agents": [
    "module.base",
    "module.purchase",
    "module.stock",
    "platform.upgrade-migration",
    "platform.runtime-registry",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/modules/purchase/overview.md",
    "knowledge/modules/stock/overview.md",
    "knowledge/base-platform/upgrade-migration.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:ho-enterprise-source-restored",
      "relation": "related_to"
    },
    {
      "id": "runtime-registry:ho-enterprise-view-compatibility",
      "relation": "related_to"
    },
    {
      "id": "runtime-registry:portable-odoodata-layout",
      "relation": "depends_on"
    }
  ]
}
```