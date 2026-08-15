---
layout: page
title: "web:owl-server-mediated-data-access"
subtitle: "Learning — web"
permalink: /decisions/2026-08-11-owl-orm-rpc-data-access/
nav_order: 0
---
# web:owl-server-mediated-data-access

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>web</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-11T06:45:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">18.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">conversation</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">/Users/srste/.codex/attachments/f55b2a1c-958b-4fcf-8d3c-fdbd970192c6/pasted-text.txt; addons/sale_order_extension/static/src/workspace/sale_order_workspace.js</div></div>
</div>

## Claim

An OWL component must not connect directly to PostgreSQL. For model CRUD and model methods it uses the web client ORM service; for purpose-built API operations it uses the RPC service with an authenticated Python controller. Both paths terminate in the server-side Odoo ORM, preserving ACLs, record rules, create/write/unlink overrides, constraints, computed fields, audit logic, and transaction semantics. Embedded native View components already use this controller/model/ORM stack internally.

## Verification

verified_by_code_scan

## Implementation

addons/sale_order_extension/static/src/workspace/sale_order_workspace.js

## Related agents

- `module.web`
- `module.sale_order_extension`
- `platform.assets-frontend`
- `platform.http-rpc`
- `platform.orm-transactions`
- `platform.security-identity`
- `platform.views-actions-qweb`

## Related wikis

- `knowledge/modules/web/overview.md`
- `knowledge/modules/sale_order_extension/overview.md`
- `knowledge/base-platform/assets-frontend.md`
- `knowledge/base-platform/http-rpc.md`
- `knowledge/base-platform/orm-transactions.md`
- `knowledge/base-platform/security-identity.md`
- `knowledge/base-platform/views-actions-qweb.md`

## Affected entities

- `web`
- `sale_order_extension`
- `assets-frontend`
- `http-rpc`
- `orm-transactions`
- `security-identity`
- `views-actions-qweb`

## Raw record

```json
{
  "id": "web:owl-server-mediated-data-access",
  "module": "web",
  "claim": "An OWL component must not connect directly to PostgreSQL. For model CRUD and model methods it uses the web client ORM service; for purpose-built API operations it uses the RPC service with an authenticated Python controller. Both paths terminate in the server-side Odoo ORM, preserving ACLs, record rules, create/write/unlink overrides, constraints, computed fields, audit logic, and transaction semantics. Embedded native View components already use this controller/model/ORM stack internally.",
  "source_type": "conversation",
  "source": "/Users/srste/.codex/attachments/f55b2a1c-958b-4fcf-8d3c-fdbd970192c6/pasted-text.txt; addons/sale_order_extension/static/src/workspace/sale_order_workspace.js",
  "odoo_version": "18.0",
  "observed_at": "2026-08-11T06:45:00Z",
  "confidence": "high",
  "verification": "verified_by_code_scan",
  "affected_entities": [
    {
      "kind": "module",
      "id": "web",
      "impact": "direct"
    },
    {
      "kind": "module",
      "id": "sale_order_extension",
      "impact": "example"
    },
    {
      "kind": "platform",
      "id": "assets-frontend",
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
      "id": "security-identity",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "views-actions-qweb",
      "impact": "related"
    }
  ],
  "related_modules": [
    "web",
    "sale_order_extension"
  ],
  "related_agents": [
    "module.web",
    "module.sale_order_extension",
    "platform.assets-frontend",
    "platform.http-rpc",
    "platform.orm-transactions",
    "platform.security-identity",
    "platform.views-actions-qweb"
  ],
  "related_wikis": [
    "knowledge/modules/web/overview.md",
    "knowledge/modules/sale_order_extension/overview.md",
    "knowledge/base-platform/assets-frontend.md",
    "knowledge/base-platform/http-rpc.md",
    "knowledge/base-platform/orm-transactions.md",
    "knowledge/base-platform/security-identity.md",
    "knowledge/base-platform/views-actions-qweb.md"
  ],
  "related_learnings": [
    {
      "id": "web:owl-component-and-service-fundamentals",
      "relation": "extended_by"
    },
    {
      "id": "sale_order_extension:native-view-workspace-composition",
      "relation": "explains"
    },
    {
      "id": "sale:servicenow-patterns-through-native-odoo",
      "relation": "extends"
    },
    {
      "id": "orm-transactions:direct-database-workbench-guardrails",
      "relation": "contrasts"
    }
  ],
  "implementation": "addons/sale_order_extension/static/src/workspace/sale_order_workspace.js"
}
```