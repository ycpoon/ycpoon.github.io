---
layout: archive
title: "Experiences"
permalink: /experiences/
author_profile: true
redirect_from:
  - /experiences
---
<a id="top"></a>
<a href="#top" class="back-to-top">Back to Top ⬆️</a>

## Table of Contents ⫶☰

------------------------------- 
Click on any of the job titles to be directed to its description:
- [Work Experiences](#work-experiences-)
  - [UMich CSE Dept - Digital Logic Design Teaching Assistant](#cse), *Aug 2024 to Dec 2025*
  - [Advanced Micro Devices (AMD) - Design Verification Intern](#amd), *May 2025 to Aug 2025*
  - [Efinix Inc. - Post Silicon Validation and DFT Engineering Intern](#efinix), *May 2024 to Aug 2024*
  - [UMich Solar Car Team - Microsystems and Firmware Engineer](#solar-car), *Aug 2023 to Aug 2024*
  - [Aerodyne Group -  Tech Research Intern](#aerodyne), *Jan 2023 - Mar 2023*
  - [Taylor's University - Calculus 1 and Physics 1 Teaching Assistant](#taylors-university), *Jan 2022 to Dec 2022*
- [Leadership Experiences](#leadership-experiences-)
  - [Michigan Hackers - Embedded Systems Team Lead at Michigan Hackers](#mhackers), *Aug 2024  to Aug 2025*
  - [Agents of Tech, Taylor's University - President](#aot), *Oct 2022 to Oct 2023*
  - [ICMS - National Executive Director (Malaysia)](#icms), *Sep 2022 to Sep 2023*
  - [YME - Director of Finance and Sponsorship](#yme), *Oct 2022 to Oct 2023*
  - [TUSC - Campus Welfare Committee Member](#tusc), *Nov 2021 to Sep 2022*
- [Professional Activities & Conferences Leadership](#professional-activities--conferences-leadership-)
  - [Malaysian Students’ Technology Week - Executive Coordinator](#mstw), *Oct 2022*
  - [Be Your Own Boss Entrepreneurship Event - Project Manager](#byob), *Aug 2021*
  - [Taylor's Lakeside MUN - Committee Affairs Associate](#tlmun), *Aug 2021*

## Work Experiences 💼

------------------------------- 

### <span style="display:none;">CSE</span>
**University of Michigan CSE Department**, Aug 2024 - Dec 2025   
*EECS 270: Logic Design Instructional Aide (Teaching Assistant)*
![UM_CSE](/images/cse.png){: .align-right width="250px"}
- Responsible in leading weekly lab sessions, guiding students on RTL design projects in the course, and grading students' designs.
- Supporting the development of the course's Autograder, mainly responsible for structuring test cases using UVM frameworks to verify students' digital designs more systematically and provide students with automated and accurate feedback on buggy designs.
- Wrote several bash scripts automating RTL design testing and grading for 200+ students. 
- ***Skills Associated:*** Teaching, Verilog, RTL Design, Bash

*References:*  
*Saquib Razak, Professor of CSE UMich, razak@umich.edu;  Karem Sakallah, Professor of CSE UMich, karem@umich.edu*

|  ![IA1](/images/IA.jpg){: width="400px"} |  ![IA2](/images/IA2.png){: width="400px"}|
|:-----------------------:|:-----------------------:|
| ***Hosting my Lab Section*** | ***Course Staff Introduction*** |

&nbsp;

### <span style="display:none;">AMD</span>
***Advanced Micro Devices (AMD)***,  May 2025 - Aug 2025  
*Silicon Design Engineering Intern - Design Verification*  
![AMD_logo](/images/amd-logo.png){: .align-right width="350px"} 
-	Contributed to the verification flow of a USB xHCI sub-block device reset verification test, including designing test plans based on coverage plan and design specifications, writing UVM test sequences with constrained random sequence items, developing SystemVerilog Assertion (SVA) checkers, debugging testcase failures, performing functional and code coverage analysis, verifying waveform behavior against specification through Verdi, and deploying testcase to regression. 
-	Assisted in refining UVM monitors by extracting protocol-layer data transaction packets, enabling more detailed debug printing.
-	Developed a Python script for parsing post-simulation UVM logs and generating an interactive GUI centralized tracker for USB transactions, comprising of transfers queued in system memory, AXI interfacing, DMA reads/writes, protocol-level packet exchanges, and more. 
- Refactored 1000+ lines of xHCI test sequence library by reorganizing general sequence classes to testcase-specific sequence classes and reconfiguring internal build scripts to support the new structure, improving test clarity and scalability for easier future debugging.

***Skills Associated:*** Design Verification, Universal Verification Methodology (UVM), Verdi, USB, Python, SystemVerilog

*References: Chi Chiet Woo, Senior Manager of Silicon Design Engineering, ChiChiet.Woo@amd.com*

|  ![AMD_first](/images/amd_first.jpeg){: width="350px"} |  ![AMD_last](/images/amd_last.jpeg){: width="350px"}|  ![AMD_proto](/images/fifo_org.drawio.png){: width="400px"}  | 
|:-----------------------:|:-----------------------:|:-----------------------:|
| ***First Day at AMD*** | ***Last Day with Mentors*** | ***Sample Prototype of Debug Tool Software Algorithm (Discarded)*** | 

&nbsp;

### <span style="display:none;">Efinix</span>
**Efinix Inc.**, May 2024 - Aug 2024  
*Post Silicon Validation & Design for Testability (DFT) Engineering Intern*  
![EF_logo](/images/efinix__logo.jpeg){: .align-right width="350px"} 
- Contributed to the development of the test program for Efinix's Ti375C529 Configurable PLL Duty Cycle Distortion (DCD) IP, involved in the full process including defining test methodologies, implementing RTL designs, running simulations on Cadence Xcelium and QuestaSim, simulation debugging, and VCD conversion to Advantest V39000 tester format.
- Researched and designed a low latency March C variant with 100% coverage in most fault models for Efinix’s Memory BIST design.
- Developed Python/Perl scripts automating GPIO assignments and coverage analysis, increasing efficiency of test runs by ~150%
- Gained hands-on experience in JTAG-based debugging, scan insertions, ATPG, & fault simulation using Synopsys TetraMax diagnostic tools
- Collaborated with Design Verification in the testing and verification of Efinix’s RISC-V Core and Triple Speed Ethernet MAC Core, assisted in refining UVM testbenches for Efinix’s EdgeVision image processing module and speed verification of Ethernet IP.

***Skills Associated:*** Post Silicon Validation, DFT, BIST, Python, Perl, SystemVerilog

*References: Nen Wei Ng, Engineering & Operations Director at Efinix Inc., nwng@efinixinc.com*

|  ![EF_self](/images/efinix_selfie.jpeg){: width="400px"} |  ![EF_proto](/images/efinix_prototyping.jpeg){: width="350px"}|  ![EF_team](/images/efinix_team.jpeg){: width="350px"}  | 
|:-----------------------:|:-----------------------:|:-----------------------:|
| ***Selfie at Efinix*** | ***FPGA EdgeVision Testing*** | ***Farewell Dinner with Team*** | 


&nbsp;

### <span style="display:none;">Solar Car</span>
**University of Michigan Solar Car Team**, Aug 2023 to Aug 2024  
*Microsystems and Firmware Engineer* 
![SC](/images/sclogo.png){: .align-right width="350px"} 
- Designed the schematics and layout for a PCB that controls the car’s headlights, stop lights, and turn signals with Altium.
- Led in redesigning the dashboard PCB to integrate Battery Management System (BMS) controls to the dashboard. 
- Assisted in the software and hardware integration of the car’s sensors with the GPIO pins of the main MCU.
- Analyzed and rewrote the firmware code for the car’s light and brake system to increase the response rate by ~120%
- Developed a RTOS-based firmware that handles interrupts and schedules tasks for the MCU based on specific priorities.  

***Skills Associated:*** Firmware, STM32Cube, C++, RTOS, Altium Designer, PCB Design

*References: Jeffrey Yang, UMSCT Microsystems Lead, yangje@umich.edu*

|  ![myself](/images/myself.JPG){: width="200px"} |  ![Altium](/images/altium.jpg){: width="200px"}|  ![Firmware](/images/firmware.jpg){: width="200px"}  | ![STM](/images/stm.jpg){: width="200px"} |
|:-----------------------:|:-----------------------:|:-----------------------:|:-----------------------:|
| ***Job Appointment*** | ***PCB Schematics*** | ***Firmware*** | ***STM32 Testing*** |

&nbsp;

### <span style="display:none;">Aerodyne</span>
**Aerodyne Group**, Jan 2023 to Mar 2023  
*Tech Research Intern*  
![Aero](/images/aerodyne.jpg){: .align-right width="320px"}  
- Contributed to securing a $5 million Unmanned Aircraft System (UAS) application development project.
- Worked with the project team on the prototype and pseudocode design of a UAS Traffic Management application.
- Assisted in designing the schematics and layout for a GPS and metrics tracker PCB to enable remote metrics tracking.
- Assisted in implementing infra-red, LiDAR sensors to drones by using Arduino and Embedded C programming.
- Performed research & analysis into emerging drone and chip technologies to fit clients’ needs. 

***Skills Associated:*** Tech Research, PCB Design, LiDAR, Embedded C, Software Prototyping

*References: Jamie Barker, Future Tech Research Analyst, jamie.barker@aerodyne.ai*
  
|  ![3D](/images/3dmodel.jpg){: width="300px"} |  ![Meeting](/images/meeting.jpeg){: width="300px"}|  ![Group](/images/group.jpg){: width="300px"}  |
|:-----------------------:|:-----------------------:|:-----------------------:|
| ***3D Modeling*** | ***Company Meeting*** | ***Company Photo*** | 

&nbsp;

### <span style="display:none;">Taylor's University</span>
**Taylor's University**, Jan 2022 to Dec 2022  
*Calculus 1 & Physics 1 Teaching Assistant*  
![Taylors](/images/taylors.png){: .align-right width="300px"} 
- Hosted tutoring sessions, discussion sessions, and office hours for 150+ students enrolled in Calculus 1 and Physics 1.
- Assisted professors in planning course contents/schedules, designing homework, and grading students’ works.   
- Implemented tailored academic support strategies resulting in the transformation of 8 students from initial ‘Fail’ grade to ‘A’.
- Certificates: [Calculus 1](/files/Cal1.pdf) and [Physics 1](/files/Physics1.pdf) 

***Skills Associated:*** Teaching, Maths, Physics

*References:*  
*Dr. Ng Eng Hui, Senior Lecturer I, enghui.ng@taylors.edu.my*  
*Dr. Yvonne Kong Yeo Lee, Senior Lecturer I, kong.yeolee@taylors.edu.my*  

| ![pass](/images/pass.jpg){: width="500px"} |
|:-----------------------:|
| ***Calculus Tutor Session*** |

&nbsp;
&nbsp;

## Leadership Experiences 🧑‍💼

-----------------------------

### <span style="display:none;">MHackers</span>
**Michigan Hackers**, Aug 2024 to Aug 2025  
*Embedded Systems Team Lead*  
![MHackers](/images/mhackers.jpg){: .align-right width="250px"} 
- Led a team of 20 in the development of a semester-based embedded systems project to be showcased to 200+ MHackers’ members.
- Reviewed and provided feedback for 50+ embedded systems project designs, ensuring quality standards and optimal functionality.
- Curated 15+ hack nights and 3 workshops tailored for MHackers’ members, fostering knowledge in embedded systems.
- Built a LED roulette game (LED lights up in random order and eventually stopping at one spot) and a [Remote Controlled Car](/files/RemoteCar.pdf) using Arduino 

*References: Anisha Aggarwal, MHackers President, anishaag@umich.edu*

|  ![Mhackers](/images/mhackers1.jpg){: width="300px"} |  ![Roul](/images/roulette.jpg){: width="300px"} |  ![Car](/images/mhackers2.jpg){: width="300px"}  |
|:-----------------------:|:-----------------------:|:-----------------------:|
| ***MHackers Demo Night*** | ***LED Roulette Game*** | ***Remote Controlled Car*** | 

&nbsp;

### <span style="display:none;">AOT</span>
**Agents of Tech**, Oct 2022 to Oct 2023  
*President*  
![TaylorsAOT](/images/aot.png){: .align-right width="250px"} 
- Led in curating tech workshops and training sessions on topics such as React and Arduino for over 200 like-minded club members.
- Hosted the biggest hackathon in college’s history with 200+ participants and cash prizes amounting to more than $7k.
- Secured sponsorships amounting to $25k from 7 different tech companies and partnerships with Intel, Google, and Samsung.
- Certificates: [Agents of Tech](/files/AoT.pdf), Appointment: [IG Post](https://www.instagram.com/p/ClbPMMUpJHh/?img_index=2)

*References: Gregory Sinnappan, Student Development, gregory.sinnappan@taylors.edu.my*

|  ![hack](/images/hackathon.jpeg){: width="300px"} |  ![Myself](/images/presenting.jpg){: width="300px"}|  ![Poster](/images/poster.jpeg){: width="300px"}  |
|:-----------------------:|:-----------------------:|:-----------------------:|
| ***Hackathon Hosted*** | ***Emcee Experience*** | ***Events Organized*** | 

&nbsp;

### <span style="display:none;">ICMS</span>
**International Council of Malaysian Scholars**, Sept 2022 to Sept 2023  
*National Executive Director - Malaysia*  
- Led a board of 15 directors and a chapter of approximately 60 associates to execute events, flagships, and workshops.
- Managed external stakeholder relations with local industry partners and sponsors such as Sunway, Axiata, and Maybank.

|  ![ICMS1](/images/icms1.png){: width="400px"} |  ![ICMS2](/images/allphoto.jpg){: width="400px"}|  ![ICMS3](/images/icmsp.jpg){: width="400px"}  |
|:-----------------------:|:-----------------------:|:-----------------------:|
| ***ICMS Committee Lineup*** | ***ICMS Team Photo*** | ***Chapter Director Presentation*** | 

&nbsp;

### <span style="display:none;">YME</span>
**Young Malaysian Engineers**, Oct 2021 to Oct 2022  
*Executive Coordinator and Director of Finance and Sponsorship*  
- Led in organizing the largest student-led technology conference in Malaysia - Malaysian Students' Technology Week 2022 (MSTW), involving 22 events, 32 professional speakers, 5 sponsors, and approximately $30K worth of budget.
- Generated $20K sponsorship fund for the club and event from companies such as Dyson, Shell, PwC
- Appointment: [Finance & Sponsorship Director](https://www.instagram.com/p/CXiv31qvmd3/) & [Executive Coordinator](https://www.instagram.com/p/CdxzezPvTQB/)

|  ![F&S](/images/F&S.jpg){: width="500px"} |  ![EC](/images/EC.jpg){: width="500px"}|
|:-----------------------:|:-----------------------:|
| ***Finance & Sponsorship*** | ***Executive Coordinator*** | 

&nbsp;

### <span style="display:none;">TUSC</span>
**Taylor's Unversity Student Council**, Nov 2021 to Sept 2022  
*Committee Member of Campus Welfare Department*  
- Compiled more than 100 feedback responses by students to be brought up to the school management. 
- Liaised with the school management to discuss on students’ feedbacks and complaints.
- Project Manager for Student Development August 2022 – Be Your Own Boss.
- Appointment: [IG Post](https://www.instagram.com/p/CZjfLAJvarZ/)

|  ![TUSC](/images/tusc.jpg){: width="300px"} |  ![CW](/images/CW.jpg){: width="450px"}|  ![Event](/images/physical.jpg){: width="450px"}  |
|:-----------------------:|:-----------------------:|:-----------------------:|
| ***TUSC Lineup*** | ***Team Photoshoot*** | ***Physical Event*** |

&nbsp;
&nbsp;


## Professional Activities & Conferences Leadership 👔

-----------------------------

### <span style="display:none;">MSTW</span>
**Malaysian Students' Technology Week**, Oct 2022  
*Executive Coordinator*  
- Lead role in organising the largest student-led technology conference in Malaysia.
- Led an organising committee of 50 members to prepare and execute the event that involved 32 professional speakers and more than 500 participants from UK and MY. 
- Secured $35k sponsorship fund from Gamuda, KidoCode, TalentCorp, and EcoWorld.

&nbsp;

### <span style="display:none;">BYOB</span>
**Taylor’s University Student Development Aug ’22 – Be Your Own Boss**, Aug 2021  
*Project Manager*
- Organised an event to equip undergraduates with fundamental knowledge of entrepreneurship.
- Invited 4 entrepreneurs who have won prestigious awards such as Forbes 30 under 30 and Entrepreneur of The Year as the guest speakers of the event.
- Received more than 130 registrations for the event.  

&nbsp;

### <span style="display:none;">TLMUN</span>
**Taylor's Lakeside Model United Nations 2022 International**, Aug 2021  
*Associate of Committee Affairs*
- Part of the organising committee of one of the largest MUN conference in Malaysia.
- In charge of the event logistics and people management of the event.
- Assist in handling 14 chairs and more than 200 delegates.






