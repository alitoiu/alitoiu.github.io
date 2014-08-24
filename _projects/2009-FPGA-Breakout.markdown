---
layout: project
title:  "FPGA Breakout"
description: "The classic Breakout game implemented entirely in hardware"
thumbnail_rel_path: "Personal_Projects/Brick_Breaker/title2.jpg"
date:   2009-01-01 12:00:00
---

## Description
The classic Breakout game implemented entirely in hardware on an Altera DE2 Board, with Cyclone II FPGA. 

Players can control the paddle on the bottom of the screen using the left and right arrow buttons on the keyboard. The game is displayed onto a VGA-connected monitor.

As the game was laid out directly in hardware, it was not possible to make use of a processor, RAM memory, software code, an operating system, a VGA driver, or a keyboard driver. Instead, all of the necessary functionality for the game was laid out using logic gates, making extensive use of finite state machine circuits.

The main components of the game include:

* Graphics
* Animation
* VGA driver
* Keyboard Driver
* Tracking and Updating Game State
* Collision Detection

## Demo
<div class="video-container">
<iframe src="//www.youtube.com/embed/ufZXXdFnxNQ?rel=0" frameborder="0" allowfullscreen></iframe>
</div>

## Images
<div class="fullwidth-gallery">
	<figure>
	{% assign url_results = "Personal_Projects/Brick_Breaker/DE2_Board.png" | prepend: site.dropbox_url %}
	<a href="{{url_results}}">
	<img src="{{url_results}}" />
	</a>
	<figcaption>Fig. 1 - Image of the Altera DE2 Board with Cyclone II FPGA
	</figcaption>
	</figure>

	<figure>
	{% assign url_results = "Personal_Projects/Brick_Breaker/Breakout_Image.png" | prepend: site.dropbox_url %}
	<a href="{{url_results}}">
	<img src="{{url_results}}" />
	</a>
	<figcaption>Fig. 2 - Image of the Breakout game being displayed on a monitor, pictured with the accompanying keyboard input device
	</figcaption>
	</figure>
</div>

## Technologies Used
Quartus, Verilog, Altera DE2 Board, Hardware VGA driver, PS/2 keyboard protocol