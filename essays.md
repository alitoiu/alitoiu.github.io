---
layout: page
title: Essays
permalink: /essays/
---

<div class="home">

  <ul class="posts">
    {% assign sorted_posts = site.posts | sort: 'date' %}
    {% for post in sorted_posts reversed %}
      <li>
        <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>

