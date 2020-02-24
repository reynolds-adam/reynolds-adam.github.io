---
layout: splash
header:
  overlay_color: "#5e616c"
  overlay_filter: "0.5"
  overlay_image: /assets/images/Pages/home/computer.jpg
  actions:
    - label: "<i class='fas fa-file'></i>  See my resume"
      url: "/resume/"
excerpt: >
  Welcome to my website. Check out some of the things I’ve been working on recently, and feel free to contact me if you have any questions.<br>

intro:  
  - excerpt: '“If you just use the scientific method as a way to approach data-intensive projects, I think you’re more apt to be successful with your outcome.” *-* *Bob Hayes*'

about:
  - image_path: /assets/images/Pages/home/boat_home.jpg
    alt: "about"
    excerpt: "Hi, I’m Adam. I'm a data scientist, musician, motorcycle rider, woodworker, traveler, hiker, chef, volleyballer, snowboarder, learner, and more. To put it simply, I like creating things, solving problems, and having memorable experiences."
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
 
---
{% include feature_row id="intro" type="center" %}

<h1 align="center">About Me</h1>

{% include feature_row id="about" type="left"%}

<h1 align="center">Recent Posts</h1> <br>

{% include feature_row_latest_posts %}

<p align="center"><a href="https://adamreynoldsdata.com/blog/">All Posts</a></p>
