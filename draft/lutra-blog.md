---
layout: post
title: "Google Summer of Code 2019 : QGIS 3D Improvement"
date: 2019-09-09 00:00:00 +0000
comments: false
categories: [qgis, google summer of code, qgis 3d]
author: Ismail Sunni
image: /img/posts/input_logo.png
---
In this year Google Summer of Code (GSoC), there is a project involving QGIS 3D. <a href='https://ismailsunni.id'>Ismail Sunni</a> as the student with Martin Dobias and Peter Petrik as the mentors have implemented some new features for QGIS 3D.

<!-- more -->

# 3D On-Screen Navigation

<img alt='3D On-Screen Navigation' src='https://github.com/ismailsunni/GSoC-2019/raw/master/img/3d_on-screen_navigation.jpg' width="170" />

Previously, user can already navigate the 3D world by using mouse and keyboard. Unfortunately, for a new user it is not easy to start using them. 3D On-Screen Navigation will help navigating the 3D world. There are buttons to do zoom in/out, tilt up/down, pan up/down/left/right, and rotate the 3D map view. This feature can be activate from the 3D map view toolbar. See how to use it in <a href='https://www.youtube.com/watch?v=jp197BEymks'>this video</a>

# 3D Measurement Tool

<img alt='3D Measurement Tool' src='https://github.com/ismailsunni/GSoC-2019/raw/master/img/3d_measurement_tool.jpg' width="170" />

Now you can measure distance in 3D map view with considering the z-value. This tool is available in the 3D map view toolbar. It has the same UI as in 2D measurement tool with the same configuration (rubber band color, unit, decimal place, and keeping the base unit). It also has the same behavior (left-click to add a new point, middle-click to delete the last point, and right-click to restart the measurement). Now you can measure the distance between two building's top or lenght of river in a mountain. See the 3D measurement tool in action <a href='https://www.youtube.com/watch?v=gW0xu595HKA'>here</a>.

# 3D Rendering Point Feature as A Billboard

<img alt='3D Rendering Point Feature as A Billboard' src='https://github.com/ismailsunni/GSoC-2019/raw/master/img/3d_billboard_rendering_for_points.jpg' width="170" />

Rendering point 3D as billboard now is supported by QGIS. It allows you to show the point with QGIS symbol (e.g. marker, SVG, etc) that always face to the user and always has the same size. You can see sample usage in <a href='https://www.youtube.com/watch?v=_iCPqcXWxk0'>this video</a>.

You can also learn more about this GSoC project <a href='https://ismailsunni.github.io/GSoC-2019/'>here</a>.
