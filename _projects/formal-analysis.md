---
title: Formal Analysis
layout: gridlay
sitemap: false
permalink: /research/formal-analysis
---

<style>
p {
    display: inline-block;
}
img {
    border-radius: 0%;
}

.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
	background-color: #ffffee;
	border: 1px dashed #cccccc;
}
pre{
    white-space: pre-wrap;  
    white-space: -moz-pre-wrap; 
    white-space: -pre-wrap; 
    white-space: -o-pre-wrap; 
    word-wrap: break-word; 
    width:100%; overflow-x:auto;
}
</style>

<div class="container" markdown="0">
<h2>Formal Analysis</h2>
  
<ul>
  <li><b>CNetVerifer: An Automated, Extensible Control-Plane Protocols Verication Technique</b> [SIGCOMM'14, IEEE/ACM ToN'15]
  </li>
  <div class="jumbotron">
  <!--The control-plane protocols in cellular
	networks communicate with each other, and provide a rich set of control functions vital to cellular networks over
	three dimensions, cross-layers, cross-domains (circuit-switched and packet-switched), and cross-systems (3G and
	4G). Despite their significance, the problem of verifying protocol correctness remains largely unaddressed due to
	its complex interaction patterns and inaccessibility of cellular network infrastructure. </br> </br>-->

	We develop <i>CNetVerifier</i>, an automated control-plane protocol interaction verification method with domain-specific heuristics and model checking techniques to systematically explore possible problematic interactions in cellular networks. The main advantage of this methodology is the exploration of problems/issues in mobile networks is not restricted by unlimited use scenarios (time consuming) or the lack of full access to mobile device or network infrastructure. Its impact on the wireless/mobile networking technology and cybersecurity can be considered as far-reaching. It does not only capture the fundamental design issues of mobile networks span over multiple dimensions, but also discover the security loopholes> caused by improper designs of control-plane protocols of mobile networks. The lessons we learnt can be even applied to the next big things (e.g., 5G, Internet of Thing, Device-to-Device communication) in the networking area.
	
	
  </div>
  
  
	
    <ul class="subitem">
  	<li>CNetVerifier Overview</li>
  		<img src="{{site.baseurl}}assets/images/projects/CNetVerifier.jpg" width="650" height="300" />  		
		</ul>
  
  <ul class="subitem">
  	<li>Cellular network control-plane protocol interaction</li>
  		<img src="{{site.baseurl}}assets/images/projects/protocol-interaction.png" width="650" height="190" />  		
		</ul>  

  <ul class="subitem">
  	<li>Finding summary</li>
  		<img src="{{site.baseurl}}assets/images/projects/findings.png" width="650" height="190"/>  		
		</ul>

  </ul>

</div>