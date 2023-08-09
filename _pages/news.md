---
title: "News"
layout: textlay
sitemap: false
permalink: /news/
---
<!-- refine ul for smaller font -->
<style>
ol, 
ul{
    padding-left: 0.2rem;
    margin-top: 0;
    margin-bottom: 0.4rem;
}
</style>


## News

<div class="container">
{% for article in site.data.news %}
<ul>
<li><b>{{ article.date }}</b> {{ article.content }}</li>
</ul>

{% endfor %}
</div>
