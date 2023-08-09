---
title: Cellular IoT
layout: gridlay
sitemap: false
permalink: /research/cellular-iot
---

<style>
p {
    display: inline-block;
}
</style>

### NeTS: Small: Exploring the Design, Implementation, Operation Issues of Cellular IoT via Formal Analysis and Empirical Validation
---

<div class="container" markdown="0">
<a name="Goals" id="Goals"></a>
<h2>Project Goals</h2>
<p>
As an emerging technology, the Cellular Internet-of-Things (CIoT) interconnects Things via the global cellular network.
Compared to the Low-power Wide Area Network technology such as LoRA and SigFOX that is limited to unlicensed spectrum, CIoT leverages wide licensed spectrum to accommodate diversified IoT demands, ranging from wearables, car connected devices to smart meter and building automation, at a reasonable cost ($5-$15). Given such advantages, it is forecasted that the number of CIoT devices will reach 1.5 billion in 2021, representing a staggering four-fold growth from 0.4 billion in 2015. Considering the significant number of CIoT devices to be deployed in the near future, any design defects of CIoT standards, implementation issues and operational slips of CIoT devices and operational infrastructure could lead to devastating consequences at a global scale. Moreover, the goals of this project are to (1) use formal methods to study and identify the critical design defects of CIoT standards, and (2) systematically examine interrelated implementation issues and operational slips of CIoT practice.
</p>

<a name="Intellectual Merit" id="Intellectual Merit"></a>
<h2>Intellectual Merit</h2>
<p>
This project targets the following three technical contributions.
<ul>
  <li><b><em>Discovering Design Defects via Formal Analyses:</em></b> We will develop a formal CIoT control-plane protocol verification tool which discovers a variety of design defects, e.g., functional incorrectness, performance downgrade, or security issues, of CIoT standards.</li>
  <li><b><em>Exploring Implementation Issues and Operational Slips:</em></b> We will develop novel testing methodologies for exploring the implementation issues and operational slips of CIoT practice, which covers CIoT conformance testing standards, CIoT practice and SQA (Software Quality Assurance) experts's feedbacks.</li>
  <li><b><em>Develop an Open-source Cellular IoT Platform:</em></b> We will develop an open-source cellular IoT platform (openCIoT) supporting both of the device and infrastructure since some design defects, implementation issues and operational slips cannot be validated using commercial off-the-shelf CIoT devices and operational CIoT infrastructure, especially for abnormal usage testing or security issues. On top of openCIoT, researchers are projected to design, deploy and evaluate their innovative theory, algorithm, mechanisms or systems. The whole CIoT ecosystem will benefit from the research efforts.</li>
</ul>
</p>

<a name="Broader Impact" id="Broader Impact"></a>
<h2>Broader Impact</h2>
<p>
<ul>
  <li><b><em>Impact on Society:</em></b>The proposed project represents the first full investigation of cellular IoT services from its design, implementation and operation perspectives. The successful completion of this project will contribute to 1) new techniques to identify design defects, implementation issues and operational slips of CIoT services; 2) the release of a new open-source CIoT testbed to the research community; and 3) facilitating the deployment of CIoT services, boosting the CIoT economy in the U.S., as well as providing new insights for the upcoming 5G network.</li>
  
  <li><b><em>Broad Dissemination of Results:</em></b>We plan to use three main venues for disseminating our research results: 1) academic conferences, 2) software distribution, and 3) industrial collaboration. We believe that combining these three strategies will maximize the scientific and societal impact of our work. We will continue to publish the proposed research in top-tier conferences and distribute software by our project website. Moreover, we will collaborate with industrial partners to gain better insights into the practical issues in and speed up the adoption of our innovations in the industry. Over the years, we have established collaborative relationships with industry including the leading mobile device manufacturers including Samsung and LG, and cellular IoT network carriers including AT&T, Verizon, etc. We will continuously seek feedback from our industrial partners for this project.</li>
  
  <li><b><em>Undergraduate Mentoring and K-12 Outreach:</em></b> To attract undergraduate students to the wireless/mobile networking, formal verification and mobile system research, the PI/Co-PI will offer well-defined mini-projects related to this research to such students in the summer or during regular semesters through the undergraduate research programs (e.g., EnSURE). The goal is to motivate, prepare, and attract undergraduate students towards graduate research. They will leverage the existing resources and programs (Summer Institute for Superintendents or Annual Education Conference) of the MSU/K-12 outreach program to deliver innovative science education content to high-school students through teachers or principals. They expect to provide K-12 teachers and students with correct information and knowledge about the security vulnerabilities, threats, attacks and defenses, and enhance their interests in the STEM field.</li>
  
  <li><b><em>Recruiting/Advising Female and Minority Students:</em></b> Dr. Tu has advised an undergraduate student, Amanuel Goshu, who is the member of underrepresented minorities (African Americans) and interested in cybersecurity, for a year. With PI's encouragement, he is pursuing the admission to graduate programs in several top U.S. universities such as University of California, Berkeley and Princeton University. Dr. Zhang has had the privilege of mentoring six talented undergraduate students in the past three years, including one female student, one Hispanic American student, and one African American student. They joined the lab after taking Co-PI Zhang's sophomore class, and have been working with Co-PI Zhang on a variety of research projects. Dr. Tu has recruited a female Ph.D. students at MSU in Fall 2019. They will continue their active efforts in recruiting and mentoring female and under-represented talents for this project and inspire more such students to join the exciting technology space of wireless networking, mobile systems and formal verification.</li>

  <li><b><em>Impact on Undergraduate and Graduate Curricula:</em></b> Today's educational curriculum is inadequate in training new-generation engineers and researchers to take on the challenges of building and operating secure mobile network systems. PI/Co-PI plan to incorporate more up-to-date information on both research results and industry practice into undergraduate and graduate courses at MSU. Dr. Tu will continue to incorporate cutting-edge network security in undergraduate courses: Computer Networks and Introduction to Computer Security. Dr. Zhang will incorporate research results from this project into his course, Mobile Computing. Moreover, PI and Co-PI will also help mentor graduate students to be effective teachers by having the graduate students who perform this research participate in the preparation of these course modules to appropriate classes.</li>
</ul>
</p>

<a name="Activities" id="Activities"></a>
<h2>Activities</h2>
<ul>
  <li> <b>Year 1:</b>
	<ul>
		<li>Studied 3GPP cellular LTE-M/CAT-M1 IoT standards. Note that LTE-M/CAT-M1 IoT is supported by two major U.S. carriers: Verizon and AT&T, which together dominate U.S. IoT service market.</li>
		<li>Studied the existing open-source SDR-based cellular network platforms, e.g., OAI and srsLTE, and examine the feasibility of upgrading them to support LTE-M/CAT-M1 IoT devices.</li>
		<li>Designed and developed open-source cellular LTE-M/CAT-M1 IoT research platforms.</li>
		<li>Study the security vulnerabilities of current operational cellular IoT services.</li>
	</ul>
  </li>
  <li> <b>Year 2:</b>
	<ul>
		<li>Developed an SDR-based mobile device platform supporting IoT-specific features including Power Saving Mode and eDRX (Extended Discontinuous Reception) features to communicate with commercial cellular networks supporting IoT services.</li>
		<li>Explored the problematic design, implementation issues, and operational slips of current operational cellular IoT services and devices.</li>
	</ul>
  </li>
<li> <b>Year 3:</b>
	<ul>
		<li>Developed an SDR-based cellular network infrastructure platform supporting IoT-specific features including Power Saving Mode.</li>
		<li>Explored the problematic design, implementation issues, and operational slips of current operational cellular IoT services and devices.</li>
	</ul>
  </li>  
<li> <b>Year 4:</b>
	<ul>
		<li>Upgraded the SDR-based cellular network infrastructure platform to support multiple COTS NB-IoT devices.</li>
		<li>Explored the problematic design, implementation issues, and operational slips of current operational cellular IoT services and devices.</li>
	</ul>
  </li>    
</ul>  


<a name="Outputs" id="Outputs"></a>
<h2>Outputs</h2>
<ul>
  <li> <b>Year 1:</b>
	<ul>
		<li>Tian Xie, Guan-Hua Tu, Chi-Yu Li, Chunyi Peng, "How Can IoT Services Pose New Security Threats In Operational Cellular Networks?", Submitted to <b>IEEE Transaction on Mobile Computing</b>, 2020.</li>
		<li>Xiao Zeng, Ming Yan, and Mi Zhang. “Mercury: A Framework for Efficient On-Device Distributed Deep Learning”. Submitted to <b>Systems and Machine Learning Conference</b> 2020.</li>		
	</ul>
  </li>

  <li> <b>Year 2:</b>
		<ul>		
			<li>Tian Xie, Guan-Hua Tu, Chi-Yu Li, Chunyi Peng, <a href="http://www.cse.msu.edu/~ghtu/published-papers/CIoT-charging-security.pdf">"How Can IoT Services Pose New Security Threats In Operational Cellular Networks?"</a>, accepted by <b>IEEE Transaction on Mobile Computing</b>, 2020.</li>
			<li>Xinyu Lei, Guan-Hua Tu, Chi-Yu Li, Tian Xie and Mi Zhang, <a href="http://www.cse.msu.edu/~ghtu/published-papers/Lei-Mobisys20.pdf">"SecWIR: Securing Smart Home IoT Communications via Wi-Fi Routers with Embedded Intelligence"</a>, accepted by <b>ACM MobiSys'20</b>.</li>		
			<li>Biyi Fang, Xiao Zeng, Faen Zhang, Hui Xu, and Mi Zhang. "FlexDNN: Input-Adaptive On-Device Deep Learning for Efficient Mobile Vision", acceepted by <b>ACM/IEEE Symposium on Edge Computing (SEC'20)</b>.</li>
			<li>Shen Yan, Yu Zheng, Wei Ao, Xiao Zeng, Mi Zhang, "Does Unsupervised Architecture Representation Learning Help Neural Architecture Search?", <b>NeurIPS'20</b>. </li>
		</ul>
  </li>
    
  <li> <b>Year 3:</b>
	<ul>		
		<li>Sihan Wang, Guan-Hua Tu, Xinyu Lei, Tian Xie, Chi-Yu Li, Po-Yi Chou, Fucheng Hsieh, Yiwen Hu, Li Xiao, Chunyi Peng, "Insecurity of Operational Cellular IoT Service: New Vulnerabilities, Attacks, and Countermeasures", accepted by <b>ACM MobiCom'21</b></li>		
		<li>Shen Yan, Kaiqiang Song, Fei Liu, Mi Zhang, "CATE: Computation-aware Neural Architecture Encoding with Transformers", ICML'21. </li>
	</ul>
  </li>

   <li> <b>Year 4:</b>
	<ul>	
		<li> Yiwen Hu, Min-Yue Chen, Guan-Hua Tu, Chi-Yu Li, Sihan Wang, Jingwen Shi, Tian Xie, Xiao Li, Chunyi Peng, Zhaowei Tan, Songwu Lu, "Uncovering Insecure Designs of Cellular Emergency Services (911)," Accepted by <i>Proceedings of ACM the 28th Annual International Conference On Mobile Computing And Networking (MobiCom) 2022,</i></li>
		<li>Power-saving Sonica (PS-Sonica), an SDR-based open-source cellular IoT tested supporting essential power saving service features, based on Sonica developed by WiNG@UCLA. Link: <a href="SDR-NB-IoT-Testbed (Sonica-PowerSaving).zip">SDR-NB-IoT-Testbed (Sonica-PowerSaving).zip</a> </li>
	</ul>
  </li>   
  
</ul>  


<a name="Personnel" id="Personnel"></a>
<h2>Personnel</h2>
<ul>
  <li><a href="https://www.cse.msu.edu/~ghtu">Dr. Guan-Hua Tu (PI)</a></li>
  <li><a href="https://www.egr.msu.edu/~mizhang">Dr. Mi Zhang (Co-PI)</a></li>
  <li><a href="https://www.cse.msu.edu/~xietian1">Tian Xie</a> (Ph.D. student at MSU CSE)</li>
  <li><a href="http://www.cse.msu.edu/~wangsih3/">Sihan Wang</a> (Ph.D. student at MSU CSE)</li>
  <li>Wei Ao (Ph.D. student at MSU ECE)</li>
  <li>Marven Nadhum (Undergraduate student at MSU CSE)</li>
  <li>Jouse Kpodo (Undergraduate student at MSU CSE)</li>
  
</ul>
</div> 