---
layout: page
title: "Website Live Chat (website_livechat)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_livechat/
nav_order: 0
---
# Website Live Chat — `website_livechat`

**Source:** [`agents/modules/generated/website_livechat.yaml`](../../agents/modules/generated/website_livechat.yaml) · **Wiki:** [`knowledge/modules/website_livechat/overview.md`](../../knowledge/modules/website_livechat/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_livechat</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Website Live Chat</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_livechat</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_livechat"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Chat with your website visitors

## Direct dependencies

[`im_livechat`](im_livechat.md), [`website`](website.md)

## Reverse dependencies (modules that depend on this)

[`test_discuss_full`](test_discuss_full.md), [`website_crm_livechat`](website_crm_livechat.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>im_livechat.channel</code></div><div class="role">defined by <code>website_livechat</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>chatbot.script</code></div><div class="role">extended by <code>website_livechat</code></div></div>
<div class="model"><div class="name"><code>chatbot.script.step</code></div><div class="role">extended by <code>website_livechat</code></div></div>
<div class="model"><div class="name"><code>discuss.channel</code></div><div class="role">extended by <code>website_livechat</code></div></div>
<div class="model"><div class="name"><code>im_livechat.channel</code></div><div class="role">extended by <code>website_livechat</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>website_livechat</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website_livechat</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_livechat</code></div></div>
<div class="model"><div class="name"><code>website.published.mixin</code></div><div class="role">extended by <code>website_livechat</code></div></div>
<div class="model"><div class="name"><code>website.visitor</code></div><div class="role">extended by <code>website_livechat</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.im_livechat` | depends_on, extends_model_from | `agents/modules/generated/im_livechat.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.test_discuss_full` | required_by | `agents/modules/generated/test_discuss_full.yaml` |
| `module.website` | depends_on, extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_crm_livechat` | required_by | `agents/modules/generated/website_crm_livechat.yaml` |
| `module.website_event` | extends_model_from | `agents/modules/generated/website_event.yaml` |
| `module.website_event_track` | extends_model_from | `agents/modules/generated/website_event_track.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_livechat`](../../../agents/modules/generated/website_livechat.yaml)
- Domain: `website_ecommerce`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_livechat)
- Direct dependencies: [`im_livechat`](../im_livechat/overview.md), [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_discuss_full`](../test_discuss_full/overview.md), [`website_crm_livechat`](../website_crm_livechat/overview.md)
- Impact graph: [`module:website_livechat`](../../impact-graph.json)

## Purpose

Chat with your website visitors

## Model relationships

- `im_livechat.channel`
- Extends `chatbot.script` — defined by [`im_livechat`](../im_livechat/overview.md)
- Extends `chatbot.script.step` — defined by [`im_livechat`](../im_livechat/overview.md)
- Extends `discuss.channel` — defined by [`im_livechat`](../im_livechat/overview.md), [`mail`](../mail/overview.md)
- Extends `im_livechat.channel` — defined by [`im_livechat`](../im_livechat/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)
- Extends `website.published.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.visitor` — defined by [`website`](../website/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — depends_on, extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.test_discuss_full`](../../../agents/modules/generated/test_discuss_full.yaml) — required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on, extends_model_from
- [`module.website_crm_livechat`](../../../agents/modules/generated/website_crm_livechat.yaml) — required_by
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — extends_model_from
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`im_livechat`](../im_livechat/overview.md), [`mail`](../mail/overview.md), [`website`](../website/overview.md), [`website_event`](../website_event/overview.md), [`website_event_track`](../website_event_track/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
