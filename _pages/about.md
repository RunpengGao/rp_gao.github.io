---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I have got my master degree in Electronic Engineering from Nanjing University. I have designed several analog integrated circuits, for Bandgap\LDO\Driver etc., building the tools of [Cadence virtuoso], Mentor Calibre, which are efficient tools for circuits and layout design. I am also familiar with Synopsys Verilog, thus I am able to do some digital VLSI circuits.

My research area is LED Drivers with a variety of features for both outdoor and indoor LED displays. My master project is ["Research and development of CMOS Micro-LED driver chip"](National key research and development plan project) in which I proposed a framework about high performance LED driver which yields satisfactory performances. [More than 10 Chinese National Invention Patents and one American Patents] (LED DISPLAY DRIVER CHIP AND USE THEREOF), and I am now working for an IEEE paper in October (Current Control LED Driver Based On DS-PWM Algorithm). Outstanding academic records are also obtained in my studies, ranking [top 5%] out of 300 students and won many academic awards.


Education
======
M.S., 2020 - 2023, School of Electronic Science and Engineering, Nanjing University, Nanjing, China

B.S., 2016 - 2020, School of Electrical and Automation Engineering, Nanjing Normal University, Nanjing, China


Publications
======
Papers:
1. Gao, Runpeng & Liu, John. (2019). Hearing loss identification by wavelet entropy and cat swarm optimization. AIP Conference Proceedings. 2073. 020082. 10.1063/1.5090736. 

Patents:
1. Mini-LED driving method and display system. CN113851080A. 2021. [link](https://globaldossier.uspto.gov/#/result/publication/CN/113851080/1)
2. Mini-LED backlight driving control chip and system supporting breakpoint resume. CN113838414A. 2021. [link](https://globaldossier.uspto.gov/#/result/publication/CN/113838414/1)
3. LED driving current modulation method and system and application. CN113554980A. 2021. [link](https://globaldossier.uspto.gov/#/result/publication/CN/113554980/1)
4. Shadow elimination voltage level control method, display method, system and display device. CN113314072A. 2021. [link](https://globaldossier.uspto.gov/#/result/publication/CN/113314072/1)
5. Clock duty ratio trimming method and system. CN113162586A. 2021. [link](https://globaldossier.uspto.gov/#/result/publication/CN/113162586/1)
6. Clock duty ratio calibration method and system. CN113014229A. 2021. [link](https://globaldossier.uspto.gov/#/result/publication/CN/113014229/1)
7. Driving method and device of display element. CN112908244A. 2021. [link](https://globaldossier.uspto.gov/#/result/publication/CN/112908244/1)
8. LED driving method, LED driving circuit and display screen. CN112735326A. 2021. [link](https://globaldossier.uspto.gov/#/result/publication/CN/112735326/1)
9. Active clamping circuit. CN111831045A. 2020. [link](https://globaldossier.uspto.gov/#/result/publication/CN/111831045/1)
10. LED display screen row driving chip driving method and chip. CN111724727A. 2021. [link](https://globaldossier.uspto.gov/#/result/publication/CN/111724727/1)


Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
