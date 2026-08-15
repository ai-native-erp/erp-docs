---
layout: page
title: "runtime-registry:cmr-endpoint-bootstrap-enterprise-gate"
subtitle: "Learning — base"
permalink: /decisions/2026-08-12-cmr-endpoint-bootstrap-enterprise-gate/
nav_order: 0
---
# runtime-registry:cmr-endpoint-bootstrap-enterprise-gate

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-12T13:40:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_scan</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">Docker customer-profile endpoint and Store module-install smoke tests; CMR module manifests/imports; supplied CMR/LICENSE</div></div>
</div>

## Claim

Fixed-database CMR services must initialize a missing database before normal Odoo startup, without replacing an existing database. The Store Odoo 17 application also requires its declared and imported spreadsheet Python dependencies before its principal custom modules can install. Enterprise source remains a separate entitlement boundary: an LGPL/Community license text does not authorize or provide Odoo Enterprise addons.

## Verification

verified_by_test

## Implementation

tools/cmr_start.sh; Dockerfile.customer; requirements-cmr.txt; compose.yaml; docs/cmr-docker-deployment.md

## Related agents

- `module.base`
- `module.web`
- `module.point_of_sale`
- `module.stock`
- `module.account`
- `platform.runtime-registry`
- `platform.upgrade-migration`
- `platform.security-access`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/modules/web/overview.md`
- `knowledge/modules/point_of_sale/overview.md`
- `knowledge/modules/stock/overview.md`
- `knowledge/modules/account/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/upgrade-migration.md`
- `knowledge/base-platform/security-access.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `runtime-registry`
- `upgrade-migration`
- `security-access`
- `testing-performance`

## Raw record

```json
{
  "id": "runtime-registry:cmr-endpoint-bootstrap-enterprise-gate",
  "module": "base",
  "claim": "Fixed-database CMR services must initialize a missing database before normal Odoo startup, without replacing an existing database. The Store Odoo 17 application also requires its declared and imported spreadsheet Python dependencies before its principal custom modules can install. Enterprise source remains a separate entitlement boundary: an LGPL/Community license text does not authorize or provide Odoo Enterprise addons.",
  "source_type": "local_scan",
  "source": "Docker customer-profile endpoint and Store module-install smoke tests; CMR module manifests/imports; supplied CMR/LICENSE",
  "odoo_version": "17.0",
  "observed_at": "2026-08-12T13:40:00Z",
  "confidence": "high",
  "verification": "verified_by_test",
  "affected_entities": [
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
      "id": "security-access",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "testing-performance",
      "impact": "direct"
    }
  ],
  "related_modules": [
    "base",
    "web",
    "point_of_sale",
    "stock",
    "account"
  ],
  "related_agents": [
    "module.base",
    "module.web",
    "module.point_of_sale",
    "module.stock",
    "module.account",
    "platform.runtime-registry",
    "platform.upgrade-migration",
    "platform.security-access",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/modules/web/overview.md",
    "knowledge/modules/point_of_sale/overview.md",
    "knowledge/modules/stock/overview.md",
    "knowledge/modules/account/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/upgrade-migration.md",
    "knowledge/base-platform/security-access.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:cmr-ho-store-isolation",
      "relation": "extends"
    },
    {
      "id": "security-access:licensing-aware-product-architecture",
      "relation": "constrained_by"
    },
    {
      "id": "runtime-registry:odoo-17-customer-baseline",
      "relation": "implements"
    }
  ],
  "implementation": "tools/cmr_start.sh; Dockerfile.customer; requirements-cmr.txt; compose.yaml; docs/cmr-docker-deployment.md"
}
```