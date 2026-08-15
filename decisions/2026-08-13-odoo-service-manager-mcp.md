---
layout: page
title: "runtime-registry:guarded-service-manager-mcp"
subtitle: "Learning — base"
permalink: /decisions/2026-08-13-odoo-service-manager-mcp/
nav_order: 0
---
# runtime-registry:guarded-service-manager-mcp

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-13T06:48:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">odoo-service-mcp/server.py; compose.yaml; odoo-service-mcp/README.md</div></div>
</div>

## Claim

Local Odoo lifecycle automation is exposed through a localhost-only MCP that allowlists Base, HO, and Store; provides bounded status and logs, restart, selected-module upgrade, registry view compilation, and post-change checks; refuses arbitrary shell, SQL, destructive Docker operations, and addon upgrades without explicit matching database/filestore backup confirmation.

## Verification

verified_by_test

## Implementation

odoo-service-mcp/server.py

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
  "id": "runtime-registry:guarded-service-manager-mcp",
  "module": "base",
  "claim": "Local Odoo lifecycle automation is exposed through a localhost-only MCP that allowlists Base, HO, and Store; provides bounded status and logs, restart, selected-module upgrade, registry view compilation, and post-change checks; refuses arbitrary shell, SQL, destructive Docker operations, and addon upgrades without explicit matching database/filestore backup confirmation.",
  "source_type": "local_test",
  "source": "odoo-service-mcp/server.py; compose.yaml; odoo-service-mcp/README.md",
  "odoo_version": "17.0",
  "observed_at": "2026-08-13T06:48:00Z",
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
      "id": "runtime-registry:troubleshoot-by-lifecycle-layer",
      "relation": "related_to"
    },
    {
      "id": "testing-performance:customization-regression-rings",
      "relation": "related_to"
    }
  ],
  "implementation": "odoo-service-mcp/server.py"
}
```