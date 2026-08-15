---
layout: page
title: "runtime-registry:external-colima-capacity"
subtitle: "Learning — base"
permalink: /decisions/2026-08-13-external-colima-capacity/
nav_order: 0
---
# runtime-registry:external-colima-capacity

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-13T11:00:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">Crucial X9 /Volumes/OdooData; Colima data disk; cmr_ho_test restore</div></div>
</div>

## Claim

Moving Colima's sparse runtime files to a larger host volume does not enlarge Docker's guest filesystem. For this Odoo 17 HO restore, the 60 GiB Colima data disk filled during index creation; the Colima disk image, partition, and ext4 filesystem all had to be expanded before the 46 GiB restored database could complete.

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
  "id": "runtime-registry:external-colima-capacity",
  "module": "base",
  "claim": "Moving Colima's sparse runtime files to a larger host volume does not enlarge Docker's guest filesystem. For this Odoo 17 HO restore, the 60 GiB Colima data disk filled during index creation; the Colima disk image, partition, and ext4 filesystem all had to be expanded before the 46 GiB restored database could complete.",
  "source_type": "local_test",
  "source": "Crucial X9 /Volumes/OdooData; Colima data disk; cmr_ho_test restore",
  "odoo_version": "17.0",
  "observed_at": "2026-08-13T11:00:00Z",
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
      "id": "runtime-registry:customer-addon-mount-preflight",
      "relation": "related_to"
    },
    {
      "id": "runtime-registry:ho-enterprise-source-gap",
      "relation": "related_to"
    }
  ]
}
```