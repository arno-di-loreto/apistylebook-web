---
layout: page
title: Design Topics
permalink: /design/topics/
date: 2016-08-18 22:31:09 +0200
menu: true
anchors: true
---
{% assign sorted_pages = (site.pages | where: "layout" , "topic" | sort: "sort" | group_by: "topic_category") %}
{% for category in sorted_pages %}
  <h2>{{category.name}}</h2>
  <div>
  {% for topic in category.items %}
    <h3><a href="{{ topic.url | prepend: site.baseurl | prepend: site.github.url}}">{{ topic.topic_name | escape }}</a></h3>
    <p>{{ topic.topic_description}}</p>
  {% endfor %}
  </div>
{% endfor %}
