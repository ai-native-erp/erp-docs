---
layout: page
title: "base:licensing-aware-product-boundaries"
subtitle: "Learning — base"
permalink: /decisions/2026-08-11-odoo-licensing-product-architecture/
nav_order: 0
---
# base:licensing-aware-product-boundaries

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-11T18:30:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">18.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">official_doc</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">https://www.odoo.com/documentation/18.0/legal/licenses.html; https://apps.odoo.com/apps/vendor-guidelines; https://apps.odoo.com/apps/faq; work-dir/odoo/LICENSE; /Users/srste/.codex/attachments/e7278c8d-2107-4dfa-8908-c3b64250ea5f/pasted-text.txt</div></div>
</div>

## Claim

Commercial Odoo products should be separately authored addons that extend Community, Enterprise, or third-party modules through declared dependencies, inheritance, and supported interfaces. Community 18 is LGPL-3; OEEL-1 and OPL-1 permit compatible dependent modules but prohibit redistribution of copies or modified copies of their proprietary software. Product review must additionally cover every transitive dependency, bundled asset, distribution channel, Enterprise/paid-addon entitlement, external-service and customer-data disclosure, tenant boundary, notices, and current marketplace rules.

## Verification

official

## Implementation

knowledge/product-architecture/licensing-playbook.md

## Related agents

- `module.base`
- `platform.licensing-commercial-boundaries`
- `platform.metadata-xmlids`
- `platform.upgrade-migration`
- `platform.multi-company`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/base-platform/licensing-commercial-boundaries.md`
- `knowledge/base-platform/metadata-xmlids.md`
- `knowledge/base-platform/upgrade-migration.md`
- `knowledge/base-platform/multi-company.md`

## Affected entities

- `base`
- `licensing-commercial-boundaries`
- `metadata-xmlids`
- `upgrade-migration`
- `multi-company`

## Raw record

```json
{
  "id": "base:licensing-aware-product-boundaries",
  "module": "base",
  "claim": "Commercial Odoo products should be separately authored addons that extend Community, Enterprise, or third-party modules through declared dependencies, inheritance, and supported interfaces. Community 18 is LGPL-3; OEEL-1 and OPL-1 permit compatible dependent modules but prohibit redistribution of copies or modified copies of their proprietary software. Product review must additionally cover every transitive dependency, bundled asset, distribution channel, Enterprise/paid-addon entitlement, external-service and customer-data disclosure, tenant boundary, notices, and current marketplace rules.",
  "source_type": "official_doc",
  "source": "https://www.odoo.com/documentation/18.0/legal/licenses.html; https://apps.odoo.com/apps/vendor-guidelines; https://apps.odoo.com/apps/faq; work-dir/odoo/LICENSE; /Users/srste/.codex/attachments/e7278c8d-2107-4dfa-8908-c3b64250ea5f/pasted-text.txt",
  "odoo_version": "18.0",
  "observed_at": "2026-08-11T18:30:00Z",
  "confidence": "high",
  "verification": "official",
  "affected_entities": [
    {
      "kind": "module",
      "id": "base",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "licensing-commercial-boundaries",
      "impact": "direct"
    },
    {
      "kind": "platform",
      "id": "metadata-xmlids",
      "impact": "related"
    },
    {
      "kind": "platform",
      "id": "upgrade-migration",
      "impact": "related"
    },
    {
      "kind": "platform",
      "id": "multi-company",
      "impact": "related"
    }
  ],
  "related_modules": [
    "base"
  ],
  "related_agents": [
    "module.base",
    "platform.licensing-commercial-boundaries",
    "platform.metadata-xmlids",
    "platform.upgrade-migration",
    "platform.multi-company"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/base-platform/licensing-commercial-boundaries.md",
    "knowledge/base-platform/metadata-xmlids.md",
    "knowledge/base-platform/upgrade-migration.md",
    "knowledge/base-platform/multi-company.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:file-complete-domain-extraction",
      "relation": "depends_on"
    }
  ],
  "implementation": "knowledge/product-architecture/licensing-playbook.md"
}
```