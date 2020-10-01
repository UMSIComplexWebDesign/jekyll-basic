---
layout: default
title: My Blogs Page
blog: "current"
---

Here are my blog posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

End loop.
