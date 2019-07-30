---
layout: splash
header:
  overlay_color: "#5e616c"
  overlay_filter: "0.5"
  overlay_image: /assets/images/home/computer.jpg
  actions:
    - label: "<i class='fas fa-file'></i>  See my resume"
      url: "/resume/"
excerpt: >
  Welcome to my portfolio site. Check out some of the projects I’ve been working on recently, and feel free to contact me if you have any questions.<br />

intro:  
  - excerpt: '“If you just use the scientific method as a way to approach data-intensive projects, I think you’re more apt to be successful with your outcome.” *-* *Bob Hayes*'

feature_row:
  - image_path: /assets/images/home/boat_home.jpg
    alt: "about"
    title: "About Me"
    excerpt: "Learn more than you probably care to know"
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/home/project.jpg
    alt: "projects"
    title: "Projects"
    excerpt: "Some projects I have been working on"
    url: "/recent-projects/"
    btn_class: "btn--primary"
    btn_label: "Recent Projects"
  - image_path: /assets/images/home/notes.jpg
    alt: "blog"
    title: "Blog"
    excerpt: "My Data Science Blog"
    url: "/blog/"
    btn_class: "btn--primary"
    btn_label: "All Notes"      
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}