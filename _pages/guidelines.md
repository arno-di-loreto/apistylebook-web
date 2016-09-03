---
layout: page
title: Design Guidelines
permalink: /design/guidelines/
date: 2016-08-18 22:31:09 +0200
menu: true
---
<ul>
  {% assign sorted_pages = (site.pages | where: "layout" , "guideline" | sort: 'sort') %}
  {% for page in sorted_pages %}
    <li>
      <h2>
        {{ page.data.type }} <a class="post-link" href="{{ page.url | prepend: site.baseurl | prepend: site.github.url}}">{{ page.guideline_company | escape }} - {{ page.guideline_title | escape }}</a>
      </h2>
    </li>
  {% endfor %}
</ul>