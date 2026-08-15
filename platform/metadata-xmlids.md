---
layout: platform-page
title: "Model Metadata, Modules, and XML IDs"
subtitle: "Base-platform SME — metadata xmlids"
permalink: /platform/metadata-xmlids/
nav_order: 0
nav_title: "Model Metadata, Modules, and XML IDs"
---
# Model Metadata, Modules, and XML IDs

**Source:** [`agents/platform/metadata-xmlids.yaml`](../../agents/platform/metadata-xmlids.yaml) · **Wiki:** [`knowledge/base-platform/metadata-xmlids.md`](../../knowledge/base-platform/metadata-xmlids.md)

- Owner: [`platform.metadata-xmlids`](../../agents/platform/metadata-xmlids.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:metadata-xmlids`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Licensing and Commercial Architecture Boundaries](licensing-commercial-boundaries.md) — [`platform.licensing-commercial-boundaries`](../../agents/platform/licensing-commercial-boundaries.yaml)
- [Runtime, Registry, and Module Loading](runtime-registry.md) — [`platform.runtime-registry`](../../agents/platform/runtime-registry.yaml)
- [Module Upgrade, Migration, and Lifecycle](upgrade-migration.md) — [`platform.upgrade-migration`](../../agents/platform/upgrade-migration.yaml)
- [Views, Actions, QWeb, and Reports](views-actions-qweb.md) — [`platform.views-actions-qweb`](../../agents/platform/views-actions-qweb.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)

## Upstream evidence surfaces

- [`odoo/addons/base/models/ir_model.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_model.py)
- [`odoo/addons/base/models/ir_module.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_module.py)

## High-risk changes

- external ID stability
- noupdate behavior
- schema metadata
- install state

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-11-repository-domain-extraction`](../conversations/2026-08-11-repository-domain-extraction.json)
- [`2026-08-11-odoo-licensing-product-architecture`](../conversations/2026-08-11-odoo-licensing-product-architecture.json)
