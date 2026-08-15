---
layout: page
title: "runtime-registry:ho-missing-enterprise-metadata-quarantine"
subtitle: "Learning — sale"
permalink: /decisions/2026-08-13-ho-missing-enterprise-metadata-quarantine/
nav_order: 0
---
# runtime-registry:ho-missing-enterprise-metadata-quarantine

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-13T14:10:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">cmr_ho_test installed module scan using get_module_path; sale.order actions 316 and 317 get_views</div></div>
</div>

## Claim

A restored Odoo database may retain active XML metadata for every installed Enterprise module even when those addon sources are absent. Quarantining only custom-module metadata is insufficient: sale_planning left planning_first_sale_line_id in sale.order views. The safe partial-registry workaround is to identify every installed module with no resolvable addon path, reversibly deactivate its views, menus, and asset directives, regenerate bundles, and validate all affected action view modes.

## Verification

verified_by_test

## Related agents

- `module.sale`
- `module.base`
- `module.web`
- `platform.runtime-registry`
- `platform.metadata-xmlids`
- `platform.frontend-owl-assets`
- `platform.upgrade-migration`

## Related wikis

- `knowledge/modules/sale/overview.md`
- `knowledge/modules/base/overview.md`
- `knowledge/modules/web/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/metadata-xmlids.md`
- `knowledge/base-platform/frontend-owl-assets.md`
- `knowledge/base-platform/upgrade-migration.md`

## Affected entities

- `sale`
- `base`
- `runtime-registry`
- `metadata-xmlids`
- `frontend-owl-assets`
- `upgrade-migration`

## Raw record

```json
{
  "id": "runtime-registry:ho-missing-enterprise-metadata-quarantine",
  "module": "sale",
  "claim": "A restored Odoo database may retain active XML metadata for every installed Enterprise module even when those addon sources are absent. Quarantining only custom-module metadata is insufficient: sale_planning left planning_first_sale_line_id in sale.order views. The safe partial-registry workaround is to identify every installed module with no resolvable addon path, reversibly deactivate its views, menus, and asset directives, regenerate bundles, and validate all affected action view modes.",
  "source_type": "local_test",
  "source": "cmr_ho_test installed module scan using get_module_path; sale.order actions 316 and 317 get_views",
  "odoo_version": "17.0",
  "observed_at": "2026-08-13T14:10:00Z",
  "confidence": "high",
  "verification": "verified_by_test",
  "affected_entities": [
    {
      "kind": "module",
      "id": "sale",
      "impact": "direct"
    },
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
      "id": "metadata-xmlids",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "frontend-owl-assets",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "upgrade-migration",
      "impact": "direct"
    }
  ],
  "related_modules": [
    "sale",
    "base",
    "web"
  ],
  "related_agents": [
    "module.sale",
    "module.base",
    "module.web",
    "platform.runtime-registry",
    "platform.metadata-xmlids",
    "platform.frontend-owl-assets",
    "platform.upgrade-migration"
  ],
  "related_wikis": [
    "knowledge/modules/sale/overview.md",
    "knowledge/modules/base/overview.md",
    "knowledge/modules/web/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/metadata-xmlids.md",
    "knowledge/base-platform/frontend-owl-assets.md",
    "knowledge/base-platform/upgrade-migration.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:ho-enterprise-source-gap",
      "relation": "depends_on"
    },
    {
      "id": "runtime-registry:ho-unloaded-custom-metadata-quarantine",
      "relation": "supports"
    },
    {
      "id": "frontend-owl-assets:stale-view-after-metadata-quarantine",
      "relation": "related_to"
    }
  ]
}
```