---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Click [here](/files/CV.pdf) for PDF version

Education
======
* B.Tech (Honors) Electrical Engineering, Indian Institute of Technology Madras, 2024 (expected)

Research Experience
======
* Radar Synchronization - Summer@EPFL
(Guide: [Dr. Haitham Hassanieh](https://people.epfl.ch/haitham.alhassanieh?lang=en), SENS Lab, School of Computer and Communication Sciences, EPFL)
The [Sensing and Networking Systems (SENS)](https://www.epfl.ch/labs/sens/) lab focuses on wireless imaging for autonomous vehicles, wireless networking, and next-generation wireless networks. I worked on the time and frequency synchronization of radars.
  * Built a custom circuit to generate a hardware trigger for time synchronization
  * Synchronizing multiple AWR2243 radars to achieve coherent processing and enable a larger virtual array
  * Modified PCB design of AWR2243 single-chip radar to include connectors required for finer frequency synchronization

* Spectrum Sensing
(Guide: [Dr. David Koilpillai](https://www.ee.iitm.ac.in/~koilpillai/), Dept. of Electrical Engineering, IIT Madras)
Spectrum Sensing is my Bachelor's Thesis project. This project focuses on sensing the spectrum as fast as possible with the most cost-effective equipment. I am implementing [SweepSense](https://www.usenix.org/conference/nsdi19/presentation/guddeti), which uses sweeping capture and calibration to sense the spectrum. I am exploring further alternatives to energy-based detection like Cyclostationarity and Kurtosis. I am also examining [SparSDR](https://wcsng.ucsd.edu/sparsdr/) to utilize the reduced backhaul for implementing a mobile spectrum scanner on a drone.
  * Implemented traditional band hopping spectrum sensing using energy-based detection on a USRP B210
  * Periodically ramping the Local Oscillator’s center frequency to scan the spectrum at a high rate
  * Scanning the spectrum with variable bandwidth in order to gain more insights on regions with more activity

* Automatic RF Circuit Synthesis
(Guide: [Dr. Sankaran Aniruddhan](https://www.ee.iitm.ac.in/ani/), Dept. of Electrical Engineering, IIT Madras)
Designing schematics of RF circuits is a slow iterative process involving non-idealities and parasitics. Automation of circuit design allows an IC designer to move directly to the layout section of the design workflow. In this project, I worked on simulation and automating the optimization of Capacitor Cross-Coupled CG LNA in the TSMC 65nm process. My work resulted in a 6 GHz LNA with >25 dB Gain and 2.5 dB Noise Figure.
  * Automated RF circuit design process which significantly reduces the design time of RF front-ends like LNAs, Mixers
  * Used Gradient Descent Algorithm to achieve the minimum of a custom loss function based on specifications
  * Optimized the design of Capacitor Cross Coupled CG LNA in TSMC 65nm process using Cadence Virtuoso

Professional Experience
======
* Embedded Software Developer - Curneu MedTech Pvt Ltd
[Curneu](https://www.curneu.com/) is a healthcare technology firm focused on building affordable and innovative healthcare solutions that address clinical needs. My work made it possible to integrate hardware & software aspects and to produce the first batch of neurosurgeon training machines.
  * Responsible for an accurate real-life training system for neurosurgeons performing brain aneurysm operations
  * Developed code for firmware update and shifting firmware from USART to USB OTG FS communication protocol
  * Tested and debugged my code with actual hardware interfaced with software and documented the results

* Low Voltage Subsystem Engineer - Raftar Formula Racing
[Raftar Formula Racing](https://cfi.iitm.ac.in/competition-teams/raftar-formula-racing) is the Formula Student team of IIT Madras. Its vision is to build an electric car from scratch. I was responsible for designing the shutdown and safety circuits for the proper performance of the electric car. I contributed to various design decisions for designing PCBs and developing 3D harness for the electric car. We competed as a team of fifty students and were winners of the Best Powertrain Award and the Overall winners in Formula Bharat'21.
  * Created the Brake System Plausibility Device PCB as part of the shutdown circuit for detecting faulty brake pedal
  * Designed the HV check PCB to check if the voltage in the battery pack has exceeded 60V to indicate HV status
  * Developed the entire car 2D harness which involved interconnections across multiple system modules
  * Analyzed placement of various components so that routing is efficient, cost-effective and follows clearance rules
  * Routed wires through anchored conduits for protection, added redundancy wiring for robust failure management

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!---
Relevant Courses
======
* EE6110: Adaptive Signal Processing
* EE4140: Digital Communication Systems
* EE6133: Multirate Digital Signal Processing
* EE5141: Introduction to Wireless and Cellular Communication
* EE5150: Communication Systems
* EE3110: Probability Foundations for Electrical Engineers
* EE2004: Digital Signal Processing
* EE6320: RF Integrated Circuits
* EE5320: Analog IC Design
* EE3002: Analog Circuits
* EE2003: Computer Organization
* EE3004: Control Systems
* EE2016: Microprocessor Theory and Lab

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
--->

  
Service and Leadership
======
* Saathi Mentor - IIT Madras
A Saathi Mentor helps freshmen settle into the college’s new environment and provides a smooth onboarding experience. They continue to mentor freshmen and advise them on academic matters till they become sophomores. I was a Saathi Mentor and mentored six students each in my sophomore and junior years. I helped my mentees with the challenging courses in their freshman year, solved their doubts, and gave advice on co-curricular activities.
  
* Acad Buddy Mentor - IIT Madras
An Acad Buddy mentor helps both freshmen and sophomores who are academically distressed. They mentor the students throughout the year and assist them in their courses. I mentored three students each in my sophomore and junior years.
