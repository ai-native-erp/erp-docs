---
layout: platform-page
title: "Views, Actions, QWeb, and Reports"
subtitle: "Base-platform SME — views actions qweb"
permalink: /platform/views-actions-qweb/
nav_order: 0
nav_title: "Views, Actions, QWeb, and Reports"
---
# Views, Actions, QWeb, and Reports

**Source:** [`agents/platform/views-actions-qweb.yaml`](../../agents/platform/views-actions-qweb.yaml) · **Wiki:** [`knowledge/base-platform/views-actions-qweb.md`](../../knowledge/base-platform/views-actions-qweb.md)

- Owner: [`platform.views-actions-qweb`](../../agents/platform/views-actions-qweb.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:views-actions-qweb`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Asset Bundles and Frontend Foundation](assets-frontend.md) — [`platform.assets-frontend`](../../agents/platform/assets-frontend.yaml)
- [HTTP, RPC, Controllers, and Sessions](http-rpc.md) — [`platform.http-rpc`](../../agents/platform/http-rpc.yaml)
- [Model Metadata, Modules, and XML IDs](metadata-xmlids.md) — [`platform.metadata-xmlids`](../../agents/platform/metadata-xmlids.yaml)
- [Security and Identity](security-identity.md) — [`platform.security-identity`](../../agents/platform/security-identity.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)
- [`web`](../modules/web/overview.md) — [`module.web`](../../agents/modules/generated/web.yaml)

## Upstream evidence surfaces

- [`odoo/addons/base/models/ir_ui_view.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_ui_view.py)
- [`odoo/addons/base/models/ir_actions.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_actions.py)
- [`odoo/addons/base/models/ir_qweb.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_qweb.py)

## High-risk changes

- view inheritance
- XPath stability
- action bindings
- rendering security

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-11-sale-order-workspace`](../conversations/2026-08-11-sale-order-workspace.json)
- [`2026-08-11-owl-orm-rpc-data-access`](../conversations/2026-08-11-owl-orm-rpc-data-access.json)
- [`2026-08-11-owl-component-fundamentals`](../conversations/2026-08-11-owl-component-fundamentals.json)
