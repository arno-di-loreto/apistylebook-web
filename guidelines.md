---
layout: page
title: Design Guidelines
permalink: /design/guidelines/
date: 2016-08-18 22:31:09 +0200
menu: true
---
<div class="container">
    <div class="row">
        {% assign sorted_pages = (site.pages | where: "layout" , "guideline" | sort: 'sort') %}
        {% for page in sorted_pages %}
        <div class="col-sm-6 col-md-4">
            <div class="thumbnail">
                <img src="{{ page.guideline_screenshotUrl | prepend: site.baseurl | prepend: site.github.url}}" alt="screenshot">
                <div class="caption">
                    <h3>{{ page.guideline_title | escape }}</h3>
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
    $(".thumbnail").height(Math.max.apply(null, $(".thumbnail").map(function() { return $(this).height(); })));
    //$(".caption").height(Math.max.apply(null, $(".caption").map(function() { return $(this).height(); }))); 
});
$(window).resize(function() {
    console.log('resize!');
    $(".thumbnail").height(Math.max.apply(null, $(".thumbnail").map(function() { return $(this).height(); })));
    //$(".caption").height(Math.max.apply(null, $(".caption").map(function() { return $(this).height(); })));
});
</script>