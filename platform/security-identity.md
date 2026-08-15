---
layout: platform-page
title: "Security and Identity"
subtitle: "Base-platform SME — security identity"
permalink: /platform/security-identity/
nav_order: 0
nav_title: "Security and Identity"
---
# Security and Identity

**Source:** [`agents/platform/security-identity.yaml`](../../agents/platform/security-identity.yaml) · **Wiki:** [`knowledge/base-platform/security-identity.md`](../../knowledge/base-platform/security-identity.md)

- Owner: [`platform.security-identity`](../../agents/platform/security-identity.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:security-identity`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Attachments, Binary Serving, and Filestore](attachments-filestore.md) — [`platform.attachments-filestore`](../../agents/platform/attachments-filestore.yaml)
- [Configuration, Defaults, Settings, and Sequences](configuration-settings.md) — [`platform.configuration-settings`](../../agents/platform/configuration-settings.yaml)
- [HTTP, RPC, Controllers, and Sessions](http-rpc.md) — [`platform.http-rpc`](../../agents/platform/http-rpc.yaml)
- [Licensing and Commercial Architecture Boundaries](licensing-commercial-boundaries.md) — [`platform.licensing-commercial-boundaries`](../../agents/platform/licensing-commercial-boundaries.yaml)
- [Multi-company and Context Boundaries](multi-company.md) — [`platform.multi-company`](../../agents/platform/multi-company.yaml)
- [ORM, Fields, Environments, and Transactions](orm-transactions.md) — [`platform.orm-transactions`](../../agents/platform/orm-transactions.yaml)
- [Partners, Companies, Currency, and Localization Primitives](partner-localization.md) — [`platform.partner-localization`](../../agents/platform/partner-localization.yaml)
- [Views, Actions, QWeb, and Reports](views-actions-qweb.md) — [`platform.views-actions-qweb`](../../agents/platform/views-actions-qweb.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)
- [`auth_signup`](../modules/auth_signup/overview.md) — [`module.auth_signup`](../../agents/modules/generated/auth_signup.yaml)
- [`auth_oauth`](../modules/auth_oauth/overview.md) — [`module.auth_oauth`](../../agents/modules/generated/auth_oauth.yaml)
- [`auth_totp`](../modules/auth_totp/overview.md) — [`module.auth_totp`](../../agents/modules/generated/auth_totp.yaml)

## Upstream evidence surfaces

- [`odoo/addons/base/models/ir_rule.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_rule.py)
- [`odoo/addons/base/models/ir_model.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_model.py)
- [`odoo/addons/base/models/res_users.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/res_users.py)

## High-risk changes

- ACLs
- record rules
- sudo
- field groups
- public access

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-10-odoo-postgres-mcp`](../conversations/2026-08-10-odoo-postgres-mcp.json)
- [`2026-08-10-sale-servicenow-patterns`](../conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-11-owl-orm-rpc-data-access`](../conversations/2026-08-11-owl-orm-rpc-data-access.json)
- [`2026-08-11-owl-component-fundamentals`](../conversations/2026-08-11-owl-component-fundamentals.json)
