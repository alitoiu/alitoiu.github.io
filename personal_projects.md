---
layout: list_page
title: Personal Projects
permalink: /personal_projects/
navigation_index: 1
---

<ul class="posts projects">

{% assign even = "even" %}
{% assign sorted_projects = site.projects | sort: 'date' %}
{% for project in sorted_projects reversed %}
  {% if even == "even" %} {% assign even = "odd" %} 
  {% else %} {% assign even = "even" %}
  {% endif %}

  <li class="{{ even }}">

    <span class="post-date date">{{ project.date | date: "%Y" }}</span>

    <a class="post-link" href="{{ project.url | prepend: site.baseurl }}">
    	{% if project.thumbnail_rel_path %}
	    <img src="{{site.dropbox_url}}{{project.thumbnail_rel_path}}" class="thumbnail"/>
        {% endif %}
    </a>

    <div class="list-content">

	    <a class="post-link title" href="{{ project.url | prepend: site.baseurl }}">
	    	{{project.title}}
		</a>

	    <span class="description">
	    	{{project.description}}
		</span>

		{% if project.accolade1 %}
		<span class="accolade">
			<img src="{{site.dropbox_url}}Layout/check_green.png"/>
			<p>{{ project.accolade1 }}</p>
		</span>
		{% endif %}

	</div>

  </li>
{% endfor %}
</ul>
