---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
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

## Research
<br>

<div class="row mb-1" markdown="0">
  <div class="col-md-12">
    <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
      <div class="col p-4 d-flex flex-column position-static">
        <h4 class="mb-0">Cellular IoT</h4>
            <!-- <div class="mb-1" style="color:gray; margin-left:2px"><p>NeTS: Small: Exploring the Design, Implementation, Operation Issues of Cellular IoT via Formal Analysis and Empirical Validation</p>
            </div> -->
            <br>
            <p class="card-text mb-auto">As an emerging technology, the Cellular Internet-of-Things (CIoT) interconnects Things via the global cellular network. Compared to the Low-power Wide Area Network technology such as LoRA and SigFOX that is limited to unlicensed spectrum, CIoT leverages wide licensed spectrum to accommodate diversified IoT demands, ranging from wearables, car connected devices to smart meter and building automation, at a reasonable cost ($5-$15). Given such advantages, it is forecasted that the number of CIoT devices will reach 1.5 billion in 2021, representing a staggering four-fold growth from 0.4 billion in 2015. Considering the significant number of CIoT devices to be deployed in the near future, any design defects of CIoT standards, implementation issues and operational slips of CIoT devices and operational infrastructure could lead to devastating consequences at a global scale. Moreover, the goals of this project are to (1) use formal methods to study and identify the critical design defects of CIoT standards, and (2) systematically examine interrelated implementation issues and operational slips of CIoT practice.</p>
            <div style="text-align:right">
            <p><a href="/research/cellular-iot" class="stretched-link">Read more</a></p>
          </div>
      </div>
    </div>
  </div>
</div>


<div class="row mb-1" markdown="0">
  <div class="col-md-12">
    <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
      <div class="col p-4 d-flex flex-column position-static">
        <h4 class="mb-0">Mobile service security</h4>
            <br>
            <p class="card-text mb-auto">In this work, we explore security issues of the operational Wi-Fi calling services in three major U.S. operators’ networks using commodity devices. We disclose that current Wi-Fi calling security is not bullet-proof. We uncover four vulnerabilities which stem from improper standard designs, device implementation issues and network operation slips. By exploiting them, we devise two proof-of-concept attacks: user privacy leakage and telephony harassment or denial of voice service (THDoS); they can bypass the security defenses deployed on both mobile devices and network infrastructure. We have confirmed their feasibility and simplicity using real-world experiments, as well as assessed their potential damages and proposed recommended solutions.</p>
            <div style="text-align:right">
            <p><a href="/research/mobile-service-security" class="stretched-link">Read more</a></p>
          </div>
      </div>
    </div>
  </div>
</div>


<div class="row mb-1" markdown="0">
  <div class="col-md-12">
    <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
      <div class="col p-4 d-flex flex-column position-static">
        <h4 class="mb-0">Mobile Data Charging Security</h4>
            <br>
            <p class="card-text mb-auto">The accounting of data usage is the most important functionality in the management plane of cellular network. However, we find that the control-plane and management-plane functions of cellular network are not well designed from either charging accuracy or security aspect.</p>
            <div style="text-align:right">
            <p><a href="/research/mobile-data-charging-security" class="stretched-link">Read more</a></p>
          </div>
      </div>
    </div>
  </div>
</div>

<div class="row mb-1" markdown="0">
  <div class="col-md-12">
    <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
      <div class="col p-4 d-flex flex-column position-static">
        <h4 class="mb-0">Formal Analysis</h4>
            <br>
            <p class="card-text mb-auto">We develop <i>CNetVerifier</i>, an automated control-plane protocol interaction verification method with domain-specific heuristics and model checking techniques to systematically explore possible problematic interactions in cellular networks. The main advantage of this methodology is the exploration of problems/issues in mobile networks is not restricted by unlimited use scenarios (time consuming) or the lack of full access to mobile device or network infrastructure. Its impact on the wireless/mobile networking technology and cybersecurity can be considered as far-reaching. It does not only capture the fundamental design issues of mobile networks span over multiple dimensions, but also discover the security loopholes> caused by improper designs of control-plane protocols of mobile networks. The lessons we learnt can be even applied to the next big things (e.g., 5G, Internet of Thing, Device-to-Device communication) in the networking area.</p>
            <div style="text-align:right">
            <p><a href="/research/formal-analysis" class="stretched-link">Read more</a></p>
          </div>
      </div>
    </div>
  </div>
</div>


<div class="row mb-1" markdown="0">
  <div class="col-md-12">
    <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
      <div class="col p-4 d-flex flex-column position-static">
        <h4 class="mb-0">IoT/SmartHome security</h4>
            <br>
            <p class="card-text mb-auto">Home Digital Voice Assistants (HDVAs) are getting popular in recent years. Users can control smart devices and get living assistance through those HDVAs (e.g., Amazon Alexa, Google Home) using voice. In this work, we study the insecurity of HDVA services by using Amazon Alexa and Google Home as case studies. We disclose three security vulnerabilities which root in their insecure access control. We then exploit them to devise two proof-of-concept attacks, home burglary and fake order, where the adversary can remotely command the victim’s HDVA device to open a door or place an order from Amazon.com or Google Express. The insecure access control is that HDVA devices not only rely on a single-factor authentication but also take voice commands even if no people are around them. We thus argue that HDVAs should have another authentication factor, a physical presence based access control; that is, they can accept voice commands only when any person is detected nearby. To this end, we devise a Virtual Security Button (VSButton), which everages the WiFi technology to detect indoor human motions. Once any indoor human motion is detected, the HDVA device is enabled to accept voice commands. Our evaluation results show that it can effectively differentiate indoor motions from the cases of no motion and outdoor motions in both laboratory and real world settings.</p>
            <div style="text-align:right">
            <p><a href="/research/iot-smarthome-security" class="stretched-link">Read more</a></p>
          </div>
      </div>
    </div>
  </div>
</div>


<div class="row mb-1" markdown="0">
  <div class="col-md-12">
    <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
      <div class="col p-4 d-flex flex-column position-static">
        <h4 class="mb-0">Blockchain security</h4>
            <!-- <br>
            <p class="card-text mb-auto">asd </p>
            <div style="text-align:right">
            <p><a href="/projects/privacy-dynamics" class="stretched-link">Read more</a></p> 
            </div>-->
      </div>
    </div>
  </div>
</div>