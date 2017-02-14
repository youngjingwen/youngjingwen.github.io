---
layout: default
---


  <ul class="postlist">
    {% for post in site.posts %}
      <li><a href="{{ post.url }}">{{ post.title }}<span>{{ post.date | date_to_string }}</span></a></li>
    {% endfor %}
  </ul>
