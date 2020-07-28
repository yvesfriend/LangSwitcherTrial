---
title: Heading 3
body_classes: _lightcase-fullwidth_
enable_submenu: true

submenus:
    - name: Sub heading 1
    - name: Sub heading 2
    - name: Sub heading 3

content:
    items: @self.modular
    order:
        by: default
        dir: asc
        custom:
            - _section-as-header
            - _news
            - _faqs
            - _get-started
---