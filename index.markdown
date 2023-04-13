---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
---

Asiashop MaiNgo

{% for product in site.data.products %}  
<div>{{product.name}} {{product.category}} </div>
{% endfor %} 

{% for file in site.static_files%}
{% if file.image %}
{{file.name}}
{% endif %}
{% endfor%}