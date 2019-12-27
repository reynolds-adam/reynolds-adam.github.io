---
permalink: /hometest2/
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

<div class="feature__wrapper">

  {% for post in site.posts limit:3 %}
    {% capture post_url %}{{ post.url }}{% endcapture %}
    <div class="feature__item--left">
      <div class="archive__item">
        <div class="archive__item-teaser">
          <img src=assets/images/home/wordcloud_small.png>
        </div>
      </div>
      <div class="archive__item-body">
        <h2 class="archive__item-title">{{ post.title }}</h2>
        <div class="archive__item-excerpt">
          {{ post.excerpt | markdownify | remove: "<p>" | remove: "</p>" }}
          <p><a>href="https://adamreynoldsdata.com/Titanic/"</a></p>
        </div>
      </div>
    </div>
  {% endfor %}

</div>


<ul id="posts">
    {% for post in paginator.posts %}
 <a href="{{ post.url }}">
    <li>
      <div>
        {% assign foundImage = 0 %}
          {% assign images = post.content | split:"<img " %}
              {% for image in images %}
                {% if image contains 'src' %}
                    {% if foundImage == 0 %}
                    {% assign html = image | split:"/>" | first %}
                    <time>{{ post.date | date:"%d %b %Y" }}</time>
                    <h3>{{ post.title }}</h3>
                    <hr>
                    <div><img width="250" {{ html }} />{{ post.desc }}</div>
                     {% assign foundImage = 1 %}
                    {% endif %}
             {% endfor %}
        </div>
     </li>
 </a>
    {% endif %}
    {% endfor %}
</ul>