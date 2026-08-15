---
layout: page
title: "web:owl-component-and-service-fundamentals"
subtitle: "Learning — web"
permalink: /decisions/2026-08-11-owl-component-fundamentals/
nav_order: 0
---
# web:owl-component-and-service-fundamentals

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>web</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-11T07:05:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">18.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">conversation</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">/Users/srste/.codex/attachments/22b0b510-51d5-497d-a7c4-0682bc807881/pasted-text.txt; addons/sale_order_extension/static/src/workspace</div></div>
</div>

## Claim

OWL (Odoo Web Library) is Odoo's browser-side component framework: Component classes bind to QWeb/OWL templates, useState provides reactive state and automatic DOM updates, event handlers implement client behavior, and Odoo services connect UI components to platform capabilities. Prefer the ORM service for model CRUD and model methods; use RPC for purpose-built controller contracts such as multi-model aggregation, files, webhooks, external-system orchestration, or specialized responses. Native View components already own their controller/model/ORM lifecycle.

## Verification

verified_by_code_scan

## Implementation

addons/sale_order_extension/static/src/workspace/sale_order_workspace.js

## Related agents

- `module.web`
- `module.sale_order_extension`
- `platform.assets-frontend`
- `platform.views-actions-qweb`
- `platform.http-rpc`
- `platform.orm-transactions`
- `platform.security-identity`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/web/overview.md`
- `knowledge/modules/sale_order_extension/overview.md`
- `knowledge/base-platform/assets-frontend.md`
- `knowledge/base-platform/views-actions-qweb.md`
- `knowledge/base-platform/http-rpc.md`
- `knowledge/base-platform/orm-transactions.md`
- `knowledge/base-platform/security-identity.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `web`
- `sale_order_extension`
- `assets-frontend`
- `views-actions-qweb`
- `http-rpc`
- `orm-transactions`
- `security-identity`
- `testing-performance`

## Raw record

```json
{
  "id": "web:owl-component-and-service-fundamentals",
  "module": "web",
  "claim": "OWL (Odoo Web Library) is Odoo's browser-side component framework: Component classes bind to QWeb/OWL templates, useState provides reactive state and automatic DOM updates, event handlers implement client behavior, and Odoo services connect UI components to platform capabilities. Prefer the ORM service for model CRUD and model methods; use RPC for purpose-built controller contracts such as multi-model aggregation, files, webhooks, external-system orchestration, or specialized responses. Native View components already own their controller/model/ORM lifecycle.",
  "source_type": "conversation",
  "source": "/Users/srste/.codex/attachments/22b0b510-51d5-497d-a7c4-0682bc807881/pasted-text.txt; addons/sale_order_extension/static/src/workspace",
  "odoo_version": "18.0",
  "observed_at": "2026-08-11T07:05:00Z",
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
      "id": "views-actions-qweb",
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
      "impact": "related"
    },
    {
      "kind": "platform",
      "id": "testing-performance",
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
    "platform.views-actions-qweb",
    "platform.http-rpc",
    "platform.orm-transactions",
    "platform.security-identity",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/web/overview.md",
    "knowledge/modules/sale_order_extension/overview.md",
    "knowledge/base-platform/assets-frontend.md",
    "knowledge/base-platform/views-actions-qweb.md",
    "knowledge/base-platform/http-rpc.md",
    "knowledge/base-platform/orm-transactions.md",
    "knowledge/base-platform/security-identity.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "web:owl-server-mediated-data-access",
      "relation": "extends"
    },
    {
      "id": "sale_order_extension:native-view-workspace-composition",
      "relation": "explains"
    },
    {
      "id": "sale:servicenow-patterns-through-native-odoo",
      "relation": "maps_to"
    }
  ],
  "implementation": "addons/sale_order_extension/static/src/workspace/sale_order_workspace.js"
}
```