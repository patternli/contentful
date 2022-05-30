---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
# Hello World


{% for prod in site.data.contentful.davyjones.product %}
## {{ prod.title }}
{{ prod.short }}

{% endfor %}