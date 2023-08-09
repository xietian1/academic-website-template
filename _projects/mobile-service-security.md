---
title: Mobile Service Security
layout: gridlay
sitemap: false
permalink: /research/mobile-service-security
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
<h2>Mobile Service Security</h2>
  
<ul>
	
	
  <li>
  <b>The Dark Side of Operational Wi-Fi Calling Services [CNS'18, <font color="red">best paper award</font>]</b> 
  </li>

  <div class="jumbotron">All of four major U.S. operators have rolled out nationwide Wi-Fi calling services. They are projected to surpass VoLTE (Voice over LTE) and other VoIP services in terms of mobile IP voice usage minutes in 2018. They enable mobile users to place cellular calls over Wi-Fi networks based on the 3GPP IMS (IP Multimedia Subsystem) technology. Compared with conventional cellular voice solutions, the major difference lies in that their traffic traverses untrustful Wi-Fi networks and the Internet. This exposure to insecure networks may cause the Wi-Fi calling users to suffer from security threats. Its security mechanisms are similar to the VoLTE, because both of them are supported by the IMS. They include SIM-based security, 3GPP AKA (Authentication and Key Agreement), IPSec (Internet Protocol Security), etc. However, are they sufficient to secure WiFi calling services? Unfortunately, our study yields a negative answer. 
  
  In this work, we explore security issues of the operational Wi-Fi calling services in three major U.S. operators’ networks using commodity devices. We disclose that current Wi-Fi calling security is not bullet-proof. We uncover four vulnerabilities which stem from improper standard designs, device implementation issues and network operation slips. By exploiting them, we devise two proof-of-concept attacks: user privacy leakage and telephony harassment or denial of voice service (THDoS); they can bypass the security defenses deployed on both mobile devices and network infrastructure. We have confirmed their feasibility and simplicity using real-world experiments, as well as assessed their potential damages and proposed recommended solutions.

	We actively contact and report the security issues we discovered to WiFi Calling device manufacturers, e.g.,Google, and WiFi calling service providers, such as Verizon, AT&T, and T-Mobile. We had received positive feedback from them. E.g., <u>Google Android security team has recognized the security issues we discovered. The problem will be fixed on Google Android phones at the next possible patch opportunity.</u></div>
	
    <ul class="subitem">
  	<li>WiCA (WiFi Calling Analyzer) (<u>Discover six WiFi calling events</u>)</li>
  		<img src="{{site.baseurl}}assets/images/projects/wica-design.png" alt="WiCA" width="650" />
  	<li>Six WiFi calling events	(I: Activating Wi-Fi calling service, II: Receiving an incoming call, III: Dialing an outgoing call, IV: Sending a text, V: Receiving a text, VI: Deactivating Wi-Fi calling service)</li>	
  		<img src="{{site.baseurl}}assets/images/projects/six-wifi-calling-events.png" alt="Six Events" width="650" />
  		<br>
  		<div class="jumbotron">
			<b>Demo 1: </b><a href="{{site.baseurl}}assets/images/projects/Default-WiFi-calling-security-mechanism-WiFi2Cellular-Switch.mpg">[Default secuirty defense, WiFi2Cellular-Switch]</a>      
			<br>
			<b>Demo 2: </b><a href="{{site.baseurl}}assets/images/projects/Annoying-Incoming-Attack-Drop-180-Ringing.mp4">[Annoying incoming call attack]</a> <br>
			<b>Demo 3: </b><a href="{{site.baseurl}}assets/images/projects/Telephony-Harassment-Denial-of-Service-Attack.mp4">[THDoS Telephony Harassment/DoS attack]</a>    	 
  		</div>
  	
  	<li><b>Media report</b> </li>
  		MSU Today: <a href="https://msutoday.msu.edu/news/2018/protect-your-phone-data-from-grinches/">
  			<img src="{{site.baseurl}}assets/images/projects/wifi-calling-news.png" width="750" height="300"/>
  		</a><br>
  		Futurity:  <a href="https://www.futurity.org/phone-hackers-wifi-shopping-1924842-2/">
  			<img src="{{site.baseurl}}assets/images/projects/wifi-calling-news2.png" width="750" height="300"/>
  		</a>	
  		   
		</ul>

  <li>
  <b>New Security Threats Caused by IMS-based SMS Service in 4G LTE Networks [CCS'16]</b> 
  </li>
  <div class="jumbotron">
		SMS (Short Messaging Service) is a text messaging service for mobile users to exchange short text messages. It is also widely used to provide SMS-powered services (e.g., mobile banking). With the rapid deployment of all-IP 4G mobile networks, the underlying technology of SMS evolves from the legacy circuit-switched network to the IMS (IP Multimedia Subsystem) system over packetswitched network. In this work, we study the insecurity of the IMS-based SMS. We uncover its security vulnerabilities and exploit them to devise four SMS attacks: silent SMS abuse, SMS spoofing, SMS client DoS, and SMS spamming. We further discover that those SMS threats can propagate towards SMS-powered services, thereby leading to three malicious attacks: social network account hijacking, unauthorized donation, and unauthorized subscription. Our analysis reveals that the problems stem from the loose security regulations among mobile phones, carrier networks, and SMS-powered services. We finally propose remedies to the identified security issues.
		<br><br>
		
		We actively contact and report the security issues we discovered to cellular network operators (e.g. Verizon) and SMS-powered service providers such as Facebook. <u>We had received positive feedback from the industry. Both of Verizon and Facebook reconginzed the security issues we discovered and fixed them accordingly.</u>
  </div>
  
    <ul class="subitem">
  	<li>Compromise Facebook accounts without passwords</li>
  		<div class="jumbotron"><b>Demo 1: </b><a href="{{site.baseurl}}assets/images/projects/fb-update-status.mpg">[Update the victim's FB status]</a>      
      <br>
      <b>Demo 2: </b><a href="{{site.baseurl}}assets/images/projects/fb-like-page.mpg">[Like a page on behalf of a victim]</a> <br>
			<b>Demo 3: </b><a href="{{site.baseurl}}assets/images/projects/fb-add-friend.mpg">[Add a person to a victim's friend list]</a>    	 
  		</div>   
		</ul>
	
  <li>
  <b>New Security Threats towards Data Service by Exploiting Control-Plane of Voice Services [MOBICOM'13, CCS'15, CNS'15]</b> 
  </li>
  <div class="jumbotron">
  	There are two voice solutions for 4G LTE users: CSFB (Circuit-Switched FallBack) and VoLTE (Voice Over LTE). Our study shows that both of them introduced new security threats towards individuals or carrier networks due to their improper control-plane designs.
	  <br>
	  <br>
    For <b>CSFB</b>, its control-plane is designed to switch 4G user back to 2G/3G to access CS voice service. If 4G users refuse the inter-system switch, they cannot dial any calls or receive calls. In MOBICOM'13, we discovered that voice calls may incur throughput drop (up to 83.4%)or even transmission stop for seconds, lost 4G connectivity, and application aborts for data sessions due to its inappropriate control-plane design. 
   
    In CNS'15, we demonstrate how the adversary remotely launches the ping-pong attacks to (1)tear down all TCP connections within few minutes, (2)get Internet applications aborted, or (3)deprive users' 4G LTE connectivity without their consent.
    <br>
	<br>

    For <b>VoLTE</b>, we devise four novel attacks: 
    (1) free-data attack, accessing Internet at no cost in two tier-one US carrier networks; 
    (2) Data DoS attack, shutting down any ongoing data service at the victim by injecting high-rate spamming traffic to the high-priority signaling bearer reserved for VoLTE control-plane; 
    (3) Overbilling attack, bypassing NAT/Firewall deployed by carriers, inject the spamming packets towards victim phones from internal mobile device and the victims have to pay for those unsolicited packets; 
    (4) Voice Muted attack, caller and callee cannot hear each other over phones.
      <br><br>
  		
	We actively coworked with tier-one US carriers, e.g., Verizon and T-Mobile, and fixed the security loopholes we discovered, and had received the postive feedback from those carriers. The National Science Foundation (NSF) also funded us to continue the study of the security vulnerabilities of control-plane and impacts on the data-plane of current and 5G mobile networks (Award number: CNS-1528122).
  </div>

  
  <ul class="subitem">
  	<li>Ping-Pong Attack (<u>Tear down all TCP connections within few minutes and largely downgrade UDP throughput</u>)</li>
  		<img src="{{site.baseurl}}assets/images/projects/CNS-attack.jpg" alt="Ping-Pong Attack" width="650" />
  	<li>Free-Data-Service, Data Dos, Overbilling, Voice Muted Attacks (<u>Abuse VoLTE signaling bearer</u>)		
  		<img src="{{site.baseurl}}assets/images/projects/CCS15-attack.jpg" alt="VoLTE Attack" width="650" />
  		<br>
  	<div class="jumbotron"><b>Demo 1: </b><a href="{{site.baseurl}}assets/images/projects/free-data-service.mp4">[Free data service video]</a> <font color="red">Note that we demostrate free data service attack through a Skype conference call.
    The IP traffic produced by other non-Skype applications running in background is still charged by carriers.</font>  	
        <!--<video width="780" controls><source src="myfiles/free-data-service.mp4" type="video/mp4"></video>-->
      <br>
      <b>Demo 2:</b><a href="{{site.baseurl}}assets/images/projects/mute_voice_attack.mp4">[Voice muted attack video]</a> 
        	          
  	</div>
  </li>    
	<li><b>Media report</b> </li>
  		<a href="http://www.theverge.com/2015/10/22/9594128/volte-vulnerability-attack-verizon-att-tmobile">
  			<img src="{{site.baseurl}}assets/images/projects/volte-news.png" width="750" />
  		</a>
	</ul>
	

	
 

  </ul>
</div>