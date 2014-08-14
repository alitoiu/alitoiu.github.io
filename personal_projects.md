---
layout: page
title: Personal Projects
permalink: /personal_projects/
---

<div class="home">

  <ul class="posts">
    {% for project in site.projects %}
      <li>
        <span class="post-date">{{ project.date | date: "%b %-d, %Y" }}</span>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ project.title }}</a>
      </li>
    {% endfor %}
  </ul>

</div>


