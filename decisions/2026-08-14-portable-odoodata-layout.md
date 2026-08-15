---
layout: page
title: "runtime-registry:portable-odoodata-layout"
subtitle: "Learning — base"
permalink: /decisions/2026-08-14-portable-odoodata-layout/
nav_order: 0
---
# runtime-registry:portable-odoodata-layout

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-14T02:00:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">/Volumes/OdooData portable instance relocation and post-relocation service validation</div></div>
</div>

## Claim

For this Odoo 17 development instance, the Git workspace, licensed addon sources, source backups, and the complete Colima runtime are colocated on /Volumes/OdooData. The original project and Colima paths are compatibility symlinks; the Colima runtime contains the Docker images, containers, and named volumes, while a generated inventory and image archive provide secondary recovery inputs. Colima must be stopped before the SSD is detached.

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
  "id": "runtime-registry:portable-odoodata-layout",
  "module": "base",
  "claim": "For this Odoo 17 development instance, the Git workspace, licensed addon sources, source backups, and the complete Colima runtime are colocated on /Volumes/OdooData. The original project and Colima paths are compatibility symlinks; the Colima runtime contains the Docker images, containers, and named volumes, while a generated inventory and image archive provide secondary recovery inputs. Colima must be stopped before the SSD is detached.",
  "source_type": "local_test",
  "source": "/Volumes/OdooData portable instance relocation and post-relocation service validation",
  "odoo_version": "17.0",
  "observed_at": "2026-08-14T02:00:00Z",
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
      "id": "runtime-registry:external-colima-capacity",
      "relation": "depends_on"
    },
    {
      "id": "runtime-registry:customer-addon-mount-preflight",
      "relation": "related_to"
    },
    {
      "id": "runtime-registry:ho-enterprise-source-restored",
      "relation": "impacts"
    }
  ]
}
```