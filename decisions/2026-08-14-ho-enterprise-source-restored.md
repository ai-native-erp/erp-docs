---
layout: page
title: "runtime-registry:ho-enterprise-source-restored"
subtitle: "Learning — base"
permalink: /decisions/2026-08-14-ho-enterprise-source-restored/
nav_order: 0
---
# runtime-registry:ho-enterprise-source-restored

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-14T01:56:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">/Volumes/OdooData/enterprise_addons_17; /Volumes/OdooData/Odoo 17/auto_database_backup; odoo-cmr-ho registry and validate_views</div></div>
</div>

## Claim

The entitled SSD addon tree at /Volumes/OdooData/enterprise_addons_17 supplies 154 of the 156 previously absent HO module sources; auto_database_backup is supplied separately and studio_customization is database-generated. After mounting the SSD read-only into Colima, adding declared Python dependencies, and restoring compatible quarantined metadata, Odoo loaded all 359 non-base installed modules and validated 652 action/view combinations with zero failures.

## Verification

verified_by_test

## Related agents

- `module.base`
- `module.web`
- `module.sale`
- `platform.runtime-registry`
- `platform.upgrade-migration`
- `platform.testing-performance`
- `licensing_architecture`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/modules/web/overview.md`
- `knowledge/modules/sale/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/upgrade-migration.md`
- `knowledge/base-platform/testing-performance.md`
- `knowledge/product-architecture/licensing-playbook.md`

## Affected entities

- `base`
- `runtime-registry`
- `upgrade-migration`
- `testing-performance`

## Raw record

```json
{
  "id": "runtime-registry:ho-enterprise-source-restored",
  "module": "base",
  "claim": "The entitled SSD addon tree at /Volumes/OdooData/enterprise_addons_17 supplies 154 of the 156 previously absent HO module sources; auto_database_backup is supplied separately and studio_customization is database-generated. After mounting the SSD read-only into Colima, adding declared Python dependencies, and restoring compatible quarantined metadata, Odoo loaded all 359 non-base installed modules and validated 652 action/view combinations with zero failures.",
  "source_type": "local_test",
  "source": "/Volumes/OdooData/enterprise_addons_17; /Volumes/OdooData/Odoo 17/auto_database_backup; odoo-cmr-ho registry and validate_views",
  "odoo_version": "17.0",
  "observed_at": "2026-08-14T01:56:00Z",
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
    "base",
    "web",
    "sale"
  ],
  "related_agents": [
    "module.base",
    "module.web",
    "module.sale",
    "platform.runtime-registry",
    "platform.upgrade-migration",
    "platform.testing-performance",
    "licensing_architecture"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/modules/web/overview.md",
    "knowledge/modules/sale/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/upgrade-migration.md",
    "knowledge/base-platform/testing-performance.md",
    "knowledge/product-architecture/licensing-playbook.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:ho-enterprise-source-gap",
      "relation": "supersedes"
    },
    {
      "id": "runtime-registry:ho-missing-enterprise-metadata-quarantine",
      "relation": "related_to"
    },
    {
      "id": "runtime-registry:external-colima-capacity",
      "relation": "related_to"
    }
  ],
  "licensing_constraint": "The mounted tree contains OEEL-1 modules and may only be used under the customer's valid Enterprise entitlement; keep it outside Git and do not redistribute it. The local bundle has no Git metadata, so its exact upstream commit remains unverified."
}
```