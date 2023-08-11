---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /complete-publications/
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
ul {
    margin-bottom: 0.05rem;
}
pre{
    white-space: pre-wrap;  
    white-space: -moz-pre-wrap; 
    white-space: -pre-wrap; 
    white-space: -o-pre-wrap; 
    word-wrap: break-word; 
    width:100%; overflow-x:auto;
}
.btn {
    font-size: 0.75rem;
    padding: 0.1rem 0.75rem;
    margin-top: 0;
}
</style>




<!-- Start -->

## Complete Publications

<div class="container">
### Journal/Magazine Publications
<div style="display: inline-block">
{% for entry in site.data.papers %}
<ul>
{% if entry.type == "journal"%}
<li>{% if entry.short-name %}<b>[{{ entry.short-name }}]</b>{% endif %} {{ entry.contents }}

{% if entry.pdf %}
<a href="{{ site.url }}{{ site.baseurl }}/papers/{{ entry.pdf }}" target="_blank"><button class="btn btn-success btn-xs">PDF</button></a>
{% endif %}

{% if entry.bibtex %}
<button class="btn btn-warning btn-xs"  onclick="toggleBib{{entry.title}}()">BIB</button>

<div class="jumbotron" id="a{{entry.title}}" style="display: none; background-color:#fff; border-radius:5px; padding:10px; background-color:#eef">
<pre>{{ entry.bibtex }}</pre> </div>

<script>
function toggleBib{{entry.title}}(parameter) {
    var x= document.getElementById('a{{entry.title}}');
    if (x.style.display === 'none') {
        x.style.display = 'block';
    } else {
        x.style.display = 'none';
    }
}
</script>
{% endif %}
</li> 
{% endif %}
</ul>
{% endfor %}

</div>
</div>

--- 

<div class="container">
### Conferences Publications
<div style="display: inline-block">
{% for entry in site.data.papers %}
<ul>
{% if entry.type == "conference"%}
<li>{% if entry.short-name %}<b>[{{ entry.short-name }}]</b>{% endif %} {{ entry.contents }}

{% if entry.pdf %}
<a href="{{ site.url }}{{ site.baseurl }}/papers/{{ entry.pdf }}" target="_blank"><button class="btn btn-success btn-xs">PDF</button></a>
{% endif %}

{% if entry.bibtex %}
<button class="btn btn-warning btn-xs"  onclick="toggleBib{{entry.title}}()">BIB</button>

<div class="jumbotron" id="a{{entry.title}}" style="display: none; background-color:#fff; border-radius:5px; padding:10px; background-color:#eef">
<pre>{{ entry.bibtex }}</pre> </div>

<script>
function toggleBib{{entry.title}}(parameter) {
    var x= document.getElementById('a{{entry.title}}');
    if (x.style.display === 'none') {
        x.style.display = 'block';
    } else {
        x.style.display = 'none';
    }
}
</script>
{% endif %}
{% if entry.slide %}
<a href="{{ site.url }}{{ site.baseurl }}/papers/{{ entry.slide }}" target="_blank"><button class="btn btn-info btn-xs">Slides</button></a>
{% endif %}
</li> 
{% endif %}
</ul>
{% endfor %}

</div>
</div>

---



<div class="container">
### US Patents (Granted)
<div style="display: inline-block">
<ol>
{% for entry in site.data.grants %}
<li>{{ entry.contents }}</li> 
{% endfor %}
</ol>
</div>
</div>

