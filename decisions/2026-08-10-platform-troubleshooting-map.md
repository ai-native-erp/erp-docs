---
layout: page
title: "runtime-registry:troubleshoot-by-lifecycle-layer"
subtitle: "Learning — base"
permalink: /decisions/2026-08-10-platform-troubleshooting-map/
nav_order: 0
---
# runtime-registry:troubleshoot-by-lifecycle-layer

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-10T15:30:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">18.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_code</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">work-dir/odoo/odoo/service/server.py; work-dir/odoo/odoo/modules/loading.py; work-dir/odoo/odoo/http.py; work-dir/odoo/odoo/api.py; work-dir/odoo/odoo/models.py; work-dir/odoo/odoo/sql_db.py</div></div>
</div>

## Claim

Platform defects are diagnosed most reliably by locating the first failing lifecycle layer—startup/module loading, request dispatch, ORM/security execution, rendering/storage, background work, or transaction completion—then tracing the owning model and downstream impact graph before changing code.

## Verification

verified_in_code

## Related agents

- `platform.http-rpc`
- `platform.orm-transactions`
- `platform.runtime-registry`
- `platform.testing-performance`

## Related wikis

- `knowledge/base-platform/http-rpc.md`
- `knowledge/base-platform/orm-transactions.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `runtime-registry`
- `http-rpc`
- `orm-transactions`
- `testing-performance`

## Raw record

```json
{
  "id": "runtime-registry:troubleshoot-by-lifecycle-layer",
  "module": "base",
  "claim": "Platform defects are diagnosed most reliably by locating the first failing lifecycle layer\u2014startup/module loading, request dispatch, ORM/security execution, rendering/storage, background work, or transaction completion\u2014then tracing the owning model and downstream impact graph before changing code.",
  "source_type": "local_code",
  "source": "work-dir/odoo/odoo/service/server.py; work-dir/odoo/odoo/modules/loading.py; work-dir/odoo/odoo/http.py; work-dir/odoo/odoo/api.py; work-dir/odoo/odoo/models.py; work-dir/odoo/odoo/sql_db.py",
  "odoo_version": "18.0",
  "observed_at": "2026-08-10T15:30:00Z",
  "confidence": "high",
  "verification": "verified_in_code",
  "affected_entities": [
    {
      "kind": "platform",
      "id": "runtime-registry",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "http-rpc",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "orm-transactions",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "testing-performance",
      "impact": "related"
    }
  ],
  "related_modules": [],
  "related_agents": [
    "platform.http-rpc",
    "platform.orm-transactions",
    "platform.runtime-registry",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/base-platform/http-rpc.md",
    "knowledge/base-platform/orm-transactions.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "testing-performance:customization-regression-rings",
      "relation": "depends_on"
    },
    {
      "id": "orm-transactions:direct-database-workbench-guardrails",
      "relation": "supported_by"
    }
  ],
  "handbook": "knowledge/platform-handbook/README.md"
}
```