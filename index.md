---
title: "Data Science Portfolio"
layout: splash
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/home/computer.jpg
  actions:
    - label: "All Projects"
      url: "https://reynolds-adam.github.io/projects/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Welcome to my portfolio. Check out some of the projects I've been working on recently, and contact me if you have any questions."
intro: 
  - excerpt: '“If you just use the scientific method as a way to approach data-intensive projects, I think you’re more apt to be successful with your outcome.” *-* *Bob Hayes*'
recent:
  - title: "Recent Projects"  
  
feature_row:
  - image_path: assets/images/computer.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/computer.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/computer.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row1:
  - image_path: /assets/images/output_16_0.png
    alt: "placeholder image 2"
    title: "Derrick Rose Joins the 50 Point Club"
    excerpt: "Even in his MVP season, D-rose never scored 50 points in a season. 5 years and several injuries later, he finally joined the club."
    url: "https://reynolds-adam.github.io/Derrick-Rose-50-Points/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/titanic.png
    alt: "placeholder image 2"
    title: "How to Survive the Titanic"
    excerpt: 'An analysis on how to survive the one of the deadliest shipwrecks in history'
    url: "https://reynolds-adam.github.io/projects/titanic/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/bell_curve.png
    alt: "placeholder image 2"
    title: "Is the Gaussian Distribution Really Normal?"
    excerpt: 'The sample text is nice because most people will not even read it anyway.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/wordcloud.png
    alt: "placeholder image 2"
    title: "Analysis of Twitter Text Data"
    excerpt: 'Are Canadians really as nice as they seem? How to they compare to Australians?'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="recent" type="center" %}

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="left" %}