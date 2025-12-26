---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---

## ⫶☰ Table of Contents

------------------------------- 
Click on any of the following project titles to be directed to its description:
- [Personal Projects](#personal-projects-)
  - [SystemVerilog IP Core Library](#systemverilog-ip-core-library)
  - [MIPS R10k Style Out-of-Order Processor](#mips-r10k-style-out-of-order-processor)
  - [RISC-V 5-Stage Pipeline Processor](#risc-v-5-stage-pipeline-processor)
  - [$80 Computer Initiative](#80-computer-initiative)
  - [RoboChef](#robochef)
- [College Projects](https://ycpoon.github.io/collegeprojects/)
  - Full List of College Projects: [https://ycpoon.github.io/collegeprojects/](https://ycpoon.github.io/collegeprojects/)
- [Archived Projects](#archived-past-projects-️)
  - [Socius](#socius)
  - [Autonomous Quadcopter](#autonomous-quadcopter)
  - [Saunea 3000](#saunea-3000)

## Personal Projects ✅

------------------------------- 

### SystemVerilog IP Core Library
- A project aimed to redesign various common IP cores in SystemVerilog for additional features and/or latency & performance improvements
- IP cores reworked including High Latency Asynchronous FIFO, AXI4-Stream Interconnect, Efficient Priority Selector, Integer Square Root, Four Function Calculator modules.
- Access the full library here: [https://ycpoon.github.io/iplib/](https://ycpoon.github.io/iplib/)

&nbsp;
&nbsp;

### MIPS R10k Style Out-of-Order Processor
- Designed and synthesized a 32-bit MIPS R10K Style Out of Order Processor that supports the RV32I subset of RISC-V ISA in SystemVerilog
- Implemented various advanced features including N-way Superscalar Width, Early Tag Broadcasting, Early Branch Resolution, Tournament Branch Predictor, Load/Store Queue for Load-Store Forwarding, Non-Blocking Caches, Victim Caches, Banked Cache, Prefetcher Logic and others.
- Averaged a CPI of ~1.4 on general assembly programs, achieved a clock period of 7.8ns
-	Developed a comprehensive SystemVerilog Assertion (SVA) suite for verification of internal data structures and cache subsystems
- Final Project Repo: [470 GitHub Repo](https://github.com/ycpoon/MIPS_R10K_RISCV_Processor)
- Final Project Report: [470 Project Report](/files/470finalreport.pdf)

|  ![arch](/images/470diagram.png){: width="400px"} |  ![syn](/images/470synthesis.png){: width="300px"}  |  ![ana](/images/470analysis.png){: width="400px"}  |
|:-----------------------:|:-----------------------:|:-----------------------:|
| ***Processor Architecture*** | ***Synthesized RTL Design*** | ***Processor Analysis*** |

&nbsp;
&nbsp;

### RISC-V 5 Stage Pipeline Processor
- A project to build a simple 5-stage in-order pipelined processor that supports the RV32I subset of RISC-V ISA
- This project incorporates structural, control, data hazard management as well as data forwarding capabilities for optimal in-order CPI
- The processor is designed and built in SystemVerilog, synthesizable with Synopsis Design Compiler
- Full documentation and code provided in GitHub: [https://github.com/ycpoon/RISCV_5_Stage_Pipelined_Processor](https://github.com/ycpoon/RISCV_5_Stage_Pipelined_Processor)

| ![5-stage](/images/five_stage.png){: width="500px"} |
|:-----------------------:|
| ***Five Stage Pipeline Processor*** |

&nbsp;
&nbsp;

### $80 Computer Initiative
- A project to build cheap computers under the cost of $80 as an initiative to provide underpriviledge children access to computers
- How did we built it?
> 1. We first purchased and used [Raspberry Pi 4 Model B](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/) as the computer's main CPU.
> 2. We later bought second-hand monitors, microphones, keyboards, mouse, and speakers to integrate it with the Raspberry Pi computer.
> 3. To make the computer compatible with daily-use applications, we installed [Chromium](https://www.chromium.org/chromium-projects/), which is a free open-source OS available on the internet, to the computer.
> 4. Packaging all of it together, we have a fully functional $80 computer that is capable of running basic applications such as Word, Excel, and even access the internet.
- Amount of Computers Built and Donated: 4
- We hope that through this initiative, we can contribute towards combating the computer iliteracy issue among underpriveledged children in our country, Malaysia

|  ![comp](/images/80comp.jpg){: width="500px"} |  ![CPU](/images/cpu.jpeg){: width="500px"}|
|:-----------------------:|:-----------------------:|
| ***Final Completed Product*** | ***$80 computer "CPU"*** |


&nbsp;
&nbsp;

### RoboChef
- A web application that receives an image (as an URL) of any food, then identifies the food and its ingredient, and finally compile a list of recipes that shares the same ingredients as the food in the image given
- Benefits of the Application: Identify any image and provide recipes instantly, provide multiple recipe options, help students decide meals easily, fast & easy
- *Front-End* - HTML, Javascript, CSS ; *APIs* - [Clarifai](https://www.clarifai.com/), [Edamam](https://www.edamam.com/)
- GitHub Repo: [RoboChef](https://github.com/ycpoon/RoboChef)

|  ![R1](/images/robochef1.png){: width="500px"} |  ![R2](/images/robochef2.png){: width="500px"}|  ![R3](/images/robochef3.png){: width="200px"}  |
|:-----------------------:|:-----------------------:|:-----------------------:|
| ***Image URL input prompt*** | ***Recipe Output*** | ***ML Predictions*** |  

&nbsp;
&nbsp;


## Archived Past Projects ☑️

-------------------------------

### Socius
- A mobile application aimed to increase work & study motivation amidst the pandemic through tracking and gamifying the work & study process
- Features of the Application: Work/Study Tracker & Timer, Leaderboard and Gamified Work/Study Tracker to motivate good competition among friends, Courses Listings to expand knowledge
- *Tech Stack* - XML, Gradle
- Achievements: Malaysian Student Technology Week 2021 Hackathon - Top 6 Finalist
- GitHub Repo: [Socius](https://github.com/ycpoon/Socius)

|  ![S1](/images/socius1.png){: width="300px"} |  ![S2](/images/socius2.png){: width="300px"}|  ![S3](/images/socius3.png){: width="300px"}  |
|:-----------------------:|:-----------------------:|:-----------------------:|
| ***Login & Home Page*** | ***Timer Tracker & Leaderboard*** | ***Course Listings*** |  

&nbsp;
&nbsp;

### Autonomous Quadcopter
- To build a functional and controllable quadcopter programmed with Rasberry Pi
- To integrate a Rasberry Pi camera module for image capturing
- To implement an object detection model and a path-finding model from NVIDIA TAO Toolkit
- Current Progress: Tech Stack Identified & Parts Purchased

| ![drone](/images/drone.jpg){: width="500px"} |
|:-----------------------:|
| ***Quadcopter Parts*** |

&nbsp;
&nbsp;

### Saunea 3000
- A device that collects outer sound energy and convert sound energy to usable electrical energy.
- The aim of the project is to make a device that can harvest energy from noise pollution and convert it to electrical energy, opening up the possibility of using sound energy as a source of clean energy.
- Developed the model of the device using fundamentals of piezoelectricity to create electrical charge under mechanical stress.
- Achievements: Kuala Lumpur Engineering Science Fair (KLESF) Finalist among 100+ groups
- Reports Published: [Physics Report](/files/physics-project.pdf)
