---
layout: page
title: "runtime-registry:file-complete-domain-extraction"
subtitle: "Learning — base"
permalink: /decisions/2026-08-11-repository-domain-extraction/
nav_order: 0
---
# runtime-registry:file-complete-domain-extraction

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-11T08:00:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">18.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">tools/extract_odoo_domain_knowledge.py; knowledge/source-inventory.json; knowledge/modules/*/code-map.json; knowledge/modules/*/domain.md</div></div>
</div>

## Claim

Repository-wide Odoo understanding should be generated from a deterministic, file-complete source inventory and evidence-backed semantic maps rather than manifest summaries alone. Per-module code maps now enumerate every file hash and extract models, fields and relations, methods and lifecycle rules, validations, controllers, XML records and references, menus and buttons, ACL CSV data, OWL services/registries, tests, personas, workflow entry points, and troubleshooting playbooks, while explicitly retaining static-analysis limits.

## Verification

verified_by_test

## Implementation

tools/extract_odoo_domain_knowledge.py

## Related agents

- `module.base`
- `platform.runtime-registry`
- `platform.metadata-xmlids`
- `platform.testing-performance`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/metadata-xmlids.md`
- `knowledge/base-platform/testing-performance.md`

## Affected entities

- `base`
- `runtime-registry`
- `metadata-xmlids`
- `testing-performance`

## Raw record

```json
{
  "id": "runtime-registry:file-complete-domain-extraction",
  "module": "base",
  "claim": "Repository-wide Odoo understanding should be generated from a deterministic, file-complete source inventory and evidence-backed semantic maps rather than manifest summaries alone. Per-module code maps now enumerate every file hash and extract models, fields and relations, methods and lifecycle rules, validations, controllers, XML records and references, menus and buttons, ACL CSV data, OWL services/registries, tests, personas, workflow entry points, and troubleshooting playbooks, while explicitly retaining static-analysis limits.",
  "source_type": "local_test",
  "source": "tools/extract_odoo_domain_knowledge.py; knowledge/source-inventory.json; knowledge/modules/*/code-map.json; knowledge/modules/*/domain.md",
  "odoo_version": "18.0",
  "observed_at": "2026-08-11T08:00:00Z",
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
      "id": "metadata-xmlids",
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
    "platform.metadata-xmlids",
    "platform.testing-performance"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/metadata-xmlids.md",
    "knowledge/base-platform/testing-performance.md"
  ],
  "related_learnings": [
    {
      "id": "testing-performance:customization-regression-rings",
      "relation": "extends"
    },
    {
      "id": "runtime-registry:troubleshoot-by-lifecycle-layer",
      "relation": "extends"
    }
  ],
  "implementation": "tools/extract_odoo_domain_knowledge.py"
}
```