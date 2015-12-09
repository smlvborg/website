---
layout: page
title: Events
link-title: Events
permalink: /events/
---

<ul class="post-list">
  {% for post in site.posts %}
    <li>
     
      <h2>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}"> {{ post.title }} <span class="post-meta"> - {{ post.date | date: "%b %-d, %Y" }}</span></a>
      </h2>
    </li>
  {% endfor %}
</ul>