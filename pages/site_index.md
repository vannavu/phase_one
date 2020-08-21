---
title: Index
permalink: /site_index
layout: default
---

### Index

<ul class="index">
{% for post in site.posts %}
  <li>
    <a href="{{ site.url }}{{ post.url }}">{{ post.date | date: "%m.%d.%y" }} — {{ post.title }}</a>
  </li>
{% endfor %}
</ul>
