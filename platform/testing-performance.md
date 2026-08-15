---
layout: platform-page
title: "Testing, Performance, and Regression Control"
subtitle: "Base-platform SME — testing performance"
permalink: /platform/testing-performance/
nav_order: 0
nav_title: "Testing, Performance, and Regression Control"
---
# Testing, Performance, and Regression Control

**Source:** [`agents/platform/testing-performance.yaml`](../../agents/platform/testing-performance.yaml) · **Wiki:** [`knowledge/base-platform/testing-performance.md`](../../knowledge/base-platform/testing-performance.md)

- Owner: [`platform.testing-performance`](../../agents/platform/testing-performance.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:testing-performance`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Asset Bundles and Frontend Foundation](assets-frontend.md) — [`platform.assets-frontend`](../../agents/platform/assets-frontend.yaml)
- [ORM, Fields, Environments, and Transactions](orm-transactions.md) — [`platform.orm-transactions`](../../agents/platform/orm-transactions.yaml)
- [Runtime, Registry, and Module Loading](runtime-registry.md) — [`platform.runtime-registry`](../../agents/platform/runtime-registry.yaml)
- [Module Upgrade, Migration, and Lifecycle](upgrade-migration.md) — [`platform.upgrade-migration`](../../agents/platform/upgrade-migration.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)
- [`web_tour`](../modules/web_tour/overview.md) — [`module.web_tour`](../../agents/modules/generated/web_tour.yaml)

## Upstream evidence surfaces

- [`odoo/tests`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/tests)
- [`odoo/addons/base/tests`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/tests)

## High-risk changes

- query growth
- cache behavior
- concurrency
- install/upgrade regressions
- tour coverage

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-10-odoo-customization-testing`](../conversations/2026-08-10-odoo-customization-testing.json)
- [`2026-08-10-platform-troubleshooting-map`](../conversations/2026-08-10-platform-troubleshooting-map.json)
- [`2026-08-10-postgres-workbench-safety`](../conversations/2026-08-10-postgres-workbench-safety.json)
- [`2026-08-10-odoo-postgres-mcp`](../conversations/2026-08-10-odoo-postgres-mcp.json)
- [`2026-08-10-sale-servicenow-patterns`](../conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-11-sale-order-workspace`](../conversations/2026-08-11-sale-order-workspace.json)
- [`2026-08-11-owl-component-fundamentals`](../conversations/2026-08-11-owl-component-fundamentals.json)
- [`2026-08-11-repository-domain-extraction`](../conversations/2026-08-11-repository-domain-extraction.json)
- [`2026-08-13-odoo-service-manager-mcp`](../conversations/2026-08-13-odoo-service-manager-mcp.json)
- [`2026-08-13-customer-addon-mount-preflight`](../conversations/2026-08-13-customer-addon-mount-preflight.json)
- [`2026-08-14-ctl-fashion-isolated-restore`](../conversations/2026-08-14-ctl-fashion-isolated-restore.json)
- [`2026-08-14-customer-source-lossless-delta-consolidation`](../conversations/2026-08-14-customer-source-lossless-delta-consolidation.json)
