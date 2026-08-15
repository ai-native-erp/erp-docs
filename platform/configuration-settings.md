---
layout: platform-page
title: "Configuration, Defaults, Settings, and Sequences"
subtitle: "Base-platform SME — configuration settings"
permalink: /platform/configuration-settings/
nav_order: 0
nav_title: "Configuration, Defaults, Settings, and Sequences"
---
# Configuration, Defaults, Settings, and Sequences

**Source:** [`agents/platform/configuration-settings.yaml`](../../agents/platform/configuration-settings.yaml) · **Wiki:** [`knowledge/base-platform/configuration-settings.md`](../../knowledge/base-platform/configuration-settings.md)

- Owner: [`platform.configuration-settings`](../../agents/platform/configuration-settings.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:configuration-settings`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Cron, Automation, and Background Work](jobs-automation.md) — [`platform.jobs-automation`](../../agents/platform/jobs-automation.yaml)
- [Multi-company and Context Boundaries](multi-company.md) — [`platform.multi-company`](../../agents/platform/multi-company.yaml)
- [Partners, Companies, Currency, and Localization Primitives](partner-localization.md) — [`platform.partner-localization`](../../agents/platform/partner-localization.yaml)
- [Security and Identity](security-identity.md) — [`platform.security-identity`](../../agents/platform/security-identity.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)

## Upstream evidence surfaces

- [`odoo/addons/base/models/ir_config_parameter.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_config_parameter.py)
- [`odoo/addons/base/models/ir_default.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_default.py)
- [`odoo/addons/base/models/ir_sequence.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_sequence.py)
- [`odoo/addons/base/models/res_config.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/res_config.py)

## High-risk changes

- secret storage
- global vs company scope
- sequence gaps
- module settings

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-10-postgres-workbench-safety`](../conversations/2026-08-10-postgres-workbench-safety.json)
- [`2026-08-10-odoo-postgres-mcp`](../conversations/2026-08-10-odoo-postgres-mcp.json)
