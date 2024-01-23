---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Herbal Teas
layout: default
---
<ul class="row gap-4 p-0 h-100">
    {% for tea in site.data.herbal-teas %}
    <li class="col-xs-1 col-sm-2 col-md-3 col-lg-3 col-xl-4 card p-4">
        <a class="text-decoration-none" href={{tea.path}}>{{tea.name}}</a>
    </li>
    {% endfor %}
</ul>