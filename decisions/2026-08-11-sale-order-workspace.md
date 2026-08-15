---
layout: page
title: "sale_order_extension:native-view-workspace-composition"
subtitle: "Learning — sale_order_extension"
permalink: /decisions/2026-08-11-sale-order-workspace/
nav_order: 0
---
# sale_order_extension:native-view-workspace-composition

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_order_extension</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-11T06:10:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">18.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">addons/sale_order_extension/static/src/workspace; addons/sale_order_extension/views/sale_order_workspace_views.xml; live browser verification against cmr</div></div>
</div>

## Claim

A ServiceNow-style workspace can be implemented as an Odoo OWL client action that composes native list and form View components: selectRecord drives the master-detail selection, a dedicated form view exposes related x2many lists, declarative client actions update reactive UI state, and declarative server actions call ORM methods that retain access rules, validation, transactions, and audit behavior.

## Verification

verified_by_test

## Implementation

addons/sale_order_extension/README.md

## Related agents

- `module.sale_order_extension`
- `module.sale`
- `module.web`
- `platform.views-actions-qweb`
- `platform.assets-frontend`
- `platform.orm-transactions`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/sale_order_extension/overview.md`
- `knowledge/modules/sale/overview.md`
- `knowledge/modules/web/overview.md`
- `knowledge/base-platform/views-actions-qweb.md`
- `knowledge/base-platform/assets-frontend.md`
- `knowledge/base-platform/orm-transactions.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `sale_order_extension`
- `sale`
- `web`
- `views-actions-qweb`
- `assets-frontend`
- `orm-transactions`
- `testing-performance`

## Raw record

```json
{
  "id": "sale_order_extension:native-view-workspace-composition",
  "module": "sale_order_extension",
  "claim": "A ServiceNow-style workspace can be implemented as an Odoo OWL client action that composes native list and form View components: selectRecord drives the master-detail selection, a dedicated form view exposes related x2many lists, declarative client actions update reactive UI state, and declarative server actions call ORM methods that retain access rules, validation, transactions, and audit behavior.",
  "source_type": "local_test",
  "source": "addons/sale_order_extension/static/src/workspace; addons/sale_order_extension/views/sale_order_workspace_views.xml; live browser verification against cmr",
  "odoo_version": "18.0",
  "observed_at": "2026-08-11T06:10:00Z",
  "confidence": "high",
  "verification": "verified_by_test",
  "affected_entities": [
    {
      "kind": "module",
      "id": "sale_order_extension",
      "impact": "direct"
    },
    {
      "kind": "module",
      "id": "sale",
      "impact": "direct"
    },
    {
      "kind": "module",
      "id": "web",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "views-actions-qweb",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "assets-frontend",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "orm-transactions",
      "impact": "related"
    },
    {
      "kind": "platform",
      "id": "testing-performance",
      "impact": "related"
    }
  ],
  "related_modules": [
    "sale_order_extension",
    "sale",
    "web"
  ],
  "related_agents": [
    "module.sale_order_extension",
    "module.sale",
    "module.web",
    "platform.views-actions-qweb",
    "platform.assets-frontend",
    "platform.orm-transactions",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/sale_order_extension/overview.md",
    "knowledge/modules/sale/overview.md",
    "knowledge/modules/web/overview.md",
    "knowledge/base-platform/views-actions-qweb.md",
    "knowledge/base-platform/assets-frontend.md",
    "knowledge/base-platform/orm-transactions.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "web:owl-component-and-service-fundamentals",
      "relation": "explained_by"
    },
    {
      "id": "sale:servicenow-patterns-through-native-odoo",
      "relation": "extends"
    },
    {
      "id": "testing-performance:customization-regression-rings",
      "relation": "applies"
    },
    {
      "id": "web:owl-server-mediated-data-access",
      "relation": "explained_by"
    }
  ],
  "implementation": "addons/sale_order_extension/README.md"
}
```