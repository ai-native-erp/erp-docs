---
layout: page
title: "licensing-commercial-boundaries:local-proprietary-dependency-consolidation"
subtitle: "Learning — base"
permalink: /decisions/2026-08-14-local-proprietary-dependency-consolidation/
nav_order: 0
---
# licensing-commercial-boundaries:local-proprietary-dependency-consolidation

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-14T03:45:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">/Volumes/OdooData/ODOO-ERP/.gitignore, .env, compose.yaml and live Docker mount/health validation</div></div>
</div>

## Claim

Licensed Enterprise source and the third-party auto_database_backup addon may be colocated inside the portable ODOO-ERP workspace only as separate Git-ignored dependency trees, not merged into project-owned custom addons. After checksum/count verification, HO and CTL Fashion were switched to enterprise-addons and vendor-addons respectively, recreated, and passed registry health and HTTP checks with no active mounts to the former top-level source paths.

## Verification

verified_by_test

## Related agents

- `module.base`
- `platform.runtime-registry`
- `platform.licensing-commercial-boundaries`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/licensing-commercial-boundaries.md`

## Affected entities

- `base`
- `runtime-registry`
- `licensing-commercial-boundaries`

## Raw record

```json
{
  "id": "licensing-commercial-boundaries:local-proprietary-dependency-consolidation",
  "module": "base",
  "claim": "Licensed Enterprise source and the third-party auto_database_backup addon may be colocated inside the portable ODOO-ERP workspace only as separate Git-ignored dependency trees, not merged into project-owned custom addons. After checksum/count verification, HO and CTL Fashion were switched to enterprise-addons and vendor-addons respectively, recreated, and passed registry health and HTTP checks with no active mounts to the former top-level source paths.",
  "source_type": "local_test",
  "source": "/Volumes/OdooData/ODOO-ERP/.gitignore, .env, compose.yaml and live Docker mount/health validation",
  "odoo_version": "17.0",
  "observed_at": "2026-08-14T03:45:00Z",
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
      "id": "licensing-commercial-boundaries",
      "impact": "direct"
    }
  ],
  "related_modules": [
    "base"
  ],
  "related_agents": [
    "module.base",
    "platform.runtime-registry",
    "platform.licensing-commercial-boundaries"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/licensing-commercial-boundaries.md"
  ],
  "related_learnings": [
    {
      "id": "licensing-commercial-boundaries:odoo-licensing-product-architecture",
      "relation": "depends_on"
    },
    {
      "id": "runtime-registry:portable-odoodata-layout",
      "relation": "impacts"
    },
    {
      "id": "runtime-registry:ho-enterprise-source-restored",
      "relation": "impacts"
    }
  ]
}
```