---
title: IoT Smarthome Security
layout: gridlay
sitemap: false
permalink: /research/iot-smarthome-security
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
<h2>IoT Smarthome Security</h2>

<ul>
  <li><b>The Insecurity of Home Digital Voice Assistants - Vulnerabilities, Attacks and Countermeasures</b>[CNS'18]
  </li>
  <div class="jumbotron">
Home Digital Voice Assistants (HDVAs) are getting popular in recent years. Users can control smart devices and get living assistance through those HDVAs (e.g., Amazon Alexa, Google Home) using voice. In this work, we study the insecurity of HDVA services by using Amazon Alexa and Google Home as case studies. We disclose three security vulnerabilities which root in their insecure access control. We then exploit them to devise two proof-of-concept attacks, home burglary and fake order, where the adversary can remotely command the victim’s HDVA device to open a door or place an order from Amazon.com or Google Express. The insecure access control is that HDVA devices not only rely on a single-factor authentication but also take voice commands even if no people are around them. We thus argue that HDVAs should have another authentication factor, a physical presence based access control; that is, they can accept voice commands only when any person is detected nearby. To this end, we devise a Virtual Security Button (VSButton), which leverages the WiFi technology to detect indoor human motions. Once any indoor human motion is detected, the HDVA device is enabled to accept voice commands. Our evaluation results show that it can effectively differentiate indoor motions from the cases of no motion and outdoor motions in both laboratory and real world settings.	
  </div>
  
  
    <ul class="subitem">
  		<li>Alexa service model</li>
  			<img src="{{site.baseurl}}assets/images/projects/Alexa-service-model.png" width="650" />
			<li>VSButton Design</li>
  			<img src="{{site.baseurl}}assets/images/projects/VSButton.png" width="650"/>  		
			<li>Indoor and outdoor CSI variations.</li>
  			<img src="{{site.baseurl}}assets/images/projects/Indoor-outdoor-CSI.png" width="650" /> 
		</ul>
  
  


  </ul>



</div>