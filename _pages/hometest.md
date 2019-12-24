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



<br>
<h1>Latest Posts</h1>
{% for post in site.posts limit:5 %}
<li><a href="{{ https://adamreynoldsdata.com/ }}{{ post.url }}">{{ post.title }}</a></li>  
{% endfor %}

<br>
<h1>Latest Posts</h1>
{% for post in site.posts limit:5 %}
<a href="{{ https://adamreynoldsdata.com/ }}{{ post.url }}">{{ post.title }}</a> 
<br>{{ post.date | date: "%B %d, %Y" }}
{% endfor %}


<br>
<h1>Latest Posts</h1>
{% for post in site.posts limit:5 %}
feature_row:
  - image_path: "assets\images\basic\wordcloud_small.png"
    alt: "about"
    title: {{ post.title }}
    excerpt: {{ post.excerpt }}
    url: "{{ https://adamreynoldsdata.com/ }}{{ post.url }}"
    btn_class: "btn--primary"
    btn_label: "Read more"

{% include feature_row id="feature_row" type="left" %}

{% endfor %}
