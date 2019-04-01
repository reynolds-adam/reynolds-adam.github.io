---
permalink: /notes/
title: "Data Science Notes"
layout: collection
author_profile: false
type: pages
collection: notes
      
---

{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "notes" %}
    {% capture label %}{{ collection.label }}{% endcapture %}
    {% if label != written_label %}
      <h2 id="{{ label | slugify }}" class="archive__subtitle">{{ label }}</h2>
      {% capture written_label %}{{ label }}{% endcapture %}
    {% endif %}
  {% endunless %}
  {% for post in collection.docs %}
    {% unless collection.output == false or collection.label == "notes" %}
      {% include archive-single.html %}
    {% endunless %}
  {% endfor %}
{% endfor %}