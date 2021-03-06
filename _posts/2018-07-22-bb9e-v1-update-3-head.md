---
layout: single
title: Sphere Robot BB9E V1 Project - Head / Dome
categories: projects
tags: bb9e
header:
  overlay_image: /assets/images/bb9e/starfield.jpg
  show_overlay_excerpt: true
  teaser: /assets/images/bb9e/bb9e-teaser.jpg
excerpt: BB9E Robot / Design and built from scratch by Alwurts
author_profile: false
sidebar:
  nav: "bb9e"
toc: true
toc_label: "Contents"
toc_icon: "cog"
comments: true
---
BB9E V1 Head / Dome
===========


The inside of the head will also contain electronic components which will give a better look to the robot such as RGB light and a speaker, more on that on the electronics section.

![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/bb9e/head-render.png){: .align-center} <center><small><i>Render of BB9E Head.</i></small></center>

The head will hold a light and a speaker to make BB9E more realistic with original sounds from the movies.

- WS8212 Single RGB Led: RGB Led with a single connection to drive it, makes it simple to control using libraries and also has enough brightness to be seen.
-	Speaker: A simple 8 ohm speaker can be used to play the sounds for BB9E.
-	Amplifier: An amplifier may be implemented if the sound from the speaker is too low.
-	SD Card with adaptor: Any low capacity card will work since its fairly low size files
-	ESP32/Nodemcu: The brains of the head will be a board that has Wi-Fi built in, with about 4 ports which are enough to drive the proposed functions; The board will be acting as Wifi client connected to the server in the Sphere board in order to play the sounds and change the lights at request.
-	Lithium battery: 1s1p battery, the circuit shouldn't need much current.
-	BMS: 1s battery protection and charging circuit.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.