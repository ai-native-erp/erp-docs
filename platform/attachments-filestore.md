---
layout: platform-page
title: "Attachments, Binary Serving, and Filestore"
subtitle: "Base-platform SME — attachments filestore"
permalink: /platform/attachments-filestore/
nav_order: 0
nav_title: "Attachments, Binary Serving, and Filestore"
---
# Attachments, Binary Serving, and Filestore

**Source:** [`agents/platform/attachments-filestore.yaml`](../../agents/platform/attachments-filestore.yaml) · **Wiki:** [`knowledge/base-platform/attachments-filestore.md`](../../knowledge/base-platform/attachments-filestore.md)

- Owner: [`platform.attachments-filestore`](../../agents/platform/attachments-filestore.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:attachments-filestore`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Asset Bundles and Frontend Foundation](assets-frontend.md) — [`platform.assets-frontend`](../../agents/platform/assets-frontend.yaml)
- [HTTP, RPC, Controllers, and Sessions](http-rpc.md) — [`platform.http-rpc`](../../agents/platform/http-rpc.yaml)
- [Security and Identity](security-identity.md) — [`platform.security-identity`](../../agents/platform/security-identity.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)
- [`web`](../modules/web/overview.md) — [`module.web`](../../agents/modules/generated/web.yaml)
- [`mail`](../modules/mail/overview.md) — [`module.mail`](../../agents/modules/generated/mail.yaml)

## Upstream evidence surfaces

- [`odoo/addons/base/models/ir_attachment.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_attachment.py)
- [`odoo/addons/base/models/ir_binary.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_binary.py)

## High-risk changes

- file access
- public tokens
- checksums
- storage consistency

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-14-ctl-fashion-isolated-restore`](../conversations/2026-08-14-ctl-fashion-isolated-restore.json)
