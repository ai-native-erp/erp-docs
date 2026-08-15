---
layout: platform-page
title: "Module Upgrade, Migration, and Lifecycle"
subtitle: "Base-platform SME — upgrade migration"
permalink: /platform/upgrade-migration/
nav_order: 0
nav_title: "Module Upgrade, Migration, and Lifecycle"
---
# Module Upgrade, Migration, and Lifecycle

**Source:** [`agents/platform/upgrade-migration.yaml`](../../agents/platform/upgrade-migration.yaml) · **Wiki:** [`knowledge/base-platform/upgrade-migration.md`](../../knowledge/base-platform/upgrade-migration.md)

- Owner: [`platform.upgrade-migration`](../../agents/platform/upgrade-migration.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:upgrade-migration`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Cron, Automation, and Background Work](jobs-automation.md) — [`platform.jobs-automation`](../../agents/platform/jobs-automation.yaml)
- [Licensing and Commercial Architecture Boundaries](licensing-commercial-boundaries.md) — [`platform.licensing-commercial-boundaries`](../../agents/platform/licensing-commercial-boundaries.yaml)
- [Model Metadata, Modules, and XML IDs](metadata-xmlids.md) — [`platform.metadata-xmlids`](../../agents/platform/metadata-xmlids.yaml)
- [Runtime, Registry, and Module Loading](runtime-registry.md) — [`platform.runtime-registry`](../../agents/platform/runtime-registry.yaml)
- [Testing, Performance, and Regression Control](testing-performance.md) — [`platform.testing-performance`](../../agents/platform/testing-performance.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)

## Upstream evidence surfaces

- [`odoo/modules/migration.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/modules/migration.py)
- [`odoo/modules/loading.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/modules/loading.py)
- [`odoo/addons/base/models/ir_module.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_module.py)

## High-risk changes

- schema migration
- hook ordering
- noupdate changes
- uninstall cleanup
- data preservation

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-10-odoo-customization-testing`](../conversations/2026-08-10-odoo-customization-testing.json)
- [`2026-08-11-odoo-licensing-product-architecture`](../conversations/2026-08-11-odoo-licensing-product-architecture.json)
- [`2026-08-13-odoo-service-manager-mcp`](../conversations/2026-08-13-odoo-service-manager-mcp.json)
- [`2026-08-13-customer-addon-mount-preflight`](../conversations/2026-08-13-customer-addon-mount-preflight.json)
- [`2026-08-14-customer-source-lossless-delta-consolidation`](../conversations/2026-08-14-customer-source-lossless-delta-consolidation.json)
