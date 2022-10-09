---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV here](http://rppgao.github.io/files/CV.pdf)

Education
======
* M.S. in School of Electronic Science and Engineering, Nanjing University, 2020-2023
	* GPA: 3.59/4    Rank: 5%
	
* B.S. in School of Electrical and Automation Engineering, Nanjing Normal University, 2016-2020
	* GPA: 3.57/4    Rank: 4%, 4/95
	
Work experience
======
Intern Analog Design Engineer, Nanjing Huanxuan Semiconductor Co., LTD, 03/2020-Present
* Take charge of analog integrated circuit design; master software, such as Cadence.
* Cooperate with senior engineer; Do some jobs in Chip wire bonding and packaging.
* Take charge in whole part of HX6158 and some important circuit in HX8864.

Research experience
======
* 12 Bit SAR ADC Design, Project Leader, 08/2022-Present 
	* Complete the design of a 12 bit high precision SAR ADC with internal integrated clock (PLL). 
	* Design the overall structure of the unit, including the design of bandgap reference module, SAR ADC module and PLL module.
	* Design digital methods to reduce offset; avoid misjudgment and reduce offset through the design of CDAC and digital signals.

* 1-2048x Programmable Gain Amplifier PGA, Project Leader, 05/2022-08/2022 
	* Complete the design of 1-2048x programmable gain amplifier PGA with DC offset cancellation (DCOC). 
	* Design the overall structure of the unit, including fully differential operational amplifier, feedback loop and designing the digital DC offset elimination method.

* 64 Sweep PWM Constant-current LED Drive Control Chip with Built-in SRAM HX8864, directed by Li Li, 05/2021-08/2022
	* Content: 
	HX8864 is a LED high-density full color screen dedicated driver chip, which supports 1 to 64 sweep 16 channel PWM constant-current output.
	The project adopts the technology of SMIC 55nm (taped out) and GF 130nm (taped out), and has completed engineering batch testing and mass production.
	* Responsibilities:
	Designed and verified the bandgap reference module with offset cancellation, LDO module, BIAS module, gain regulator module and buffer module.
	By digital selection and trimming, realized the flexible adjustment of the gain adjustment module to the output current; designed a dynamic DAC structure to accurately replicate the current.

* Small Spacing 8-channel Adjustable Serial Shadow Elimination Voltage LED Display Driver Control Chip HX6158H, directed by Li Li, 07/2020-04/2021
	* Content: 
	HX6158H is a single-chip high-current with output 8-channel serial LED display driver chip. 
	The project adopts TowerJazz 180nm technology (taped out), and has completed engineering batch testing and mass production.
	* Responsibilities:
	Designed and verified the bandgap reference module, logic control module and driver module.
	Integrate the functions of charge discharge, voltage regulation and over-voltage protection, inside the drive module.
	Eliminated the shadow phenomenon of scan screen by adjustable voltage.
	Improved the caterpillar phenomenon caused by LED leakage and short circuit.

* Irradiation-resistant Satellite Internet Interface Chip, directed by Li Li, 03-06/2020
	* Content: 
	A chip which is applied in image sensor interface circuit system for satellite laser communication.
	The project adopts SOI 130nm 180nm technology (taped out), and has completed engineering batch testing and mass production. 
	* Responsibilities:
	Designed and verified the simulation of LDO module; the module included level conversion, power-on self-start, and high and low voltage protection functions.

Skills
======
* Proficient in Cadence analog circuit design, simulation, layout and verification; AMS digital-analog mixed register verification; 
* Mentor layout design verification; Linux system operation and configuration; Verilog.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Awards
======
* First Class Scholarship for Graduate Students, NJU
* Certificate of Completion Tanner Analog & Mixed-Signal IC Design, Chinese Academy of Sciences
* Second Prize of Jiangsu Province, National Undergraduate Electronics Design Contest
* First Prize of Outstanding Student Scholarship, 4 times, NNU
* Second Prize in Electronic Design Competition, 2 times, NNU
* Second Prize of Outstanding Student Scholarship, NNU
* Scholarship of Nari Group, 2 times, NNU & Nari Group
* Advanced Individual Award, College Students' Summer Social Practice, 2 times, NNU
* Second Prize, Mechanical Drawing Contest, 2 times, NNU

  
Service and leadership
======
* Monitor of Class 4, Graduate Student, School of Electronic Science and Engineering, Nanjing University
* Monitor of Class 7, Undergraduate Counselor Assistant, School of Electrical and Automation Engineering, Nanjing Normal University