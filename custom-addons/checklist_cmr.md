---
layout: custom-page
title: "checklist (checklist_cmr)"
subtitle: "Custom addon — RetailEnterprise/Store/checklist_cmr"
permalink: /custom-addons/checklist_cmr/
nav_order: 0
nav_title: "checklist"
---
# checklist

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>checklist_cmr</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/checklist_cmr</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v">1.0</div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

Checklist CMR — operational checklist definitions used by both Head Office and Store deployments.

> **Deployment target:** Store.

## Manifest excerpt

```python
{
    "name": "checklist",
    "version": "1.0",
    'depends': ['base', 'hr'],
    'data': ['security/ir.model.access.csv',
             'views/checklist_cmr.xml',
             'data/sequence.xml',
             'report/checklistscmr.xml', ],
    # 'images': ['static/description/icon.png'],
    'installable': True,
    'applicable': True,
    'license': 'LGPL-3',
}
```
