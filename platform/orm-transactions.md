---
layout: platform-page
title: "ORM, Fields, Environments, and Transactions"
subtitle: "Base-platform SME — orm transactions"
permalink: /platform/orm-transactions/
nav_order: 0
nav_title: "ORM, Fields, Environments, and Transactions"
---
# ORM, Fields, Environments, and Transactions

**Source:** [`agents/platform/orm-transactions.yaml`](../../agents/platform/orm-transactions.yaml) · **Wiki:** [`knowledge/base-platform/orm-transactions.md`](../../knowledge/base-platform/orm-transactions.md)

- Owner: [`platform.orm-transactions`](../../agents/platform/orm-transactions.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:orm-transactions`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [HTTP, RPC, Controllers, and Sessions](http-rpc.md) — [`platform.http-rpc`](../../agents/platform/http-rpc.yaml)
- [Cron, Automation, and Background Work](jobs-automation.md) — [`platform.jobs-automation`](../../agents/platform/jobs-automation.yaml)
- [Multi-company and Context Boundaries](multi-company.md) — [`platform.multi-company`](../../agents/platform/multi-company.yaml)
- [Runtime, Registry, and Module Loading](runtime-registry.md) — [`platform.runtime-registry`](../../agents/platform/runtime-registry.yaml)
- [Security and Identity](security-identity.md) — [`platform.security-identity`](../../agents/platform/security-identity.yaml)
- [Testing, Performance, and Regression Control](testing-performance.md) — [`platform.testing-performance`](../../agents/platform/testing-performance.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)

## Upstream evidence surfaces

- [`odoo/models.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/models.py)
- [`odoo/fields.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/fields.py)
- [`odoo/api.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/api.py)
- [`odoo/sql_db.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/sql_db.py)

## High-risk changes

- recordset semantics
- cache/recompute
- transaction boundaries
- manual SQL

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-10-platform-troubleshooting-map`](../conversations/2026-08-10-platform-troubleshooting-map.json)
- [`2026-08-10-postgres-workbench-safety`](../conversations/2026-08-10-postgres-workbench-safety.json)
- [`2026-08-10-odoo-postgres-mcp`](../conversations/2026-08-10-odoo-postgres-mcp.json)
- [`2026-08-10-sale-servicenow-patterns`](../conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-11-sale-order-workspace`](../conversations/2026-08-11-sale-order-workspace.json)
- [`2026-08-11-owl-orm-rpc-data-access`](../conversations/2026-08-11-owl-orm-rpc-data-access.json)
- [`2026-08-11-owl-component-fundamentals`](../conversations/2026-08-11-owl-component-fundamentals.json)
