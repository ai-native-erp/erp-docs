---
layout: page
title: "runtime-registry:odoo-17-customer-baseline"
subtitle: "Learning — sale_order_extension"
permalink: /decisions/2026-08-12-odoo-17-customer-baseline/
nav_order: 0
---
# runtime-registry:odoo-17-customer-baseline

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_order_extension</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-12T09:45:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">Docker Odoo 17.0-20260810; upstream Odoo 17 revision 126b5bdd1e85771549198976f8570cd2ff167608; sale_order_extension clean install and test run on cmr17</div></div>
</div>

## Claim

For an Odoo 17 customer baseline, pin both the runtime image and scanned source to 17.0, isolate PostgreSQL and filestore volumes from later major versions, use 17.0 addon manifests and tree XML roots, include fields referenced by relational domains in standalone views, and publish realtime events with bus.bus._sendone(target, notification_type, payload). The OWL View API still identifies list views with type list even though their XML root is tree.

## Verification

verified_by_test

## Implementation

Dockerfile; compose.yaml; addons/sale_order_extension

## Related agents

- `module.sale_order_extension`
- `module.sale`
- `module.web`
- `module.bus`
- `platform.runtime-registry`
- `platform.views-actions-qweb`
- `platform.upgrade-migration`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/sale_order_extension/overview.md`
- `knowledge/modules/sale/overview.md`
- `knowledge/modules/web/overview.md`
- `knowledge/modules/bus/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/views-actions-qweb.md`
- `knowledge/base-platform/upgrade-migration.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `sale_order_extension`
- `sale`
- `web`
- `bus`
- `runtime-registry`
- `views-actions-qweb`
- `upgrade-migration`
- `testing-performance`

## Raw record

```json
{
  "id": "runtime-registry:odoo-17-customer-baseline",
  "module": "sale_order_extension",
  "claim": "For an Odoo 17 customer baseline, pin both the runtime image and scanned source to 17.0, isolate PostgreSQL and filestore volumes from later major versions, use 17.0 addon manifests and tree XML roots, include fields referenced by relational domains in standalone views, and publish realtime events with bus.bus._sendone(target, notification_type, payload). The OWL View API still identifies list views with type list even though their XML root is tree.",
  "source_type": "local_test",
  "source": "Docker Odoo 17.0-20260810; upstream Odoo 17 revision 126b5bdd1e85771549198976f8570cd2ff167608; sale_order_extension clean install and test run on cmr17",
  "odoo_version": "17.0",
  "observed_at": "2026-08-12T09:45:00Z",
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
      "kind": "module",
      "id": "bus",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "runtime-registry",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "views-actions-qweb",
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
    "sale_order_extension",
    "sale",
    "web",
    "bus"
  ],
  "related_agents": [
    "module.sale_order_extension",
    "module.sale",
    "module.web",
    "module.bus",
    "platform.runtime-registry",
    "platform.views-actions-qweb",
    "platform.upgrade-migration",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/sale_order_extension/overview.md",
    "knowledge/modules/sale/overview.md",
    "knowledge/modules/web/overview.md",
    "knowledge/modules/bus/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/views-actions-qweb.md",
    "knowledge/base-platform/upgrade-migration.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "sale_order_extension:native-view-workspace-composition",
      "relation": "version_adapts"
    },
    {
      "id": "testing-performance:customization-regression-rings",
      "relation": "verified_by"
    },
    {
      "id": "web:owl-server-mediated-data-access",
      "relation": "implements"
    }
  ],
  "implementation": "Dockerfile; compose.yaml; addons/sale_order_extension"
}
```