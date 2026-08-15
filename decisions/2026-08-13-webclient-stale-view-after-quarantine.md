---
layout: page
title: "frontend-owl-assets:stale-view-after-metadata-quarantine"
subtitle: "Learning — web"
permalink: /decisions/2026-08-13-webclient-stale-view-after-quarantine/
nav_order: 0
---
# frontend-owl-assets:stale-view-after-metadata-quarantine

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>web</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-13T14:00:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">cmr_ho_test product.product get_views; action 58 load; existing HO browser session</div></div>
</div>

## Claim

An already-open Odoo 17 SPA can continue parsing a previously fetched view architecture after its stale inherited view has been deactivated server-side. In the HO instance, a fresh product.product get_views response contained no last_purchase_cost reference while the existing browser tab still reported that undefined field; a full web-client reload is required after metadata quarantine.

## Verification

verified_by_test

## Related agents

- `module.web`
- `module.product`
- `platform.frontend-owl-assets`
- `platform.metadata-xmlids`

## Related wikis

- `knowledge/modules/web/overview.md`
- `knowledge/modules/product/overview.md`
- `knowledge/base-platform/frontend-owl-assets.md`
- `knowledge/base-platform/metadata-xmlids.md`

## Affected entities

- `web`
- `frontend-owl-assets`
- `metadata-xmlids`

## Raw record

```json
{
  "id": "frontend-owl-assets:stale-view-after-metadata-quarantine",
  "module": "web",
  "claim": "An already-open Odoo 17 SPA can continue parsing a previously fetched view architecture after its stale inherited view has been deactivated server-side. In the HO instance, a fresh product.product get_views response contained no last_purchase_cost reference while the existing browser tab still reported that undefined field; a full web-client reload is required after metadata quarantine.",
  "source_type": "local_test",
  "source": "cmr_ho_test product.product get_views; action 58 load; existing HO browser session",
  "odoo_version": "17.0",
  "observed_at": "2026-08-13T14:00:00Z",
  "confidence": "high",
  "verification": "verified_by_test",
  "affected_entities": [
    {
      "kind": "module",
      "id": "web",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "frontend-owl-assets",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "metadata-xmlids",
      "impact": "direct"
    }
  ],
  "related_modules": [
    "web",
    "product"
  ],
  "related_agents": [
    "module.web",
    "module.product",
    "platform.frontend-owl-assets",
    "platform.metadata-xmlids"
  ],
  "related_wikis": [
    "knowledge/modules/web/overview.md",
    "knowledge/modules/product/overview.md",
    "knowledge/base-platform/frontend-owl-assets.md",
    "knowledge/base-platform/metadata-xmlids.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:ho-unloaded-custom-metadata-quarantine",
      "relation": "depends_on"
    },
    {
      "id": "runtime-registry:ho-partial-registry-landing-repair",
      "relation": "related_to"
    }
  ]
}
```