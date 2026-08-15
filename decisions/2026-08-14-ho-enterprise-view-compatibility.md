---
layout: page
title: "metadata-xmlids:ho-enterprise-view-compatibility"
subtitle: "Learning — base"
permalink: /decisions/2026-08-14-ho-enterprise-view-compatibility/
nav_order: 0
---
# metadata-xmlids:ho-enterprise-view-compatibility

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-14T01:55:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">cmr_ho_test ir.ui.view per-record savepoint reactivation and validation</div></div>
</div>

## Claim

Re-enabling quarantined metadata after restoring addon source must be done through ORM validation per view, not by bulk SQL. In this HO restore, 1,337 views reactivated successfully while 11 remained invalid because the stored XML referenced fields or actions absent from the mounted code/schema; leaving only those views inactive preserved a healthy full registry.

## Verification

verified_by_test

## Related agents

- `module.base`
- `module.web`
- `platform.metadata-xmlids`
- `platform.upgrade-migration`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/modules/web/overview.md`
- `knowledge/base-platform/metadata-xmlids.md`
- `knowledge/base-platform/upgrade-migration.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `base`
- `metadata-xmlids`
- `upgrade-migration`
- `testing-performance`

## Raw record

```json
{
  "id": "metadata-xmlids:ho-enterprise-view-compatibility",
  "module": "base",
  "claim": "Re-enabling quarantined metadata after restoring addon source must be done through ORM validation per view, not by bulk SQL. In this HO restore, 1,337 views reactivated successfully while 11 remained invalid because the stored XML referenced fields or actions absent from the mounted code/schema; leaving only those views inactive preserved a healthy full registry.",
  "source_type": "local_test",
  "source": "cmr_ho_test ir.ui.view per-record savepoint reactivation and validation",
  "odoo_version": "17.0",
  "observed_at": "2026-08-14T01:55:00Z",
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
      "id": "metadata-xmlids",
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
    "web"
  ],
  "related_agents": [
    "module.base",
    "module.web",
    "platform.metadata-xmlids",
    "platform.upgrade-migration",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/modules/web/overview.md",
    "knowledge/base-platform/metadata-xmlids.md",
    "knowledge/base-platform/upgrade-migration.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:ho-enterprise-source-restored",
      "relation": "depends_on"
    },
    {
      "id": "runtime-registry:ho-missing-enterprise-metadata-quarantine",
      "relation": "related_to"
    }
  ]
}
```