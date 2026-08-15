---
layout: platform-page
title: "Asset Bundles and Frontend Foundation"
subtitle: "Base-platform SME — assets frontend"
permalink: /platform/assets-frontend/
nav_order: 0
nav_title: "Asset Bundles and Frontend Foundation"
---
# Asset Bundles and Frontend Foundation

**Source:** [`agents/platform/assets-frontend.yaml`](../../agents/platform/assets-frontend.yaml) · **Wiki:** [`knowledge/base-platform/assets-frontend.md`](../../knowledge/base-platform/assets-frontend.md)

- Owner: [`platform.assets-frontend`](../../agents/platform/assets-frontend.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:assets-frontend`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Attachments, Binary Serving, and Filestore](attachments-filestore.md) — [`platform.attachments-filestore`](../../agents/platform/attachments-filestore.yaml)
- [HTTP, RPC, Controllers, and Sessions](http-rpc.md) — [`platform.http-rpc`](../../agents/platform/http-rpc.yaml)
- [Testing, Performance, and Regression Control](testing-performance.md) — [`platform.testing-performance`](../../agents/platform/testing-performance.yaml)
- [Views, Actions, QWeb, and Reports](views-actions-qweb.md) — [`platform.views-actions-qweb`](../../agents/platform/views-actions-qweb.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)
- [`web`](../modules/web/overview.md) — [`module.web`](../../agents/modules/generated/web.yaml)
- [`web_editor`](../modules/web_editor/overview.md) — [`module.web_editor`](../../agents/modules/generated/web_editor.yaml)

## Upstream evidence surfaces

- [`odoo/addons/base/models/ir_asset.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_asset.py)
- [`odoo/tools/cache.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/tools/cache.py)

## High-risk changes

- bundle ordering
- cache busting
- OWL/QWeb compatibility
- global web regressions

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-10-sale-servicenow-patterns`](../conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-11-sale-order-workspace`](../conversations/2026-08-11-sale-order-workspace.json)
- [`2026-08-11-owl-orm-rpc-data-access`](../conversations/2026-08-11-owl-orm-rpc-data-access.json)
- [`2026-08-11-owl-component-fundamentals`](../conversations/2026-08-11-owl-component-fundamentals.json)
