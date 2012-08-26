---
layout: page
title: Chad DeShon
---
{% include JB/setup %}

<ul class="posts">
{% for page in paginator.posts %}
  {% include single_page.html %}
{% endfor %}
</ul>

