---
title: Section 1
# enable_submenu: true

# submenus:
#     - name: Sub Heading 1
#       childmenu:
#           - name: Page 1
#             link: baseurl=>solutions/pageone
#             description: This is Page one
#           - name: Page 2
#             link: baseurl=>solutions/pagetwo
#             description: This is Page two
#           - name: Page 3
#             link: baseurl=>solutions/pagethree
#             description: this is page 3
#     - name: Sub Heading 2

content:
    items: @self.modular
    order:
        by: default
        dir: asc
        custom:
            - _section-as-header
            - _section-etc-content
            - _get-started
---