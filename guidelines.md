---
layout: default
title: Design Guidelines
permalink: /design/guidelines/
date: 2016-08-18 22:31:09 +0200
menu: true
---

<div class="container main-container full-jumbotron">
    <div class="jumbotron">
        <h1>{{ page.title | escape }}</h1>
        <p>
        Some companies share their API Design Guidelines with the community. Each one of theses documents has been analyzed to list covered topics.
        </p>
        <p>
        If you know some publicly available API guidelines which are not here don't hesitate to ping us on Twitter.
        </p>
    </div>
</div>

<div class="container body-container">
    <div class="row">
        {% assign sorted_pages = (site.pages | where: "layout" , "guideline" | sort: 'sort') %}
        {% for page in sorted_pages %}
        <div class="col-sm-6 col-md-4">
            <div class="thumbnail">
                <img src="{{ page.guideline_screenshotUrl | prepend: site.baseurl | prepend: site.github.url}}" alt="screenshot">
                <div class="caption">
                    <div class="same-height">
                        <h3>{{ page.guideline_title | escape }}</h3>
                    </div>
                    <p>{{ page.guideline_company | escape }}</p>
                    <p><a href="{{ page.url | prepend: site.baseurl | prepend: site.github.url}}" class="btn btn-primary" role="button">Explore</a></p>
                </div>
            </div>
        </div>
        {% endfor %}
    </div>
</div>
<script language="javascript">
$(window).ready(function() {
    $(".same-height").height(Math.max.apply(null, $(".same-height").map(function() { return $(this).height(); }))); 
});
$(window).resize(function() {
    console.log('resize!');
    $("same-height").height(Math.max.apply(null, $(".same-height").map(function() { return $(this).height(); })));
});
</script>