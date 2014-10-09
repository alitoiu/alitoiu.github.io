---
layout: list_page
title: Personal Projects
permalink: /personal_projects/
navigation_index: 1
---

There is no feeling quite like pushing the limits of what you can create. I have perpetually fought to extend this limit by working on technically interesting projects on my free time since the age of 12, when I wrote my first program. This is an archive of my process of doing so throughout the years. <span class="badge inline-badge first-badge">Tagged</span> projects would go on to become businesses.

<ul class="posts projects">

{% assign even = "even" %}
{% assign sorted_projects = site.projects | sort: 'date' %}
{% for project in sorted_projects reversed %}
  {% if even == "even" %} {% assign even = "odd" %} 
  {% else %} {% assign even = "even" %}
  {% endif %}

  {% if project.business %}
  {% assign highlight = "" %}
  {% else %}
  {% assign highlight = "" %}
  {% endif %}

  <li class="{{ even }} {{highlight}}">
	<div class="list-date">{{ project.date | date: "%Y" }}</div>

	<div class="list-substance">
	    <div class="list-image">
		    <a href="{{ project.url | prepend: site.baseurl }}">
		    	{% if project.thumbnail_rel_path %}
			    <img src="{{site.dropbox_url}}{{project.thumbnail_rel_path}}" class="thumbnail"/>
		        {% endif %}
		    </a>	
		</div>

	    <div class="list-content">

	    	<span class="title">
		    <a href="{{ project.url | prepend: site.baseurl }}">
		    	{{project.title}}
			</a>

			{%if project.business%}
			<span class="badge first-badge">
			Startup
			</span>
			{%endif%}
			{%if project.ongoing%}
			<span class="badge">
			Ongoing
			</span>
			{%endif%}
			</span>

		    <span class="description">
		    	{{project.description}}.

				{%if project.demo%}<span class="content-link"><a href="{{ project.url | prepend: site.baseurl }}#demo">[DEMO]</a></span>
		    	{%elsif project.images %}<span class="content-link"><a href="{{ project.url | prepend: site.baseurl }}#images">[IMAGES]</a></span>
		    	{%endif%}

			</span>

			{% if project.accolade1 %}
			<span class="accolade">
				<img src="{{site.dropbox_url}}Layout/check_green.png"/>
				<p>{{ project.accolade1 }}</p>
			</span>
			{% endif %}
			{% if project.accolade2 %}
			<span class="accolade">
				<img src="{{site.dropbox_url}}Layout/check_green.png"/>
				<p>{{ project.accolade2 }}</p>
			</span>
			{% endif %}
			{% if project.accolade3 %}
			<span class="accolade">
				<img src="{{site.dropbox_url}}Layout/check_green.png"/>
				<p>{{ project.accolade2 }}</p>
			</span>
			{% endif %}

		</div>
	</div>

  </li>
{% endfor %}
</ul>
