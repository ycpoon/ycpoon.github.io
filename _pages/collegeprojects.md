---
layout: archive
title: "College Projects"
permalink: /collegeprojects/
author_profile: true
redirect_from:
  - /collegeprojects
---
<a id="top"></a>
<a href="#top" class="back-to-top">⬆️</a>

## Table of Contents ⫶☰

------------------------------- 
Click on any of the following project titles to be directed to its description:
- [MIPS R10K Style Out-of-Order Processor (EECS 470)](#mips-r10k-style-out-of-order-processor-eecs-470)
- [Attention Unit for Resource-Constrained Architectures (EECS 570)](#attention-unit-for-resource-constrained-architectures-eecs-570)
- [SpecNN: Hardware Accelerator for kNN (EECS 573)](#specnn-hardware-accelerator-for-knn-eecs-573)
- [Four Function Calculator, Traffic Light Controller, UpDown Counter (EECS 270)](#four-function-calculator-traffic-light-controller-updown-counter-eecs-270)
- [Low-Power/High-Speed Dual-Mode (Add/Accumulate) Adder Transistor-level Circuit Design (EECS 312)](#low-powerhigh-speed-dual-mode-addaccumulate-adder-transistor-level-circuit-design-eecs-312)
- [LC2K ISA Assembler & Linker, 5-Stage Pipelined Processor Simulator, Cache Simulator (EECS 370)](#lc2k-isa-assembler--linker-5-stage-pipelined-processor-simulator-cache-simulator-eecs-370)
- [CUDA kernel for custom PyTorch operator (EECS471)](#cuda-kernel-for-custom-pytorch-operator-eecs471)
- [Simple SQL Database, Words Morphing Algorithm, Optimal Route Finding Algorithm (EECS 281)](#simple-sql-database-words-morphing-algorithm-optimal-route-finding-algorithm-eecs-281)
- [RLC Circuits, Op-Amp Circuits (EECS 215)](#rlc-circuits-op-amp-circuits-eecs-215)
- [Euchre Card Game, Post Classifier Program, Seam-Carving Algorithm (EECS 280)](#euchre-card-game-post-classifier-program-seam-carving-algorithm-eecs-280)
- [Custom Bash Shell, Pig-Latin Translation Program, Customized Python Library (EECS 201)](#custom-bash-shell-pig-latin-translation-program-customized-python-library-eecs-201)

## College Projects

-------------------------------

### MIPS R10K Style Out-of-Order Processor (EECS 470)
* Designed a 32-bit MIPS R10K Style Out of Order Processor that supports the RV32I subset of RISC-V ISA.
* Implemented various advanced features including N-way Superscalar Width, Early Tag Broadcasting, Early Branch Resolution, Tournament Branch Predictor, Load/Store Queue for Load-Store Forwarding, Non-Blocking Caches, Victim Caches, Banked Cache, Prefetcher Logic and others.
* Averaged a CPI of ~1.4 on general assembly programs, achieved a clock period of 7.8ns.
*	Developed a comprehensive SystemVerilog Assertion (SVA) suite for verification of internal data structures and cache subsystems.
* Final Project Repo: [470 GitHub Repo](https://github.com/ycpoon/MIPS_R10K_RISCV_Processor)
* Final Project Report: [470 Project Report](/files/470finalreport.pdf)

| ***Processor Architecture*** | ***Synthesized RTL Design*** | ***Processor Analysis*** |
|:-----------------------:|:-----------------------:|:-----------------------:|
|  ![arch](/images/470diagram.png){: width="400px"} |  ![syn](/images/470synthesis.png){: width="300px"}  |  ![ana](/images/470analysis.png){: width="400px"}  |

&nbsp;
&nbsp;

### Attention Unit for Resource-Constrained Architectures (EECS 570)
* Designed a low power ASIC accelerator for the Flash Attention kernel used in modern ML transformers.
* Implemented the baseline [FLASH-D](https://arxiv.org/abs/2505.14201) architecture in SystemVerilog.
* Redesigned the [Fused ExpMul](https://arxiv.org/abs/2505.14314) architecture for fixed point 8-pit operations.
* Integrated the FLASH-D and Fused ExpMul architecture for our final Flash Attention accelerator architecture.
*	Developed a comprehensive suite of testbenches and C++ models for verification and PPA benchmarking.
* Final Project Repo: [570 GitHub Repo](https://github.com/dwvshep/A.U.R.A.---FlashAttention-ASIC-Accelerator)
* Final Project Report: [570 Project Report](/files/570report.pdf)

| ***Architecture and Result Poster*** |
|:-----------------------:|
|  ![570arch](/images/570poster.jpg){: width="600px"} |

&nbsp;
&nbsp;

### SpecNN: Hardware Accelerator for kNN (EECS 573)
* Architected a hardware accelerator for k Nearest Neighbour Search, a key primitive operation in 3D geometry-based algorithms used in autonomous driving, robotics, VR, and even ML/AI.
* Implemented the baseline bit-serial kNN search architecture from the [BitNN](https://ieeexplore.ieee.org/document/10609723) paper in SystemVerilog.
* Designed a previous kNN cache (taking advantage of query spatial locality) and a running mean threshold logic (taking advantage of sparsity consistency).
* Reduced termination warmup time for the BitNN architecture, increased overall speedup by ~10% for KITTI, SLAM datasets.
*	Wrote a cycle-accurate Python simulator modelling the architecture for performance and functional verification.
* Final Project Repo: [573 GitHub Repo](https://github.com/EECS-573-KNN-Accelerator/eecs573project)
* Final Project Report: [573 Project Report](/files/573report.pdf)

| ***Architecture Diagram*** | ***SpeedUp vs Accuracy Frontier Analysis*** |
|:-----------------------:|:-----------------------:|
|  ![573arch](/images/SpecNN.png){: width="400px"} | ![573analysis](/images/573analysis.png){: width="400px"} |

&nbsp;
&nbsp;

### Four Function Calculator, Traffic Light Controller, UpDown Counter (EECS 270)
* Developed a Four Function Calculator RTL Design on Altera DE2-115 FPGA (implemented Booth Multiplier, Carry Lookahead Adder, Quotient Divisor)
* Designed a Sensor-Integrated Traffic Light Controller using Sequential Design and the Finite States Machine concepts
* Implemented an UpDown Counter using Sequential Design

| ***Altera FPGA*** | ***Traffic Light Controller FSM*** | ***Calculator Datapath*** |
|:-----------------------:|:-----------------------:|:-----------------------:|
|  ![FPGA](/images/FPGA.png){: width="350px"} |  ![FPGA](/images/FPGA2.png){: width="300px"} |  ![FPGA](/images/FPGA3.png){: width="350px"} |

&nbsp;
&nbsp;

### Low-Power/High-Speed Dual-Mode (Add/Accumulate) Adder Transistor-level Circuit Design (EECS 312)
* Implemented a transistor-level design of a High Speed 8-bit Ripple Carry Adder using Dual-Rail Dynamic Logic Variant Implementation with Cadence Virtuoso
* Engineered a transistor-level design of a Energy Efficient 8-bit Ripple Carry Adder using Pass Transistor Logic and Transmission Gate Logic Hybrid
* Developed transistor-level designs of Muxes, D Flip Flops, XOR gate, and Latches
* Floorplanned, Placed and Routed the dual-mode adder architecture design, achieving timing closure at 1.51Mhz and reducing area by 20%
* Reports Published: [312 Report](/files/312_report.pdf)

| ***Cadence Virtuoso*** | ***Schematic Drawing*** | ***Waveform Generated*** |
|:-----------------------:|:-----------------------:|:-----------------------:|
|  ![vir](/images/312_vir.png){: width="400px"} |  ![sch](/images/312_sch.PNG){: width="400px"}  |  ![wave](/images/312_wave.jpg){: width="400px"}  |

&nbsp;
&nbsp;

### LC2K ISA Assembler & Linker, 5-Stage Pipelined Processor Simulator, Cache Simulator (EECS 370)
* Wrote a assembler program for converting LC2K assembly code to machine code object files
* Wrote a linker program for linking object files and libraries to create executables for processors
* Wrote a cycle-accurate LC2K 5-Stage Pipelined Processor simulator in C with data forwarding 
* Wrote a write-back, write-allocate set-associative cache simulator in C with parameterizable cache, set size

| ***LC2K Asembler & Linker*** | ***5-Stage Pipelined Processor Architecture*** | ***Cache Simulator Program*** | 
|:-----------------------:|:-----------------------:|:-----------------------:|
|  ![asli](/images/370_2.png){: width="350px"} |  ![proc](/images/370_3.png){: width="450px"}   |  ![cache](/images/370_4.png){: width="250px"} |

&nbsp;
&nbsp;

### CUDA kernel for custom PyTorch operator (EECS471)
* Refactored CUDA kernel code for a custom PyTorch operator, optimizing the convolution layer for the CNN
* Utilized many CUDA optimization techniques including shared memory convolution, weight matrix in constant memory, and loop unrolling to take full advantage of the V100 GPU architecture 
* Reduced execution time of the convolution layer by ~500% (0.8s to 0.15s) for predicting 10000 images from the MNIST-Fashion dataset
* Profiled the kernel code execution speed using NVIDIA NSight Profiler
* Reports Published: [471 Report](/files/471report.pdf)

| ***CUDA Kernel Architecture Diagram*** | ***NVIDIA NSight Profiler*** |
|:-----------------------:|:-----------------------:|
|  ![471_arch](/images/471_1.png){: width="400px"} | ![471_profiler](/images/471_2.png){: width="400px"} |

&nbsp;
&nbsp;

### Simple SQL Database, Words Morphing Algorithm, Optimal Route Finding Algorithm (EECS 281)
  * Developed a Letterman Words Morphing Algorithm using Stacks and Queues
  * Designed a Minemap Escape Optimal Route Finding Algorithm using Priority Queues
  * Implemented a simple SQL database using Hashmaps and Ordered Maps

| ***SQL Implementation*** | ***Mine Escape Route Finder Program*** | ***Letterman Morphing Program*** | 
|:-----------------------:|:-----------------------:|:-----------------------:|
|  ![sql](/images/sql.png){: width="400px"} |  ![ME](/images/mineescape.png){: width="350px"}   |  ![letter](/images/letterman.png){: width="450px"} |

&nbsp;
&nbsp;

### RLC Circuits, Op-Amp Circuits (EECS 215)
  * Used Waveform Generator to Measure Voltage 
  * Built RLC Circuits & Op-Amps Circuits on breadboards
  * Hands-on experience with powering Audio Transmitter with Rheostat

| ***Circuits & Waveform Generator*** 👇 | 
|  ![circuits](/images/cir1.jpg){: width="250px"} |  ![circuits](/images/cir2.jpg){: width="250px"}  |  ![circuits](/images/cir3.jpg){: width="250px"}  |

&nbsp;
&nbsp;

### Euchre Card Game, Post Classifier Program, Seam-Carving Algorithm (EECS 280)
  * Developed Euchre Card Game Program with in-built AI Opponent
  * Designed a Posts Classifier Machine Learning Program that takes in training data and predicts post classifications
  * Implemented a Seam-Carving Algorithm for images

| ***Euchre Game with AI*** | ***Machine Learning Post Classifier*** | ***Image Resizer Program*** | 
|:-----------------------:|:-----------------------:|:-----------------------:|
|  ![Euch](/images/euchre.png){: width="350px"} |  ![ML](/images/ml.png){: width="400px"}   |  ![CV](/images/cv.png){: width="450px"} |

&nbsp;
&nbsp;

### Custom Bash Shell, Pig-Latin Translation Program, Customized Python Library (EECS 201)
  * Built and customized my own bash shell
  * Engineered a Pig-Latin Translation Program
  * Created my own python library

| ***Customized Shell*** | ***Customized Shell Functions*** | ***Pig-Latinfy Program*** | 
|:-----------------------:|:-----------------------:|:-----------------------:|
|  ![2011](/images/2012.PNG){: width="450px"} |  ![2012](/images/2011.PNG){: width="375px"}   |  ![2013](/images/2013.png){: width="375px"}   |

&nbsp;
&nbsp;