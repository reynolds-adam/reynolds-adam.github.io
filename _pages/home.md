---
layout: splash
permalink: /home/
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/computer.jpg
  actions:
    - label: "<i class='fas fa-download'></i> Install now"
      url: "/docs/quick-start-guide/"
excerpt: >
  A flexible two-column Jekyll theme. Perfect for building personal sites, blogs, and portfolios.<br />
  <small><a href="">Latest release v4.16.0</a></small>
feature_row:
  - image_path: /assets/images/about/boat_home.jpg
    alt: "customizable"
    title: "About Me"
    excerpt: "Everything from the menus, sidebars, comments, and more can be configured or set with YAML Front Matter."
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/project.jpg
    alt: "fully responsive"
    title: "Projects"
    excerpt: "Built with HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
    url: "/projects/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/code.jpg
    alt: "100% free"
    title: "Code"
    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it... whatever!"
    url: "/notes/"
    btn_class: "btn--primary"
    btn_label: "More"      
---

{% include feature_row %}