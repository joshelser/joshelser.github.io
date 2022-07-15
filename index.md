---
permalink: /
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
      <a href="{{ post.url }}">More...</a>
    </li>
  {% endfor %}
</ul>
