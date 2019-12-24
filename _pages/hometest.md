---
permalink: /hometest/
layout: splash
header:
  overlay_color: "#5e616c"
  overlay_filter: "0.5"
  overlay_image: /assets/images/home/computer.jpg
  actions:
    - label: "<i class='fas fa-file'></i>  See my resume"
      url: "/resume/"
excerpt: 
  Welcome to my website. Check out some of the things I’ve been working on recently, and feel free to contact me if you have any questions.<br>

intro:  
  - excerpt: '“If you just use the scientific method as a way to approach data-intensive projects, I think you’re more apt to be successful with your outcome.” *-* *Bob Hayes*'

feature_row:
  - image_path: /assets/images/home/about-icon-256.png
    alt: "about"
    title: "About Me"
    excerpt: "Learn more than you probably care to know"
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  # - image_path: /assets/images/home/blog-icon-128.png
  #   alt: "projects"
  #   title: "Projects"
  #   excerpt: "Some projects I have been working on"
  #   url: "/recent-projects/"
  #   btn_class: "btn--primary"
  #   btn_label: "Recent projects"
  - image_path: /assets/images/home/resume-icon-512.png
    alt: "blog"
    title: "Blog"
    excerpt: "My Data Science Blog"
    url: "/blog/"
    btn_class: "btn--primary"
    btn_label: "All blog posts"      
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

<br>
<h1>Latest Posts</h1>
{% for post in site.posts limit:5 %}
<li><a href="{{ https://adamreynoldsdata.com/ }}{{ post.url }}">{{ post.title }}</a></li>  
{% endfor %}

<br>
<h1>Latest Posts</h1>
{% for post in site.posts limit:5 %}
<a href="{{ https://adamreynoldsdata.com/ }}{{ post.url }}">{{ post.title }}</a> 
<br>{{ post.date | format: 'short' }}
{% endfor %}