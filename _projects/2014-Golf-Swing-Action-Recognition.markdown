---
layout: project
title:  "Golf Swing Action Recognition"
description: "In-pocket mobile classifier to detect golf swings"
thumbnail_rel_path: "Personal_Projects/Golf_Recognition/thumbnail.png"
date:   2014-01-01 12:00:00
---

{% comment %}
_Ongoing project_

<span class="highlight">I am actively looking to collaborate with exceptional programmers, and machine learning experts on this project. If that sounds like you and this project interests you, [please get in touch!](mailto:litoiu@gmail.com)</span>
{% endcomment %}

## Description

In-pocket mobile classifier to detect when the user has performed a golf swing based on accelerometer readings. Records location of all swings via smartphone GPS, to enable playback of a round, including distances, and shot placement statistics. Requires no manual input, unlike comparable products on the market.

## Market Summary

The golf economy is $60 billion, annually, with golfers spending $6 billion on equipment. Products that give golfers statistics on their rounds are achieving some early success. For example, [Game Golf](http://www.amazon.com/GAME-Digital-Tracking-System-Black/dp/B00JDZWQZK) has raised $8 million dollars, and [GolfShot](http://golfshot.com/) has made over $50 million in revenue. However, both applications require a substantial amount of input from the user. A product that requires no user input to track statistics, and that delivers meaningful advice could dominate the market.

## Highlights
* Cross-platform event-based C++ code that runs on iPhone and Android
* Robust signal processing and feature extraction
* Machine learning data pipeline
* Efficient code takes up a fraction of iPhone 5 CPU while detecting swings

## Demo

<div class="fullwidth-gallery">

<figure>
	<div class="video-container">
	<iframe src="//www.youtube.com/embed/6L3Sd5EOcC0?rel=0" frameborder="0" allowfullscreen></iframe>
	</div>
	<figcaption>
	Golf Swing Recognition Demo
	</figcaption>

</figure>

</div>

## Technologies Used
C++, Boost Asio, dlib Machine Learning Library, Bash and Python Machine Learning Pipeline, dygraph Javascript visualization library, Git
