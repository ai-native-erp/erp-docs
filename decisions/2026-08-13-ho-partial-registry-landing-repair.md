---
layout: page
title: "runtime-registry:ho-partial-registry-landing-repair"
subtitle: "Learning — base"
permalink: /decisions/2026-08-13-ho-partial-registry-landing-repair/
nav_order: 0
---
# runtime-registry:ho-partial-registry-landing-repair

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Observed at</div><div class="v">2026-08-13T13:51:00Z</div></div>
<div class="meta-card"><div class="k">Odoo version</div><div class="v">17.0</div></div>
<div class="meta-card"><div class="k">Confidence</div><div class="v">high</div></div>
<div class="meta-card"><div class="k">Source type</div><div class="v">local_test</div></div>
<div class="meta-card"><div class="k">Source</div><div class="v">cmr_ho_test ir_asset and mail_activity; web.assets_web.min.css; res.users/systray_get_activities</div></div>
</div>

## Claim

With a restored database and missing Enterprise source, HTTP 200 and login success can still lead to a broken web client. In this HO instance, an active ir.asset directive for a missing documents SCSS file produced a 376-byte CSS error bundle, while mail.activity rows for the absent approval.request model broke the systray RPC. Disabling the unavailable asset directive, regenerating CSS, and reversibly quarantining those activities restored the landing page pending installation of the matching Enterprise addons.

## Verification

verified_by_test

## Related agents

- `module.base`
- `module.web`
- `module.mail`
- `platform.runtime-registry`
- `platform.frontend-owl-assets`
- `platform.upgrade-migration`

## Related wikis

- `knowledge/modules/base/overview.md`
- `knowledge/modules/web/overview.md`
- `knowledge/modules/mail/overview.md`
- `knowledge/base-platform/runtime-registry.md`
- `knowledge/base-platform/frontend-owl-assets.md`
- `knowledge/base-platform/upgrade-migration.md`

## Affected entities

- `base`
- `runtime-registry`
- `frontend-owl-assets`
- `upgrade-migration`

## Raw record

```json
{
  "id": "runtime-registry:ho-partial-registry-landing-repair",
  "module": "base",
  "claim": "With a restored database and missing Enterprise source, HTTP 200 and login success can still lead to a broken web client. In this HO instance, an active ir.asset directive for a missing documents SCSS file produced a 376-byte CSS error bundle, while mail.activity rows for the absent approval.request model broke the systray RPC. Disabling the unavailable asset directive, regenerating CSS, and reversibly quarantining those activities restored the landing page pending installation of the matching Enterprise addons.",
  "source_type": "local_test",
  "source": "cmr_ho_test ir_asset and mail_activity; web.assets_web.min.css; res.users/systray_get_activities",
  "odoo_version": "17.0",
  "observed_at": "2026-08-13T13:51:00Z",
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
    "base",
    "web",
    "mail"
  ],
  "related_agents": [
    "module.base",
    "module.web",
    "module.mail",
    "platform.runtime-registry",
    "platform.frontend-owl-assets",
    "platform.upgrade-migration"
  ],
  "related_wikis": [
    "knowledge/modules/base/overview.md",
    "knowledge/modules/web/overview.md",
    "knowledge/modules/mail/overview.md",
    "knowledge/base-platform/runtime-registry.md",
    "knowledge/base-platform/frontend-owl-assets.md",
    "knowledge/base-platform/upgrade-migration.md"
  ],
  "related_learnings": [
    {
      "id": "runtime-registry:ho-enterprise-source-gap",
      "relation": "depends_on"
    },
    {
      "id": "runtime-registry:customer-addon-mount-preflight",
      "relation": "supports"
    }
  ]
}
```