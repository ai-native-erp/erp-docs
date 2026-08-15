---
layout: page
title: "runtime-registry:ctl-fashion-isolated-restore"
subtitle: "Learning — base"
permalink: /decisions/2026-08-14-ctl-fashion-isolated-restore/
nav_order: 0
---
# runtime-registry:ctl-fashion-isolated-restore

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-14T03:20:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">/Volumes/OdooData/odoo-backups/CMR_CTL_FASHION/manifest.json plus Compose registry and HTTP validation</div></div>
</div>

## Claim

The supplied CMR_CTL_FASHION package is an Odoo 17 Store-family backup: its 165 installed modules align with the CMR-STORE addon source. It was restored without overwriting HO or Store into database cmr_ctl_fashion with an isolated filestore volume, Store customer addons, licensed Enterprise addons, cron disabled, and dedicated Odoo, viewer, and read-only MCP endpoints. Registry loading and HTTP health succeeded, and 17,188 filestore objects were present after restoration.

## Verification

verified_by_test

## Related agents

- `module.base`
- `platform.runtime-registry`
- `platform.attachments-filestore`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/attachments-filestore.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `base`
- `runtime-registry`
- `attachments-filestore`
- `testing-performance`

## Raw record

```json
{
  "id": "runtime-registry:ctl-fashion-isolated-restore",
  "module": "base",
  "claim": "The supplied CMR_CTL_FASHION package is an Odoo 17 Store-family backup: its 165 installed modules align with the CMR-STORE addon source. It was restored without overwriting HO or Store into database cmr_ctl_fashion with an isolated filestore volume, Store customer addons, licensed Enterprise addons, cron disabled, and dedicated Odoo, viewer, and read-only MCP endpoints. Registry loading and HTTP health succeeded, and 17,188 filestore objects were present after restoration.",
  "source_type": "local_test",
  "source": "/Volumes/OdooData/odoo-backups/CMR_CTL_FASHION/manifest.json plus Compose registry and HTTP validation",
  "odoo_version": "17.0",
  "observed_at": "2026-08-14T03:20:00Z",
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
      "id": "attachments-filestore",
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
    "platform.attachments-filestore",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/attachments-filestore.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:portable-odoodata-layout",
      "relation": "depends_on"
    },
    {
      "id": "runtime-registry:customer-addon-mount-preflight",
      "relation": "depends_on"
    }
  ]
}
```