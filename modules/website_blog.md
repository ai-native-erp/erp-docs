---
layout: page
title: "Blog (website_blog)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_blog/
nav_order: 0
---
# Blog — `website_blog`

**Source:** [`agents/modules/generated/website_blog.yaml`](../../agents/modules/generated/website_blog.yaml) · **Wiki:** [`knowledge/modules/website_blog/overview.md`](../../knowledge/modules/website_blog/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_blog</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Blog</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_blog</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_blog"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Publish blog posts, announces, news

## Direct dependencies

[`website_mail`](website_mail.md), [`website_partner`](website_partner.md)

## Reverse dependencies (modules that depend on this)

[`test_website_modules`](test_website_modules.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>blog.blog</code></div><div class="role">defined by <code>website_blog</code></div></div>
<div class="model"><div class="name"><code>blog.post</code></div><div class="role">defined by <code>website_blog</code></div></div>
<div class="model"><div class="name"><code>blog.tag</code></div><div class="role">defined by <code>website_blog</code></div></div>
<div class="model"><div class="name"><code>blog.tag.category</code></div><div class="role">defined by <code>website_blog</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.qweb.field</code></div><div class="role">extended by <code>website_blog</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>website_blog</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_blog</code></div></div>
<div class="model"><div class="name"><code>website.cover_properties.mixin</code></div><div class="role">extended by <code>website_blog</code></div></div>
<div class="model"><div class="name"><code>website.multi.mixin</code></div><div class="role">extended by <code>website_blog</code></div></div>
<div class="model"><div class="name"><code>website.published.multi.mixin</code></div><div class="role">extended by <code>website_blog</code></div></div>
<div class="model"><div class="name"><code>website.searchable.mixin</code></div><div class="role">extended by <code>website_blog</code></div></div>
<div class="model"><div class="name"><code>website.seo.metadata</code></div><div class="role">extended by <code>website_blog</code></div></div>
<div class="model"><div class="name"><code>website.snippet.filter</code></div><div class="role">extended by <code>website_blog</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.test_website_modules` | required_by | `agents/modules/generated/test_website_modules.yaml` |
| `module.web_editor` | extends_model_from | `agents/modules/generated/web_editor.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_mail` | depends_on | `agents/modules/generated/website_mail.yaml` |
| `module.website_partner` | depends_on | `agents/modules/generated/website_partner.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_blog`](../../../agents/modules/generated/website_blog.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_blog)
- Direct dependencies: [`website_mail`](../website_mail/overview.md), [`website_partner`](../website_partner/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_website_modules`](../test_website_modules/overview.md)
- Impact graph: [`module:website_blog`](../../impact-graph.json)

## Purpose

Publish blog posts, announces, news

## Model relationships

- `blog.blog`
- `blog.post`
- `blog.tag`
- `blog.tag.category`
- Extends `ir.qweb.field` — defined by [`base`](../base/overview.md), [`web_editor`](../web_editor/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)
- Extends `website.cover_properties.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.multi.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.published.multi.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.searchable.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.seo.metadata` — defined by [`website`](../website/overview.md)
- Extends `website.snippet.filter` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.test_website_modules`](../../../agents/modules/generated/test_website_modules.yaml) — required_by
- [`module.web_editor`](../../../agents/modules/generated/web_editor.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_mail`](../../../agents/modules/generated/website_mail.yaml) — depends_on
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — depends_on

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`web_editor`](../web_editor/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
