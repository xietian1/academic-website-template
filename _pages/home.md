---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---
<!-- refine ul for smaller font -->
<style>
ol, 
ul{
    padding-left: 0.5rem;
    margin-top: 0;
    margin-bottom: 0.4rem;
}
</style>

### Welcome to SNMS Lab!

Welcome to to the website of Security, Networking, and Mobile Systems Research (SNMS) laboratory (@ 2153EB) in the Department of Computer Science and Engineering at Michigan State University (MSU). Our research interests are in the broad areas of security, IoT, mobile systems, and wireless networking, with a recent focus on innovating 5G/4G mobile network architecture/protocol/technologies, cellular/Wi-Fi IoT, secure cloud computing/services, blockchain technologies.

\
\
The SNMS laboratory is led by [Dr. Guan-Hua (Scott) Tu](https://www.cse.msu.edu/~ghtu/) at MSU.

--- 

<h4><font color="darkred">Recruiting</font></h4>
<p>
I am seeking highly motivated Ph.D., master, and undergraduate students to join my research team and work on innovative topics related to wireless/cellular networks, mobile/embedded systems, and network security. My current research projects include securing cellular networks (5G and beyond), Wi-Fi, mobile devices, and IoT. Detailed information on the SNMS lab's short- and medium-term research objectives can be found in our recent publications and NSF projects. As a member of the SNMS lab, you will have the opportunity to learn and apply a range of interdisciplinary technologies, including formal methodologies, machine learning, data mining, computer vision, and networking, to solve various research issues such as security vulnerabilities or performance issues. If you are interested in working with me, please email me your CV, transcripts, publications (if applicable), and research interests. I strongly encourage students with a strong background in formal methodologies (such as model checking) to contact me. In addition, visiting/exchange scholars or undergraduate students are welcome to contact me.
</p>	


---

#### Recent News

<div class="container-fluid" markdown="0">

<div id="recentnews" style="display: inline-block">
{% for article in site.data.news limit:10 %}
<ul>
    <li>[{{ article.date }}] {{ article.content }}</li> 
</ul>
{% endfor %}
</div>
<br>


<a href="{{site.baseurl}}/news"><button class="btn btn-primary btm-sm">See All News</button></a>
<br>
</div>

<!-- <div class="container">
<div class="row">
<center>
<img src="{{ site.url }}{{ site.baseurl }}/images/banner.jpg" width="100%"/><br/>
Examples of Feynman diagrams. <br/>
Feynman R., The theory of positrons. <i>Phys. Rev.</i> (1949)
</center>
</div>
</div>
<br/> -->

