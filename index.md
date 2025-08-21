---
layout: single
title: "Welcome"
---

# About Me
Hi, I am Peter Perez. I am passionate about leveraging data analytics and machine learning to tackle complex scientific challenges in chemistry, engineering, and beyond. My background spans a Bachelor of Science in Chemistry from the Universidad Central de Venezuela and a PhD in Fuel Science from Penn State. Currently, I work as R&D Manager for a multinational oil & gas service company in Houston, Texas.

This blog is a space where I share my projects and insights, exploring how modern data science techniques can be used to clean, visualize, and analyze scientific data. I enjoy uncovering structure-property relationships, solving real-world problems, and advancing our understanding of chemical and engineering systems through data-driven approaches.

**Disclaimer:** The views expressed here are my own and do not represent those of my employer.

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
