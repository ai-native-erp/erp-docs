---
layout: page
title: "testing-performance:customization-regression-rings"
subtitle: "Learning — base"
permalink: /decisions/2026-08-10-odoo-customization-testing/
nav_order: 0
---
# testing-performance:customization-regression-rings

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-10T14:40:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">18.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">work-dir/odoo/odoo/tests/common.py; work-dir/odoo/odoo/tests/loader.py; work-dir/odoo/odoo/tools/config.py; 547 test directories and 1555 test_*.py files in the pinned Odoo checkout</div></div>
</div>

## Claim

Odoo customizations should be tested in widening impact rings: the custom module, directly inherited modules, dependency and model-extension neighbors from the impact graph, the affected functional domain, and the complete standard suite for cross-cutting base-platform changes.

## Verification

verified_in_code

## Related agents

- `platform.testing-performance`
- `platform.upgrade-migration`
- `module.base`
- `module.web_tour`

## Related wikis

- `knowledge/base-platform/testing-performance.md`
- `knowledge/base-platform/upgrade-migration.md`
- `knowledge/modules/base/overview.md`
- `knowledge/modules/web_tour/overview.md`

## Affected entities

- `testing-performance`
- `base`
- `web_tour`

## Raw record

```json
{
  "id": "testing-performance:customization-regression-rings",
  "module": "base",
  "claim": "Odoo customizations should be tested in widening impact rings: the custom module, directly inherited modules, dependency and model-extension neighbors from the impact graph, the affected functional domain, and the complete standard suite for cross-cutting base-platform changes.",
  "source_type": "local_test",
  "source": "work-dir/odoo/odoo/tests/common.py; work-dir/odoo/odoo/tests/loader.py; work-dir/odoo/odoo/tools/config.py; 547 test directories and 1555 test_*.py files in the pinned Odoo checkout",
  "symbol": "odoo.tests.common.TransactionCase; odoo.tests.common.HttpCase; --test-enable; --test-tags",
  "odoo_version": "18.0",
  "observed_at": "2026-08-10T14:40:00Z",
  "confidence": "high",
  "verification": "verified_in_code",
  "affected_entities": [
    {
      "kind": "platform",
      "id": "testing-performance",
      "impact": "direct"
    },
    {
      "kind": "module",
      "id": "base",
      "impact": "direct"
    },
    {
      "kind": "module",
      "id": "web_tour",
      "impact": "related"
    }
  ],
  "related_modules": [
    "base",
    "web_tour"
  ],
  "related_agents": [
    "platform.testing-performance",
    "platform.upgrade-migration",
    "module.base",
    "module.web_tour"
  ],
  "related_wikis": [
    "knowledge/base-platform/testing-performance.md",
    "knowledge/base-platform/upgrade-migration.md",
    "knowledge/modules/base/overview.md",
    "knowledge/modules/web_tour/overview.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:troubleshoot-by-lifecycle-layer",
      "relation": "required_by"
    },
    {
      "id": "sale:servicenow-patterns-through-native-odoo",
      "relation": "applied_by"
    },
    {
      "id": "sale_order_extension:native-view-workspace-composition",
      "relation": "applied_by"
    }
  ],
  "conversation_context": "Annotation 1 requested that custom-module test structure and the Odoo-provided regression suite become retained team knowledge.",
  "test_management": {
    "backend": "Use TransactionCase for ORM and business behavior.",
    "http_and_ui": "Use HttpCase and tours for controllers, RPC, and browser behavior.",
    "isolation": "Run installation and tests in a disposable database, never the development database.",
    "selection": "Use --test-tags for bounded suites and --stop-after-init for deterministic CI completion."
  }
}
```