---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/cover/test_header_shear_3.png
  actions:
    - label: "<i class='fas fa-download'></i> Install now"
      url: "/installation/"
excerpt: 
  Use ColorTuner tool
feature_row:

  - image_path: /assets/images/cover/cover_column_3.png
    alt: "100% free"
    title: "More information"
    excerpt: "Find out more about the requirements and objectives of the project."
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn more"   
youTube_id: -bwSsLItVi0
---

{% include feature_row %}


## What is ColorTuner?

Colortuner component implements three different image color filters in the next color spaces: RGB, HSV, YUV. It is an application to configure tailored color filters in HSV, RGB, or YUV color spaces. It is use to obtain optimal values of tint and saturation, as well as lighting, in that kind of filters. 

This tool only has one thread who cares about getting images and showing them through the GUI. ColorTuner connects the ROS image publisher driver (real or simulated), images from it and each image is shown through an GUI class (called viewer').


<img src="/assets/images/colortunerdocs.png" width="80%" height="60%">

Currently this tool is available in two branches:

1. ROS1 

It can be run used with Cameras and systems using ROS1 as middleware. To see how to use this tool visit the Installation and use page from the navigation bar.


Please watch the video below to see how to run this tool.

{% include video id= "-bwSsLItVi0" provider="youtube" %}
