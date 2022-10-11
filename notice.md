---
layout: default
---
<ul>
  {% for notice in site.notices %}
    <li>
      <h2><a href="{{ notice.url  | absolute_url}}">{{ notice.title }}</a></h2>
      <p>{{ notice.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>