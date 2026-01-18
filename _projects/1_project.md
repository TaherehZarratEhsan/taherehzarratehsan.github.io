---
layout: page
title: Broiler-Net
description: AI-Based Monitoring of Poultry Behavior
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

In this project, we developed Broiler-Net, an AI-driven framework for real-time analysis of broiler chicken behavior in cage-free poultry houses. Our system integrates a deep convolutional object detector with a lightweight centroid-based tracking algorithm to continuously monitor individual chickens across video frames. By analyzing spatial proximity and motion patterns, we automatically detect two critical abnormal behaviors: huddling, which can indicate poor environmental conditions and increased mortality risk, and inactivity, an early marker of illness. The framework is optimized for efficiency, enabling deployment on edge devices in real farm environments. Our experimental results demonstrate high detection accuracy, highlighting the potential of AI-based monitoring systems to improve animal welfare, reduce economic losses, and support data-driven farm management. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/img.JPG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Broiler-Net: AI-powered poultry behavior monitoring for smart farming.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/img2.PNG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/img1.PNG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/img_h.JPG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Broiler-Net results illustrating, from left to right, chicken detection and tracking, huddling detection, and inactive chicken detection in real farm environments.
</div>