---
layout: platform-page
title: "Runtime, Registry, and Module Loading"
subtitle: "Base-platform SME — runtime registry"
permalink: /platform/runtime-registry/
nav_order: 0
nav_title: "Runtime, Registry, and Module Loading"
---
# Runtime, Registry, and Module Loading

**Source:** [`agents/platform/runtime-registry.yaml`](../../agents/platform/runtime-registry.yaml) · **Wiki:** [`knowledge/base-platform/runtime-registry.md`](../../knowledge/base-platform/runtime-registry.md)

- Owner: [`platform.runtime-registry`](../../agents/platform/runtime-registry.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:runtime-registry`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Model Metadata, Modules, and XML IDs](metadata-xmlids.md) — [`platform.metadata-xmlids`](../../agents/platform/metadata-xmlids.yaml)
- [ORM, Fields, Environments, and Transactions](orm-transactions.md) — [`platform.orm-transactions`](../../agents/platform/orm-transactions.yaml)
- [Testing, Performance, and Regression Control](testing-performance.md) — [`platform.testing-performance`](../../agents/platform/testing-performance.yaml)
- [Module Upgrade, Migration, and Lifecycle](upgrade-migration.md) — [`platform.upgrade-migration`](../../agents/platform/upgrade-migration.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)

## Upstream evidence surfaces

- [`odoo/modules/registry.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/modules/registry.py)
- [`odoo/modules/loading.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/modules/loading.py)
- [`odoo/modules/graph.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/modules/graph.py)
- [`odoo/service/server.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/service/server.py)

## High-risk changes

- registry assembly
- module load order
- cache invalidation
- worker signaling

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-10-platform-troubleshooting-map`](../conversations/2026-08-10-platform-troubleshooting-map.json)
- [`2026-08-11-repository-domain-extraction`](../conversations/2026-08-11-repository-domain-extraction.json)
- [`2026-08-13-odoo-service-manager-mcp`](../conversations/2026-08-13-odoo-service-manager-mcp.json)
- [`2026-08-13-customer-addon-mount-preflight`](../conversations/2026-08-13-customer-addon-mount-preflight.json)
- [`2026-08-14-ctl-fashion-isolated-restore`](../conversations/2026-08-14-ctl-fashion-isolated-restore.json)
- [`2026-08-14-local-proprietary-dependency-consolidation`](../conversations/2026-08-14-local-proprietary-dependency-consolidation.json)
- [`2026-08-14-customer-source-lossless-delta-consolidation`](../conversations/2026-08-14-customer-source-lossless-delta-consolidation.json)
