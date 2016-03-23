---
layout: post
title: Brief information for ROS Indigo
link: 
link-alt: 
date: 2015-11-12
category: tricks
description: Guide for a installation and some tricks
article: yes
tags: [blog,how to,tutorial,ros,installation,indigo,ubuntu,14.04,robotics,baxter,simulator]

---

# Contents
{:.no_toc}

* This line will be replaced by the ToC, excluding the "Contents" header
{:toc}

# Installation

## For an Ubuntu 14.04 system

{% highlight bash %}
$ 
{% endhighlight %}

## For a Raspberry Pi 2 system

{% highlight bash %}
$ 
{% endhighlight %}

# Use

## Compilation

{% highlight bash %}
$ catkin
{% endhighlight %}

## roslaunch



# Templates

## Launch file

{% highlight xml %}
<?xml version="1.0" encoding="UTF-8"?>

<launch>
    <arg name="robot" />

    <group ns="$(arg robot)">
        <node name="some_skill" pkg="some_skill" type="node.py" output="screen" />
    </group>
</launch>
{% endhighlight %}
