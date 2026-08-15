---
layout: page
title: "orm-transactions:read-only-postgres-mcp-context"
subtitle: "Learning — base"
permalink: /decisions/2026-08-10-odoo-postgres-mcp/
nav_order: 0
---
# orm-transactions:read-only-postgres-mcp-context

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-10T16:45:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">18.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">db-workbench/mcp_server.py; .codex/config.toml; live MCP protocol checks against the local cmr Odoo database</div></div>
</div>

## Claim

Database-aware agents should discover Odoo models, physical tables, columns, indexes, foreign keys, and bounded row samples through a read-only MCP service, while treating the results as storage-level evidence that does not apply ORM access controls, record rules, company context, computed behavior, or cache semantics.

## Verification

verified_by_test

## Implementation

db-workbench/mcp_server.py

## Related agents

- `module.base`
- `platform.orm-transactions`
- `platform.security-identity`
- `platform.configuration-settings`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/base-platform/orm-transactions.md`
- `knowledge/base-platform/security-identity.md`
- `knowledge/base-platform/configuration-settings.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `orm-transactions`
- `security-identity`
- `configuration-settings`
- `testing-performance`

## Raw record

```json
{
  "id": "orm-transactions:read-only-postgres-mcp-context",
  "module": "base",
  "claim": "Database-aware agents should discover Odoo models, physical tables, columns, indexes, foreign keys, and bounded row samples through a read-only MCP service, while treating the results as storage-level evidence that does not apply ORM access controls, record rules, company context, computed behavior, or cache semantics.",
  "source_type": "local_test",
  "source": "db-workbench/mcp_server.py; .codex/config.toml; live MCP protocol checks against the local cmr Odoo database",
  "odoo_version": "18.0",
  "observed_at": "2026-08-10T16:45:00Z",
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
      "id": "security-identity",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "configuration-settings",
      "impact": "related"
    },
    {
      "kind": "platform",
      "id": "testing-performance",
      "impact": "related"
    }
  ],
  "related_modules": [
    "base"
  ],
  "related_agents": [
    "module.base",
    "platform.orm-transactions",
    "platform.security-identity",
    "platform.configuration-settings",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/base-platform/orm-transactions.md",
    "knowledge/base-platform/security-identity.md",
    "knowledge/base-platform/configuration-settings.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "orm-transactions:direct-database-workbench-guardrails",
      "relation": "extends"
    },
    {
      "id": "runtime-registry:troubleshoot-by-lifecycle-layer",
      "relation": "supports"
    }
  ],
  "implementation": "db-workbench/mcp_server.py"
}
```