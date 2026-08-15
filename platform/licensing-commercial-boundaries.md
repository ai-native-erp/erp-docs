---
layout: platform-page
title: "Licensing and Commercial Architecture Boundaries"
subtitle: "Base-platform SME — licensing commercial boundaries"
permalink: /platform/licensing-commercial-boundaries/
nav_order: 0
nav_title: "Licensing and Commercial Architecture Boundaries"
---
# Licensing and Commercial Architecture Boundaries

**Source:** [`agents/platform/licensing-commercial-boundaries.yaml`](../../agents/platform/licensing-commercial-boundaries.yaml) · **Wiki:** [`knowledge/base-platform/licensing-commercial-boundaries.md`](../../knowledge/base-platform/licensing-commercial-boundaries.md)

- Owner: [`platform.licensing-commercial-boundaries`](../../agents/platform/licensing-commercial-boundaries.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:licensing-commercial-boundaries`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Model Metadata, Modules, and XML IDs](metadata-xmlids.md) — [`platform.metadata-xmlids`](../../agents/platform/metadata-xmlids.yaml)
- [Multi-company and Context Boundaries](multi-company.md) — [`platform.multi-company`](../../agents/platform/multi-company.yaml)
- [Security and Identity](security-identity.md) — [`platform.security-identity`](../../agents/platform/security-identity.yaml)
- [Module Upgrade, Migration, and Lifecycle](upgrade-migration.md) — [`platform.upgrade-migration`](../../agents/platform/upgrade-migration.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)

## Upstream evidence surfaces

- [`LICENSE`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/LICENSE)
- [`addons/base/__manifest__.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base/__manifest__.py)

## High-risk changes

- license-incompatible dependency
- copied or modified proprietary source
- undisclosed external service or data transfer
- Enterprise subscription scope
- marketplace distribution obligations
- tenant and customer entitlement boundaries

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Product architecture playbook

Use the [licensing and commercial architecture checklist](../product-architecture/licensing-playbook.md) before selecting dependencies, copying code, packaging a module, connecting an external SaaS service, publishing to Odoo Apps, or provisioning tenants.

## Conversation-derived learnings

- [`2026-08-11-odoo-licensing-product-architecture`](../conversations/2026-08-11-odoo-licensing-product-architecture.json)
- [`2026-08-14-local-proprietary-dependency-consolidation`](../conversations/2026-08-14-local-proprietary-dependency-consolidation.json)
