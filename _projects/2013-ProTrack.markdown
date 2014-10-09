---
layout: project
title:  "ProTrack"
description: "More information to come following invention disclosure"
thumbnail_rel_path: "Personal_Projects/ProTrack/thumbnail_no_ball_up.png"
accolade1: "$2,500 Grant from Yale Entrepreneurship Institute VCP"
demo: 1
date:   2013-01-01 12:00:00
---

## Description
Conceived, designed and implemented a computer vision algorithm to detect and track golf balls flying downrange  up to approximately 50 yards from an iPhone 5 video recording. Reprojected from 2-dimensional video into 3-dimensions, and extrapolated trajectory using Newtonian mechanics and Magnus effect. Achieved performance of 8% average error in tracking ball flight distance compared with gold standard on a sample of swings averaging 150 yards.

## Highlights

* $2500 grant from Yale Entrepreneurship Institute VCP

<a name="demo"></a>

## Demo

<figure>
	<div class="video-container">
	<iframe src="//www.youtube.com/embed/EI9toP46ji4?rel=0" frameborder="0" allowfullscreen></iframe>
	</div>
	<figcaption>
	Early Atlus Demo from July 11, 2012
	</figcaption>

</figure>

<figure>
	<div class="video-container">
	<iframe src="//www.youtube.com/embed/EI9toP46ji4?rel=0" frameborder="0" allowfullscreen></iframe>
	</div>
	<figcaption>
	Early Atlus Demo from July 11, 2012
	</figcaption>

</figure>

{% assign url = "Personal_Projects/ProTrack/Demo/trajectories.png" | prepend: site.dropbox_url %}
<a href="{{url}}">
<img class="fullwidth" src="{{url}}" />
</a>


{% assign url = "Personal_Projects/ProTrack/Demo/results.png" | prepend: site.dropbox_url %}
<a href="{{url}}">
<img class="fullwidth" src="{{url}}" />
</a>

## Early Pitch Deck
Before building a smartphone-based golf ball tracker, the plan was to build an inexpensive radar to serve the same purpose. [Here is the original slide deck for that idea.](https://dl.dropboxusercontent.com/u/4354160/alitoiu/Personal_Projects/ProTrack/ProTrack_Deck.pdf)

## Technologies
C++, Python, OpenCV, CMake, Git