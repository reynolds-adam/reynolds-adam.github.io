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

---

<div>
  {% for post in site.posts limit:3 %}
    {{ post.url }} <br>
    {{ post.related_image }} <br>
    <img src = "{{ post.related_image }}"> <br>
    <img src = {{ post.related_image }}> <br>
    {{ paginator.page }} <br>
    {{ post.title }} <br>
    {{ post.excerpt }} <br>
  {% endfor %}
</div>