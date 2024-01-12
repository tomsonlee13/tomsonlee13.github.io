---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Access full CV here](/cv/Tomson_s_CV.pdf)

Education
======
* B.S. in Computer Engineering, Washington University in St. Louis, 2022
* M.S. in Cybersecurity Engineering, Washington University in St. Louis, 2023
* Ph.D in Computer Science, Washington University in St. Louis, Present

Work experience
======
* May 2022 - Present: Research Assistant
  * Washington University in St. Louis
  <!-- * Duties included: Tagging issues -->
  * Supervisor: Professor Ning Zhang

* July 2020 - Sept. 2020: Backend Development Intern
  * Youme.im
  * Developed an end-to-end encryption module for audio and video real-time communication
  * Integrated the encryption module into the cross-platform compilation build workflow
  * Performed testing to ensure functionalities (i.e., RTP retransmission) work after integrating the encryption module
  <!-- * Supervisor: Professor Hub -->

Projects
=====
* RichArduino V4
  * Designed and implemented $I^2C$ module and XADC wrapper for our FPGA-based microcontroller system
  * Implemented a RISC-based assembly bootloader for the microcontroller
  * Developed a Python GUI-based UART serial connection software for debugging and uploading program
  * Designed an RC circuit and soldered components on the PCB shield
  * Developed a simple assembly program to demonstrate the functionality of the microcontroller

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Technical Skills
======
* Languages: C/C++, Python, Java, JavaScript, HTML/CSS, VHDL, Assembly, SQL, PHP
* Frameworks: React, Node.js
* Developer Tools: Git, Cmake, Docker, VS Code, Visual Studio, Eclipse, Wireshark, Xcode, Ghidra
* Libraries: pandas, NumPy, Matplotlib, Tkinter
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
Awards
======
* Nominated for the 2022 Dean's Select PhD Fellowship at Washington University in St. Louis.
