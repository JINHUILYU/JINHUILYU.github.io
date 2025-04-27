---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Software Engineering, East China Normal University, 2026 (expected)
  * Aerospace Software Trusted Development Technology Laboratory 
  * Supervisor: Professor Yong Cai
  * Research directions: Requirements formalization & Requirements review
* B.S. in Electronic Information Engineering, Jiangsu University, 2022
  * Supervisor: Professor Leijun Xu

Project Experience
======
* July 2024 - now: Aviation demand analysis and development of auxiliary tools
  * Aerospace Software Trusted Development Technology Laboratory
  * Duties includes:
    * Participate in architecture design and core function realization, build a highly available and scalable demand analysis toolchain, and improve the efficiency and accuracy of demand analysis.
    * Assist aviation units such as COMAC and AVIC in completing system requirement analysis and review to ensure the accuracy and completeness of the requirements.
    * Conduct an in-depth analysis of the rationality and consistency of the project requirements, promptly identify and point out the conflicts and unreasonable aspects of the requirements, and put forward corresponding modification suggestions. Discover more than 50 errors in the project requirements of aviation units such as the 615 Research Institute of AVIC and Hanzhong 101 Aviation Electronic Equipment Co., LTD.

* November 2024 - December 2024: General large model dialogue software: [Chat-Bot](https://github.com/JINHUILYU/chat-framework)
  * Aerospace Software Trusted Development Technology Laboratory 
  * Duties includes:
    * Independently completed the system architecture design and functional implementation based on Python + PyQt.
    * Realize a role dialogue system based on prompt engineering, supporting dynamic switching of multiple roles and context memory.
    * Design pipeline strategies and arbitration mechanisms to achieve multi-prompt integrated dialogues.

* February 2024 - March 2024: Quadcopter Flight Control System Based on FlyLite OS
  * Aerospace Software Trusted Development Technology Laboratory 
  * Duties includes:
    * Be responsible for the transplantation and optimization of electrical harmonics and USB drivers to enhance system stability.

* July 2023 - July 2023: Airborne high-safety operating environment FlyLite OS
  * Aerospace Software Trusted Development Technology Laboratory 
  * Duties includes:
    * Participated in the research and development of the first domestic low-cost airworthiness runtime environment that meets the requirements of DO-178C A-level software development.
    * Assist in designing and implementing the thread full lifecycle management module, including core apis such as thread creation, information query and modification.
    * Participated in the requirement writing and review of FlyLite OS, designed and implemented unit test cases, and assisted in the overall system testing and problem troubleshooting.
    * Be responsible for the requirement analysis and test documentation of the thread library, libc library and libm library to ensure that the module functions comply with the design specifications.
    * Realize some functions of the Shell interaction module, integrate Bash command running tests and system status monitoring functions.
    * The system coverage test was completed based on the TestGrid platform, covering statement coverage, branch coverage, decision coverage and MC/DC coverage.
   
* February 2022 - May 2022: Rice Disease Identification Acceleration System Based on FPGA: [FPGA Acceleration System](https://github.com/LyuJinhui/Rice)
  * Laboratory 212, School of Electrical and Information Engineering
  * Duties includes:
    * Complete the benchmark test of object detection based on YOLOv3 to evaluate the performance of the model on FPGA hardware.
    * Optimize the anchor frame size and aspect ratio of the SSD algorithm to increase the detection accuracy by 40%.
    * The MobileNet v1 recognition network was fully implemented. Data preprocessing, model training and verification were completed, and the accuracy rate increased from 30% to 70%.
    * The convolution operator acceleration algorithm was designed to optimize the computational parallelism and data flow, and the SSD recognition rate was increased by 100% compared to YOLOv3.
  
Skills
======
* Programing
  * C/C++
  * Python
  * Rust
* Professional ability
  * Proficient in C/C++, Python and Rust (ownership).
  * Familiar with the μC/ OS-II core and RTOS/ embedded system architecture.
  * Understand MySQL indexes, transactions and their isolation levels, as well as common performance optimizations under MySQL.
  * Have practical experience in requirement analysis and formal methods (natural language → LTL transformation, model checking) as well as in the development and deployment of deep learning models.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
