---
title: Mobile data charging security
layout: gridlay
sitemap: false
permalink: /research/mobile-data-charging-security
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
<h2>Mobile data charging security</h2>
  
<ul>
	
	<li><b>Accouting, Charging Issues, Security Attacks and Countermeasures on Mobile Data Networks [MOBICOM'12, CCS'12, MOBIYSY'13, CCS'14]</b>
  </li>
  <div class="jumbotron">
The accounting of data usage is the most important functionality in the management plane of cellular network. 
    However, we find that <u>the control-plane and management-plane functions of cellular network are not well designed from either charging accuracy or security aspect</u>.
  <br><br>
  In MOBICOM'12 and MOBISYS'13, our results yield three counter-intuitive findings: (1) <b>we are charged for what we never receive in extreme case</b>; (2) <b>we can obtain what we want in data access free of charge</b>; (3) <b>we pay for the packets dropped by cellular network during user mobility cross different systems</b>. We recognize that the fundamental problem is because the 3G/4G standards design a centralized network-element-based the accounting architecture. When things go wrong outside the charging elements, the resulting data volume deviates from what is observed at end devices.
<br><br>

    In CCS'12 and CCS'14,  we discover several security vulnerabilities along improper coordination between control-plane and management-plane. First, the decoupling of authentication, authorization, and accounting of data service gives a great opportunity to <b><u>attackers to send data packets which are spoofed with the fake source address</u></b>,  and the accounting element further charges the victim instead of the attacker. Second, <b><u>mobile device cannot request the network to stop the malicious spamming packets</u></b> have been accounted unless user tears down the bearer for all data services. We demonstrate that malicious attackers can incur any large traffic volume to the victim, while the victim may not be even aware of such spam traffic.
<br><br>

  Our contributions are to identify new security threat to cellular systems from the charging/accounting perspective and draw more people's attention to this important topic. 
  <font color="red"><b>Our research results have received several media reports including MIT review, Computer World, Fiscal Times, and TheVerge</b></font>. 
  <b>Three major US operators adopt our approach to fix the free data service problem</b>. 
  </div>

    <ul class="subitem">
  	<li><b>We pay for what we never get</b> (<u>User is overcharged while signal strength gets worse</u>)</li>
  		<img src="{{site.baseurl}}assets/images/projects/mobicom12-overcharged.jpg" width="750" />
  		<br>
  		
  			
   	<li><b>We pay nothing for what we get</b> (<u>Carriers does not charge DNS traffic (UDP:53) towards Internet at all</u>)</li>
  		<img src="{{site.baseurl}}assets/images/projects/mobicom12-free.jpg" width="750" />
    <li>We pay for mobility (Pay for the packets dropped by carriers during mobility on 13 routes)</li>
  		<img src="{{site.baseurl}}assets/images/projects/mobisys13-mobility.jpg" width="550" />
	  
		<li><b>Media report</b> </li>
			<a href="http://www.theverge.com/2012/9/20/3361904/wireless-data-carrier-overcharging-ucla-study">
  		<img src="{{site.baseurl}}assets/images/projects/mobicom12-news.jpg" width="750" />
  	</a>
  	 		
	</ul>
 

  </ul>

</div>