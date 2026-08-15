---
layout: page
title: "runtime-registry:cmr-backup-restore-capacity"
subtitle: "Learning — base"
permalink: /decisions/2026-08-12-cmr-backup-restore-capacity/
nav_order: 0
---
# runtime-registry:cmr-backup-restore-capacity

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-12T14:33:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_scan</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">CMR/db_dump manifests and SQL dumps; PostgreSQL restore and Odoo registry smoke tests</div></div>
</div>

## Claim

CMR backups must be identified by installed module profile, restored with their matching filestore, and sized for PostgreSQL data plus indexes at both the Colima virtual-disk and macOS host layers. The Store production dump restores and starts on Odoo 17 after providing the undeclared httpagentparser and paramiko dependencies. The HO production dump requires more than 42 GiB of Docker storage, substantial host headroom, its matching filestore, and the licensed Enterprise 17 addon source; an enterprise activation code alone does not provide that source.

## Verification

verified_by_test

## Implementation

tools/cmr_restore.sh; requirements-cmr.txt; docs/cmr-docker-deployment.md

## Related agents

- `module.base`
- `module.web`
- `module.point_of_sale`
- `module.stock`
- `platform.runtime-registry`
- `platform.upgrade-migration`
- `platform.testing-performance`
- `platform.security-access`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/modules/web/overview.md`
- `knowledge/modules/point_of_sale/overview.md`
- `knowledge/modules/stock/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/upgrade-migration.md`
- `knowledge/base-platform/testing-performance.md`
- `knowledge/base-platform/security-access.md`

## Affected entities

- `runtime-registry`
- `upgrade-migration`
- `testing-performance`
- `security-access`

## Raw record

```json
{
  "id": "runtime-registry:cmr-backup-restore-capacity",
  "module": "base",
  "claim": "CMR backups must be identified by installed module profile, restored with their matching filestore, and sized for PostgreSQL data plus indexes at both the Colima virtual-disk and macOS host layers. The Store production dump restores and starts on Odoo 17 after providing the undeclared httpagentparser and paramiko dependencies. The HO production dump requires more than 42 GiB of Docker storage, substantial host headroom, its matching filestore, and the licensed Enterprise 17 addon source; an enterprise activation code alone does not provide that source.",
  "source_type": "local_scan",
  "source": "CMR/db_dump manifests and SQL dumps; PostgreSQL restore and Odoo registry smoke tests",
  "odoo_version": "17.0",
  "observed_at": "2026-08-12T14:33:00Z",
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
    },
    {
      "kind": "platform",
      "id": "security-access",
      "impact": "related"
    }
  ],
  "related_modules": [
    "base",
    "web",
    "point_of_sale",
    "stock"
  ],
  "related_agents": [
    "module.base",
    "module.web",
    "module.point_of_sale",
    "module.stock",
    "platform.runtime-registry",
    "platform.upgrade-migration",
    "platform.testing-performance",
    "platform.security-access"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/modules/web/overview.md",
    "knowledge/modules/point_of_sale/overview.md",
    "knowledge/modules/stock/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/upgrade-migration.md",
    "knowledge/base-platform/testing-performance.md",
    "knowledge/base-platform/security-access.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:cmr-endpoint-bootstrap-enterprise-gate",
      "relation": "extends"
    },
    {
      "id": "runtime-registry:cmr-ho-store-isolation",
      "relation": "implements"
    },
    {
      "id": "security-access:licensing-aware-product-architecture",
      "relation": "constrained_by"
    }
  ],
  "implementation": "tools/cmr_restore.sh; requirements-cmr.txt; docs/cmr-docker-deployment.md"
}
```