---
layout: platform-page
title: "Cron, Automation, and Background Work"
subtitle: "Base-platform SME — jobs automation"
permalink: /platform/jobs-automation/
nav_order: 0
nav_title: "Cron, Automation, and Background Work"
---
# Cron, Automation, and Background Work

**Source:** [`agents/platform/jobs-automation.yaml`](../../agents/platform/jobs-automation.yaml) · **Wiki:** [`knowledge/base-platform/jobs-automation.md`](../../knowledge/base-platform/jobs-automation.md)

- Owner: [`platform.jobs-automation`](../../agents/platform/jobs-automation.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:jobs-automation`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Configuration, Defaults, Settings, and Sequences](configuration-settings.md) — [`platform.configuration-settings`](../../agents/platform/configuration-settings.yaml)
- [ORM, Fields, Environments, and Transactions](orm-transactions.md) — [`platform.orm-transactions`](../../agents/platform/orm-transactions.yaml)
- [Module Upgrade, Migration, and Lifecycle](upgrade-migration.md) — [`platform.upgrade-migration`](../../agents/platform/upgrade-migration.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)
- [`base_automation`](../modules/base_automation/overview.md) — [`module.base_automation`](../../agents/modules/generated/base_automation.yaml)

## Upstream evidence surfaces

- [`odoo/addons/base/models/ir_cron.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_cron.py)
- [`odoo/addons/base/models/ir_actions.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_actions.py)
- [`odoo/addons/base/models/ir_autovacuum.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/ir_autovacuum.py)

## High-risk changes

- idempotency
- retry behavior
- locks
- privilege context
- observability

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.

## Conversation-derived learnings

- [`2026-08-10-sale-servicenow-patterns`](../conversations/2026-08-10-sale-servicenow-patterns.json)
