---
layout: page
title: Personal Projects
permalink: /personal_projects/
---

<div class="home">

  <ul class="posts">
    {% assign sorted_projects = site.projects | sort: 'date' %}
    {% for project in sorted_projects reversed %}
      <li>
        <span class="post-date">{{ project.date | date: "%Y" }}</span>
        <a class="post-link" href="{{ project.url | prepend: site.baseurl }}">{{ project.title }}</a>
      </li>
    {% endfor %}
  </ul>

</div>