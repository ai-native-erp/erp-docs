---
layout: platform-page
title: "HTTP, RPC, Controllers, and Sessions"
subtitle: "Base-platform SME — http rpc"
permalink: /platform/http-rpc/
nav_order: 0
nav_title: "HTTP, RPC, Controllers, and Sessions"
---
# HTTP, RPC, Controllers, and Sessions

**Source:** [`agents/platform/http-rpc.yaml`](../../agents/platform/http-rpc.yaml) · **Wiki:** [`knowledge/base-platform/http-rpc.md`](../../knowledge/base-platform/http-rpc.md)

- Owner: [`platform.http-rpc`](../../agents/platform/http-rpc.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:http-rpc`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Asset Bundles and Frontend Foundation](assets-frontend.md) — [`platform.assets-frontend`](../../agents/platform/assets-frontend.yaml)
- [Attachments, Binary Serving, and Filestore](attachments-filestore.md) — [`platform.attachments-filestore`](../../agents/platform/attachments-filestore.yaml)
- [ORM, Fields, Environments, and Transactions](orm-transactions.md) — [`platform.orm-transactions`](../../agents/platform/orm-transactions.yaml)
- [Security and Identity](security-identity.md) — [`platform.security-identity`](../../agents/platform/security-identity.yaml)
- [Views, Actions, QWeb, and Reports](views-actions-qweb.md) — [`platform.views-actions-qweb`](../../agents/platform/views-actions-qweb.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)
- [`web`](../modules/web/overview.md) — [`module.web`](../../agents/modules/generated/web.yaml)
- [`http_routing`](../modules/http_routing/overview.md) — [`module.http_routing`](../../agents/modules/generated/http_routing.yaml)

## Upstream evidence surfaces

- [`odoo/http.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/http.py)
- [`odoo/addons/base/models/ir_http.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_http.py)
- [`odoo/service/model.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/service/model.py)

## High-risk changes

- route authentication
- CSRF
- session lifecycle
- transaction retry
- serialization

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-10-platform-troubleshooting-map`](../conversations/2026-08-10-platform-troubleshooting-map.json)
- [`2026-08-10-sale-servicenow-patterns`](../conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-11-owl-orm-rpc-data-access`](../conversations/2026-08-11-owl-orm-rpc-data-access.json)
- [`2026-08-11-owl-component-fundamentals`](../conversations/2026-08-11-owl-component-fundamentals.json)
