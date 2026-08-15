---
layout: page
title: "upgrade-migration:customer-source-lossless-delta-consolidation"
subtitle: "Learning — base"
permalink: /decisions/2026-08-14-customer-source-lossless-delta-consolidation/
nav_order: 0
---
# upgrade-migration:customer-source-lossless-delta-consolidation

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-14T04:05:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">/Volumes/OdooData/ODOO-ERP/RetailEnterprise/HeadOffice and source-deltas/Odoo17-CMR-HO-20260814; live HO registry and HTTP validation</div></div>
</div>

## Claim

When two customer addon trees have no common merge ancestor, a lossless consolidation must not overwrite the running revision blindly. For the retired Odoo 17 source bundle, Store had zero content differences; HO had 74 conflicting source revisions, 15 source-only files, and two workspace-only modules. The 15 missing files were copied into the working HO tree, 89 source-side delta files were retained in a Git-ignored archive, workspace-only modules were preserved, and HO passed compilation, a 359-module registry load, and HTTP health before the old bundle was moved to recoverable Trash.

## Verification

verified_by_test

## Related agents

- `module.base`
- `platform.runtime-registry`
- `platform.upgrade-migration`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/upgrade-migration.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `base`
- `runtime-registry`
- `upgrade-migration`
- `testing-performance`

## Raw record

```json
{
  "id": "upgrade-migration:customer-source-lossless-delta-consolidation",
  "module": "base",
  "claim": "When two customer addon trees have no common merge ancestor, a lossless consolidation must not overwrite the running revision blindly. For the retired Odoo 17 source bundle, Store had zero content differences; HO had 74 conflicting source revisions, 15 source-only files, and two workspace-only modules. The 15 missing files were copied into the working HO tree, 89 source-side delta files were retained in a Git-ignored archive, workspace-only modules were preserved, and HO passed compilation, a 359-module registry load, and HTTP health before the old bundle was moved to recoverable Trash.",
  "source_type": "local_test",
  "source": "/Volumes/OdooData/ODOO-ERP/RetailEnterprise/HeadOffice and source-deltas/Odoo17-CMR-HO-20260814; live HO registry and HTTP validation",
  "odoo_version": "17.0",
  "observed_at": "2026-08-14T04:05:00Z",
  "confidence": "high",
  "verification": "verified_by_test",
  "affected_entities": [
    {
      "kind": "module",
      "id": "base",
      "impact": "direct"
    },
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
    "base"
  ],
  "related_agents": [
    "module.base",
    "platform.runtime-registry",
    "platform.upgrade-migration",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/upgrade-migration.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "licensing-commercial-boundaries:local-proprietary-dependency-consolidation",
      "relation": "depends_on"
    },
    {
      "id": "runtime-registry:portable-odoodata-layout",
      "relation": "impacts"
    },
    {
      "id": "runtime-registry:customer-addon-mount-preflight",
      "relation": "related_to"
    }
  ]
}
```