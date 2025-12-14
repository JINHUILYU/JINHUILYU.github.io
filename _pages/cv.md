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
 
Work Experience
======
* September 2025 – December
  * MOMENTA. OBF R&D Intern
  * Key Responsibilities:
    1. Participated in the development, integration, testing, and OTA updates of domain-controlled ECU underlying systems (BSP/MCU/SWITCH);
    2. Independently developed large-model-based automation tools to enhance requirements management, technical support, and team collaboration efficiency.
  * Duties includes:
    * Contributed to OBF-BSP project development, responsible for bench equipment assembly, development, integration, testing, and OTA upgrades covering domain control ECU components including MCU, SWITCH, and BSP. Assisted in identifying and resolving system upgrade issues.
    * Built large-model-based tools for requirement optimization and automated reviews. Successfully standardized OBF-BSP & MCU requirement descriptions per ASPICE and ISO 26262 standards, significantly improving documentation quality and consistency.
    * Developed OBF-GPT bots and related MCP tools using the Momenta BotForge framework. Embedded these into Feishu desktop and web clients via Feishu bot interfaces to enable intelligent Q&A for private databases and automated root cause analysis of user issues, substantially boosting technical support efficiency.
    * Participated in Momenta's Xiaoyangshan, Beiganshan, Tianmashan, and Hallasan projects, identifying and resolving intermittent disconnection issues between Qualcomm 8650 and Momenta BMC X7 domain control ECUs. Continuously provided OTA upgrade solutions, completing end-to-end updates and validation for MCUs, switches, and BSPs, significantly enhancing system stability and remote maintenance efficiency.
    * Developed a FO request tracking tool based on Momenta BotForge, enabling real-time monitoring of FO information for relevant projects. Automatically generates multi-dimensional summary reports daily at 8:00 AM and precisely pushes them to designated group chats, facilitating collaboration among R&D, testing, and delivery teams.
    * Developed AR-GPT—an automation bot for OBF department's CI/CD/CT compilation, version release, RMP deployment, RCT testing, PR merging, and RCT report generation/analysis—using Momenta BotForge and Feishu's robot framework. Managed ongoing maintenance and continuous OTA upgrades.
    * Developed a log visualization and analysis system using Rich and Textual, enabling interactive filtering, searching, and highlighting of large-scale Loguru JSON log files. Continuously optimized system performance and user experience.
    * Developed the reference design QA bot RD-GPT for external suppliers using Dify and Feishu Bot.

* June 2025 - September 2025: ZXISOS-653
  * ZTE Corporation. Operating System Product Department \[Intern\]
  * Key Responsibilities:
    1. Participate in module development and testing for the high-safety-level ZXISOS-653 airborne operating system, and complete requirements reviews;
    2. Establish the requirements process for DO-178C Level A software standards;
    3. Independently develop a large-model-based intelligent toolchain to empower requirements analysis and review processes.
  * Duties includes:
    * Participated in the R&D of ZTE's ZXISOS-653 avionics operating system, assisting in refining software architecture design documents, software requirements documents, and error correction tasks.
    * Based on ARINC-653 standards, participated in designing and implementing the task lifecycle management module and partition communication mechanisms within the partitioned operating system. Assisted in locating and resolving kernel/partitioned OS-related issues, designed and implemented requirement-based unit test cases, and supported system testing and troubleshooting.
    * Established activity paths for low-level requirements based on DO-178C Level A software development standards, and developed a comprehensive low-level requirements writing plan.
    * Referenced existing system requirements documentation to draft and review corresponding high-level and low-level requirements documents. Established traceability relationships between high-level and low-level requirements, organized and updated software requirements documentation, and advanced airworthiness certification processes (Requirements Review RR, Preliminary Design Review PDR).
    * Develop intelligent automation tools based on the Nebula large language model:
      1. Source code/PDL code-to-requirement description module: Generate corresponding natural language requirement descriptions from existing project code.
      2. Intelligent requirement review module: Input requirement documents and checklists to output structured review results.


Project Experience
======
* July 2024 - now: Aviation demand analysis and development of auxiliary tools
  * Aerospace Software Trusted Development Technology Laboratory
  * Key Responsibilities:
    1. Support aviation units in system requirements analysis, review, and quality assurance;
    2. Independently develop intelligent requirements support tools based on large models and RAG (Retrieval-Augmented Generation) to enhance requirements quality, analysis efficiency, and accuracy.
  * Duties includes:
    * Participate in architecture design and core functionality implementation to build a highly available, scalable requirements analysis toolchain, improving analysis efficiency and accuracy.
    * Assisted aviation entities including COMAC and AVIC in completing system requirement analysis and reviews, ensuring accuracy and completeness. Conducted requirement analysis and decomposition, organized airworthiness requirement reviews (engineering/phase) under the DO-178C framework, established traceability and checklist systems, proactively closed review issues, and generated audit-ready evidence. Conducted in-depth analysis of project requirement rationality and consistency, promptly identified and raised conflicts or inconsistencies, and proposed corresponding modification recommendations.
    * Independently developed an intelligent question-answering service using Python + FastAPI, integrating large language model APIs to build a Retrieval-Augmented Generation (RAG) workflow for document semantic search and response generation. Designed and implemented a document knowledge base using MySQL for structured, persistent storage of document content. Leveraged word embedding technology to vectorize textual knowledge, storing it in Redis to enable efficient semantic similarity-based retrieval and cache acceleration.

* April 2025 - May 2025: Intelligent document Q&A system: [LLM-powered DocQA](https://github.com/JINHUILYU/Intelligent-document-QA-system)
  * Aerospace Software Trusted Development Technology Laboratory 
  * Duties includes:
    * Independently develop an intelligent question-answering service based on Python + FastAPI, integrate the API of large language models, construct the Retrieval Enhancement Generation (RAG) process, and achieve document semantic retrieval and answer generation.
    * Design and implement the document knowledge base, manage the document content using MySQL, and achieve structured persistent storage.
    * By using word embedding technology to vectorize knowledge and store it in Redis, efficient retrieval and cache acceleration based on semantic similarity can be achieved.

* November 2024 - December 2024: General large model dialogue software: [Chat-Bot](https://github.com/JINHUILYU/chat-framework)
  * Aerospace Software Trusted Development Technology Laboratory 
  * Duties includes:
    * Independently completed the system architecture design and functional implementation based on Python + PyQt.
    * Realize a role dialogue system based on prompt engineering, supporting dynamic switching of multiple roles and context memory.
    * Design pipeline strategies and arbitration mechanisms to achieve multi-prompt integrated dialogues.

* December 2024 - now: [Blog_OS](https://github.com/JINHUILYU/blog_os)
  * Personal Project
  * A minimal operating system kernel using Rust.

* February 2024 - March 2024: Quadcopter Flight Control System Based on FlyLite OS
  * Aerospace Software Trusted Development Technology Laboratory 
  * Duties includes:
    * Be responsible for the transplantation and optimization of electrical harmonics and USB drivers to enhance system stability.

* July 2023 - July 2024: Airborne high-safety runtime environment FlyLite OS
  * Aerospace Software Trusted Development Technology Laboratory 
  * Key Responsibilities:
    1. Participate in the module design and implementation of FlyLite OS, China's first DO-178C Level A low-cost airworthiness operating system;
    2. Lead system requirements, unit testing, and high-coverage verification to support airworthiness compliance.
  * Duties includes:
    * Contributed to China's first low-cost airworthiness runtime environment meeting DO-178C Level A software development requirements, developed in compliance with FACE and POSIX standards. Based on the μC/OS-II kernel, completed kernel enhancements and component development, assisted in designing and implementing the thread lifecycle management module, including core APIs for thread creation, information querying, and modification.
    * Participated in system requirement writing and reviews, designed and implemented unit test cases, assisted in overall system testing and issue troubleshooting. Responsible for requirement analysis and test documentation preparation for the thread library, libc library, and libm library, ensuring module functionality conformed to design specifications. Implemented the Shell interaction module, integrating Bash command execution testing and system status monitoring capabilities.
    * Within the DO-178C framework, managed requirements to code implementation, test case design, and coverage analysis. Led preparation for all SOI phases and airworthiness internal audits, drove PR/CR closure and configuration consistency, participated in establishing and implementing the airworthiness system and checklists/processes, ensuring timely approval and delivery of versions. Established a bidirectional traceability platform using Jira linking requirements, design, code, test cases, and results, enabling end-to-end traceability and auditability.
    * Implemented foundational mathematical library functions and verified numerical stability. Participated in requirement clarification and end-to-end bidirectional traceability. Wrote and executed comprehensive test cases. Completed system coverage testing using the TestGrid platform, encompassing statement coverage, branch coverage, decision coverage, and MC/DC coverage.
    * Participated in preparing and building evidence for reviews throughout the software airworthiness lifecycle (SOI-1 to SOI-4), established configuration baselines and consistency controls (SCI, PR/CR management), Execute tool qualification activities per DO-330 (TQL assessment, verification plans, and archiving), and refine the airworthiness documentation system (PSAC, SDP, SVP, SCMP templates and metrics) to enable evidence reuse and efficient review passage.

   
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
  * Go
  * Rust
* Professional ability
  * Familiar with C/C++, Go, Python, DO-178C, DO-333, ARINC-653, and have a basic understanding of Rust.
  * Familiar with the μC/OS-II, xv6, Linux 0.11, and common RTOS/embedded system architectures.
  * Possess experience in requirements analysis and formal methods practice (natural language → LTL transformation, model checking), as well as in the development and deployment of deep learning models.

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
