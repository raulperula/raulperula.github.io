---
layout: post
title: Shadow Robotic Hand
download-link: 
download-alt:  
date: 2016-02-03
img: shadow_hand.png
alt: shadow-hand
category: robots
description: 
tags: [linux,ubuntu,open source]
article: yes

---

The Shadow Robotic Hand is an anthropomorphic robotic platform used for in-hand manipulation.

## Description

This platform was used in a European project called the _Handle Project_. My work was related to how to integrate an online classifier of objects of daily use using 2D (SIFT) and 3D (PointCloud) information for in-hand manipulation. This work was implemented in ROS.

This first video shows a simple classifier using 2D information from a RGBD Kinect camera.

{% include video.html url="//www.youtube.com/embed/uWT10xEzjhg" %}

The second video shows how the 2D approximation does not work properly only with 2D information.

{% include video.html url="//www.youtube.com/embed/sE9soglI-Rw" %}

Third video shows how it works the classifier using 3D information from a PointCloud, processing the data to improve the 2D information and avoiding occlusions.

{% include video.html url="//www.youtube.com/embed/u5mVW8YKgKk" %}

Finally, the next video shows the project resume about all the work developed at the UC3M (Spain) and the UPC (France).

{% include video.html url="//www.youtube.com/embed/KJybBorZjH0" %}
