---
layout: page
title: "orm-transactions:direct-database-workbench-guardrails"
subtitle: "Learning — base"
permalink: /decisions/2026-08-10-postgres-workbench-safety/
nav_order: 0
---
# orm-transactions:direct-database-workbench-guardrails

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-10T16:05:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">18.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">db-workbench/app.py; compose.yaml; integration checks against the local cmr Odoo database</div></div>
</div>

## Claim

A local PostgreSQL workbench is useful for Odoo diagnosis, but direct writes bypass ORM access rules, constraints, recomputation, tracking, and cache invalidation; therefore it must be loopback-only, parameterized, timeout-bounded, explicitly write-enabled, and require complete primary keys plus per-request confirmation for updates and deletes.

## Verification

verified_by_test

## Implementation

db-workbench/README.md

## Related agents

- `platform.configuration-settings`
- `platform.orm-transactions`
- `platform.testing-performance`

## Related wikis

- `knowledge/base-platform/configuration-settings.md`
- `knowledge/base-platform/orm-transactions.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `orm-transactions`
- `configuration-settings`
- `testing-performance`

## Raw record

```json
{
  "id": "orm-transactions:direct-database-workbench-guardrails",
  "module": "base",
  "claim": "A local PostgreSQL workbench is useful for Odoo diagnosis, but direct writes bypass ORM access rules, constraints, recomputation, tracking, and cache invalidation; therefore it must be loopback-only, parameterized, timeout-bounded, explicitly write-enabled, and require complete primary keys plus per-request confirmation for updates and deletes.",
  "source_type": "local_test",
  "source": "db-workbench/app.py; compose.yaml; integration checks against the local cmr Odoo database",
  "odoo_version": "18.0",
  "observed_at": "2026-08-10T16:05:00Z",
  "confidence": "high",
  "verification": "verified_by_test",
  "affected_entities": [
    {
      "kind": "platform",
      "id": "orm-transactions",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "configuration-settings",
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
    "platform.configuration-settings",
    "platform.orm-transactions",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/base-platform/configuration-settings.md",
    "knowledge/base-platform/orm-transactions.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:troubleshoot-by-lifecycle-layer",
      "relation": "supports"
    },
    {
      "id": "orm-transactions:read-only-postgres-mcp-context",
      "relation": "extended_by"
    }
  ],
  "implementation": "db-workbench/README.md"
}
```