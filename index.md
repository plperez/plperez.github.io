---
layout: single
title: "Welcome"
---

# About Me
Hi, I’m Pedro. I work in R&D and write about chemistry, data science, and more.

# Latest Blog Posts
<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

[See all posts →](/blog/)
