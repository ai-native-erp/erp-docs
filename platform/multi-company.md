---
layout: platform-page
title: "Multi-company and Context Boundaries"
subtitle: "Base-platform SME — multi company"
permalink: /platform/multi-company/
nav_order: 0
nav_title: "Multi-company and Context Boundaries"
---
# Multi-company and Context Boundaries

**Source:** [`agents/platform/multi-company.yaml`](../../agents/platform/multi-company.yaml) · **Wiki:** [`knowledge/base-platform/multi-company.md`](../../knowledge/base-platform/multi-company.md)

- Owner: [`platform.multi-company`](../../agents/platform/multi-company.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:multi-company`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Configuration, Defaults, Settings, and Sequences](configuration-settings.md) — [`platform.configuration-settings`](../../agents/platform/configuration-settings.yaml)
- [Licensing and Commercial Architecture Boundaries](licensing-commercial-boundaries.md) — [`platform.licensing-commercial-boundaries`](../../agents/platform/licensing-commercial-boundaries.yaml)
- [ORM, Fields, Environments, and Transactions](orm-transactions.md) — [`platform.orm-transactions`](../../agents/platform/orm-transactions.yaml)
- [Partners, Companies, Currency, and Localization Primitives](partner-localization.md) — [`platform.partner-localization`](../../agents/platform/partner-localization.yaml)
- [Security and Identity](security-identity.md) — [`platform.security-identity`](../../agents/platform/security-identity.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)

## Upstream evidence surfaces

- [`odoo/api.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/api.py)
- [`odoo/models.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/models.py)
- [`odoo/addons/base/models/res_company.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/res_company.py)

## High-risk changes

- allowed_company_ids
- company-dependent fields
- check_company
- cross-company leakage

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-11-odoo-licensing-product-architecture`](../conversations/2026-08-11-odoo-licensing-product-architecture.json)
