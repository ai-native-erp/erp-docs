---
layout: custom-page
title: "ultimate_pos_shortcuts (ultimate_pos_shortcuts)"
subtitle: "Custom addon — RetailEnterprise/Store/ultimate_pos_shortcuts"
permalink: /custom-addons/ultimate_pos_shortcuts/
nav_order: 0
nav_title: "ultimate_pos_shortcuts"
---
# ultimate_pos_shortcuts

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>ultimate_pos_shortcuts</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/ultimate_pos_shortcuts</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

ultimate_pos_shortcuts

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    'name': 'POS Keyboard Shortcut',
    'version': '17.0',
    'description': 'Reducing dependency on mouse clicks and touchscreens.',
    'summary': 'Reducing dependency on mouse clicks and touchscreens.',
    'author': 'Mathys',
    'website': 'https://ahmadyusup.com/pos-keyboard-shortcuts',
    'license': 'OPL-1',
    'category': 'Sales',
    'depends': [
        'base','point_of_sale'
    ],
    'data': [
        'views/index.xml',
    ],
    'images': [
        'static/description/main_screenshot.png',
    ],
    'auto_install': False,
    'application': False,
    'assets': {
        'point_of_sale._assets_pos': [
            'ultimate_pos_shortcuts/static/src/app/screens/**/*',
            'ultimate_pos_shortcuts/static/src/app/navbar/**/*',
            'ultimate_pos_shortcuts/static/src/app/category_selector/**/*',
            'ultimate_pos_shortcuts/static/src/app/keyboard_shortcuts/**/*',
            'ultimate_pos_shortcuts/static/src/app/pos_app.js',
            'ultimate_pos_shortcuts/static/src/app/pos_app.xml',
        ],
        'ultimate_pos_shortcuts.hotkeys': [
            ('include', 'point_of_sale._assets_pos'),
            'ultimate_pos_shortcuts/static/src/app/main.js',
        ],
    }
}
```
