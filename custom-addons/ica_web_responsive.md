---
layout: custom-page
title: "ica_web_responsive (ica_web_responsive)"
subtitle: "Custom addon — RetailEnterprise/Store/ica_web_responsive"
permalink: /custom-addons/ica_web_responsive/
nav_order: 0
nav_title: "ica_web_responsive"
---
# ica_web_responsive

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>ica_web_responsive</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/ica_web_responsive</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

ica_web_responsive

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    'name': 'ICA Web Responsive',
    "author":"Agga, Ideacode Academy",
    'category': 'Hidden',
    'version': '1.0',
    'depends': ['web', 'base_setup'],
    'auto_install': ['web'],
    'data': [
        'views/webclient_templates.xml',
    ],
    'assets': {
        'web._assets_primary_variables': [
            ('after', 'web/static/src/scss/primary_variables.scss', 'ica_web_responsive/static/src/**/*.variables.scss'),
            ('before', 'web/static/src/scss/primary_variables.scss', 'ica_web_responsive/static/src/scss/primary_variables.scss'),
        ],
        'web._assets_secondary_variables': [
            ('before', 'web/static/src/scss/secondary_variables.scss', 'ica_web_responsive/static/src/scss/secondary_variables.scss'),
        ],
        'web._assets_backend_helpers': [
            ('before', 'web/static/src/scss/bootstrap_overridden.scss', 'ica_web_responsive/static/src/scss/bootstrap_overridden.scss'),
        ],
        'web.assets_frontend': [
            'ica_web_responsive/static/src/webclient/home_menu/home_menu_background.scss', # used by login page
            'ica_web_responsive/static/src/webclient/navbar/navbar.scss',
        ],
        'web.assets_backend': [
            'ica_web_responsive/static/src/webclient/**/*.scss',
            'ica_web_responsive/static/src/views/**/*.scss',

            'ica_web_responsive/static/src/core/**/*',
            'ica_web_responsive/static/src/webclient/**/*.js',
            ('after', 'web/static/src/views/list/list_renderer.xml', 'ica_web_responsive/static/src/views/list/list_renderer_desktop.xml'),
            'ica_web_responsive/static/src/webclient/**/*.xml',
            'ica_web_responsive/static/src/views/**/*.js',
            'ica_web_responsive/static/src/views/**/*.xml',

            # Don't include dark mode files in light mode
            ('remove', 'ica_web_responsive/static/src/**/*.dark.scss'),
        ],
        'web.assets_web': [
            ('replace', 'web/static/src/main.
```
