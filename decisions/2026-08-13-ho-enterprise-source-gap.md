---
layout: page
title: "runtime-registry:ho-enterprise-source-gap"
subtitle: "Learning — base"
permalink: /decisions/2026-08-13-ho-enterprise-source-gap/
nav_order: 0
---
# runtime-registry:ho-enterprise-source-gap

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-13T11:35:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">cmr_ho_test ir_module_module; RetailEnterprise/addons scan; odoo-cmr-ho startup log</div></div>
</div>

## Claim

The restored HO database has 360 modules marked installed and depends on Odoo 17 Enterprise modules, but RetailEnterprise/addons contains the Community tree and the local enterprise-addons directory has no matching Enterprise source. Odoo therefore loads only a partial 196-module registry; HTTP health and login return 200, while Enterprise-dependent HO custom modules are skipped.

## Verification

verified_by_test

## Related agents

- `module.base`
- `platform.runtime-registry`
- `platform.upgrade-migration`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/upgrade-migration.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `base`
- `runtime-registry`
- `upgrade-migration`
- `testing-performance`

## Raw record

```json
{
  "id": "runtime-registry:ho-enterprise-source-gap",
  "module": "base",
  "claim": "The restored HO database has 360 modules marked installed and depends on Odoo 17 Enterprise modules, but RetailEnterprise/addons contains the Community tree and the local enterprise-addons directory has no matching Enterprise source. Odoo therefore loads only a partial 196-module registry; HTTP health and login return 200, while Enterprise-dependent HO custom modules are skipped.",
  "source_type": "local_test",
  "source": "cmr_ho_test ir_module_module; RetailEnterprise/addons scan; odoo-cmr-ho startup log",
  "odoo_version": "17.0",
  "observed_at": "2026-08-13T11:35:00Z",
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
    "base"
  ],
  "related_agents": [
    "module.base",
    "platform.runtime-registry",
    "platform.upgrade-migration",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/upgrade-migration.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:customer-addon-mount-preflight",
      "relation": "supports"
    },
    {
      "id": "runtime-registry:external-colima-capacity",
      "relation": "related_to"
    }
  ]
}
```