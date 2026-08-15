---
layout: page
title: "runtime-registry:customer-addon-mount-preflight"
subtitle: "Learning — base"
permalink: /decisions/2026-08-13-customer-addon-mount-preflight/
nav_order: 0
---
# runtime-registry:customer-addon-mount-preflight

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-13T06:48:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">compose.yaml; odoo-service-mcp/server.py; odoo-cmr-store runtime restart and post_change_check</div></div>
</div>

## Claim

A healthy Odoo HTTP endpoint is insufficient after a customer service restart: when a bind-source directory has moved, Docker may start with an empty addon mount and Odoo can load a reduced registry while still returning HTTP 200. Customer lifecycle operations must verify that the mounted addon path contains manifests and must fail post-change validation on unexpected missing-module messages.

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
  "id": "runtime-registry:customer-addon-mount-preflight",
  "module": "base",
  "claim": "A healthy Odoo HTTP endpoint is insufficient after a customer service restart: when a bind-source directory has moved, Docker may start with an empty addon mount and Odoo can load a reduced registry while still returning HTTP 200. Customer lifecycle operations must verify that the mounted addon path contains manifests and must fail post-change validation on unexpected missing-module messages.",
  "source_type": "local_test",
  "source": "compose.yaml; odoo-service-mcp/server.py; odoo-cmr-store runtime restart and post_change_check",
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
      "id": "runtime-registry:guarded-service-manager-mcp",
      "relation": "related_to"
    },
    {
      "id": "runtime-registry:troubleshoot-by-lifecycle-layer",
      "relation": "related_to"
    }
  ],
  "implementation": "odoo-service-mcp/server.py"
}
```