---
layout: page
title: "runtime-registry:cmr-ho-store-isolation"
subtitle: "Learning — base"
permalink: /decisions/2026-08-12-cmr-ho-store-isolation/
nav_order: 0
---
# runtime-registry:cmr-ho-store-isolation

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-12T13:20:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_scan</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">CMR/CMR-HO and CMR/CMR-STORE manifests and source; compose customer profile smoke-tested with Odoo 17.0-20260810</div></div>
</div>

## Claim

The CMR Odoo 17 application must run Head Office and Store as separate Odoo services, fixed-name databases, filestores, and addon paths because nine same-named modules have profile-specific code. Head Office additionally requires licensed Enterprise modules. Restores must keep each PostgreSQL dump paired with its matching filestore, start with cron and external integrations disabled, and use Docker service DNS for Store-to-HO calls.

## Verification

verified_by_test

## Implementation

compose.yaml; Dockerfile.customer; tools/cmr_restore.sh; docs/cmr-docker-deployment.md

## Related agents

- `module.base`
- `module.web`
- `module.account`
- `module.stock`
- `module.point_of_sale`
- `platform.runtime-registry`
- `platform.upgrade-migration`
- `platform.security-access`
- `platform.http-controllers`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/modules/web/overview.md`
- `knowledge/modules/account/overview.md`
- `knowledge/modules/stock/overview.md`
- `knowledge/modules/point_of_sale/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/upgrade-migration.md`
- `knowledge/base-platform/security-access.md`
- `knowledge/base-platform/http-controllers.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `runtime-registry`
- `upgrade-migration`
- `security-access`
- `http-controllers`
- `testing-performance`

## Raw record

```json
{
  "id": "runtime-registry:cmr-ho-store-isolation",
  "module": "base",
  "claim": "The CMR Odoo 17 application must run Head Office and Store as separate Odoo services, fixed-name databases, filestores, and addon paths because nine same-named modules have profile-specific code. Head Office additionally requires licensed Enterprise modules. Restores must keep each PostgreSQL dump paired with its matching filestore, start with cron and external integrations disabled, and use Docker service DNS for Store-to-HO calls.",
  "source_type": "local_scan",
  "source": "CMR/CMR-HO and CMR/CMR-STORE manifests and source; compose customer profile smoke-tested with Odoo 17.0-20260810",
  "odoo_version": "17.0",
  "observed_at": "2026-08-12T13:20:00Z",
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
      "id": "http-controllers",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "testing-performance",
      "impact": "related"
    }
  ],
  "related_modules": [
    "base",
    "web",
    "account",
    "stock",
    "point_of_sale"
  ],
  "related_agents": [
    "module.base",
    "module.web",
    "module.account",
    "module.stock",
    "module.point_of_sale",
    "platform.runtime-registry",
    "platform.upgrade-migration",
    "platform.security-access",
    "platform.http-controllers",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/modules/web/overview.md",
    "knowledge/modules/account/overview.md",
    "knowledge/modules/stock/overview.md",
    "knowledge/modules/point_of_sale/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/upgrade-migration.md",
    "knowledge/base-platform/security-access.md",
    "knowledge/base-platform/http-controllers.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:odoo-17-customer-baseline",
      "relation": "extends"
    },
    {
      "id": "security-access:licensing-aware-product-architecture",
      "relation": "constrained_by"
    },
    {
      "id": "testing-performance:customization-regression-rings",
      "relation": "verified_by"
    }
  ],
  "implementation": "compose.yaml; Dockerfile.customer; tools/cmr_restore.sh; docs/cmr-docker-deployment.md"
}
```