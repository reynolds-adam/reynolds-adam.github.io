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
---


<!-- <br>
<h1>Latest Posts</h1>
{% for post in site.posts limit:5 %}
<li><a href="{{ https://adamreynoldsdata.com/ }}{{ post.url }}">{{ post.title }}</a></li>  
{% endfor %}

<br>
<h1>Latest Posts</h1>
{% for post in site.posts limit:5 %}
<a href="{{ https://adamreynoldsdata.com/ }}{{ post.url }}">{{ post.title }}</a> 
<br>{{ post.date | date: "%B %d, %Y" }}
{% endfor %} -->


<br>
<h1>Latest Posts</h1>
{% for post in site.posts limit:5 %}
  post title: {{post.title}} <br>
  <a>href="{{ https://adamreynoldsdata.com/ }}{{ post.url }}"</a> <br>
  post url: {{post.url}} <br>
  post excerpt: {{post.excerpt}} <br>
  post alt : {{post.alt}}


{% endfor %}


<div class="feature__wrapper">

  {% for post in site.posts limit:3 %}
    {% capture post_url %}{{ post.url }}{% endcapture %}
    <div class="feature__item--left">
      <div class="archive__item">
        <div class="archive__item-teaser">
          <img src="assets\images\titanic.png">
            <span class="archive__item-caption"> Image Caption goes here</span>
        </div>
      </div>
      <div class="archive__item-body">
        <h2 class="archive__item-title">{{ post.title }}</h2>
        <div class="archive__item-excerpt">
          {{ post.excerpt | markdownify }}
          <p><a>href="https://adamreynoldsdata.com/Titanic/"</a></p>
        </div>
      </div>
    </div>
  {% endfor %}

</div>