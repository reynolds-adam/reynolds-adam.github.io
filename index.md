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
  Welcome to my website. Check out some of the things I’ve been working on recently, and feel free to contact me if you have any questions.<br />

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
    btn_label: "Recent projects"
  - image_path: /assets/images/home/notes.jpg
    alt: "blog"
    title: "Blog"
    excerpt: "My Data Science Blog"
    url: "/blog/"
    btn_class: "btn--primary"
    btn_label: "All blog posts"

feature_row1:
  - image_path: /assets/images/home/project.jpg
    alt: "placeholder image 2"
    title: "Derrick Rose Joins the 50 Point Club"
    excerpt: "Even in his MVP season, D-rose never scored 50 points in a season. 5 years and several injuries later, he finally joined the club."
    url: "https://reynolds-adam.github.io/Derrick-Rose-50-Points/"
    btn_label: "Read More"
    btn_class: "btn--primary
	
feature_row2:
  - image_path: /assets/images/titanic.png
    alt: "placeholder image 2"
    title: "How to Survive the Titanic"
    excerpt: 'An analysis on how to survive the one of the deadliest shipwrecks in history'
    url: "https://reynolds-adam.github.io/projects/titanic/"
    btn_label: "Read More"
    btn_class: "btn--primary"
	
feature_row3:
  - image_path: /assets/images/basic/bell_curve.png
    alt: "placeholder image 2"
    title: "Is the Gaussian Distribution Really Normal?"
    excerpt: 'The sample text is nice because most people will not even read it anyway.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
	
feature_row4:
  - image_path: /assets/images/basic/wordcloud.png
    alt: "placeholder image 2"
    title: "Analysis of Twitter Text Data"
    excerpt: 'Are Canadians really as nice as they seem? How to they compare to Australians?'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"	
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="left" %}