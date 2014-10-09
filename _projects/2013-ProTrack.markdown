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

All algorithms and software were written in high-performance, cross platform C++ code that runs on iOS, Android, Linux, OS X, and Windows.

## Highlights

* $2500 grant from Yale Entrepreneurship Institute VCP

<a name="demo"></a>

## Demo

<figure>
	<div class="video-container">
	<iframe src="//www.youtube.com/embed/yd5Zg8STmus?rel=0" frameborder="0" allowfullscreen></iframe>
	</div>
	<figcaption>
	ProTrack Technology Demonstration
	</figcaption>

</figure>

<figure>
	{% assign url = "Personal_Projects/ProTrack/Demo/results.png" | prepend: site.dropbox_url %}
	<a href="{{url}}">
	<img class="fullwidth" src="{{url}}" />
	</a>
	<figcaption>
	Chart comparing distance measurements of the ProTrack versus those of the TrackMan gold standard. As can be seen, the relationship is quite linear. Mean error was 12.5 yards.
	</figcaption>

</figure>

## Technologies
C++, Python, OpenCV, CMake, Git

## More Information
Before building a smartphone-based golf ball flight tracker, the plan was to build an inexpensive radar to serve the same purpose. [Here is the original slide deck for that idea.](https://dl.dropboxusercontent.com/u/4354160/alitoiu/Personal_Projects/ProTrack/ProTrack_Deck.pdf)
