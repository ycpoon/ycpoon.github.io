---
layout: archive
title: "IP Library"
permalink: /iplib/
author_profile: true
redirect_from:
  - /iplib
---

&nbsp;

**Simple UVM Framework on ALU**
- An attempt to learn UVM frameworks
- View Design on EDA Playground: [https://www.edaplayground.com/x/JY_y](https://www.edaplayground.com/x/JY_y)

&nbsp;

**RISC-V 5 Stage Pipelined Processor**
- An in-order 5 stage pipeline that supports a RV32I subset of RISC-V instructions
- Supports hazard management and data forwarding for optimal CPI
- Visual debugger written in C for CPU debugging and verification
- Full documentation and code provided in GitHub: [https://github.com/ycpoon/RISCV_5_Stage_Pipelined_Processor](https://github.com/ycpoon/RISCV_5_Stage_Pipelined_Processor)

&nbsp;

**Asynchronous & Synchronous FIFO Design**
- FIFO design with various additional features, ie. parameterizable read/write size, additional FIFO flags, datacount tracking
- Clock Domain Crossing with Two Flop Synchronizer and Gray/Binary Code Conversion for Asynchronous FIFO
- Full documentation and code provided in GitHub: [https://github.com/ycpoon/FIFO_Asynchronous_Synchronous](https://github.com/ycpoon/FIFO_Asynchronous_Synchronous)
- View Design on EDA Playground: [https://www.edaplayground.com/x/FrxZ](https://www.edaplayground.com/x/FrxZ)

&nbsp;

**Multi-Grant Round Robin Arbiter**
- A parameterizable multi-grant round robin arbitration logic block designed to provide grant access efficiently in round robin manner.
- This IP block uses FSM to achieve round-robin effect, implementing efficient MSB priority selector logic coupled with rotation logic to generate different arbitration scheme at every cycle.
- Full documentation and code provided in GitHub: [https://github.com/ycpoon/Multi_Grant_Round_Robin_Arbiter](https://github.com/ycpoon/Multi_Grant_Round_Robin_Arbiter)

&nbsp;

**AXI4-Stream Interconnect FIFO**
- AXI4-Stream Interconnect FIFO IP manages traffic on AXI4-Stream interfaces where it allows multiple AXI masters connect to multiple AXI slaves
- This IP also implements a MSB-LSB alternating priority selector for its arbitration logic when multiple masters are writing into one slave.
- Each slave has one FIFO buffer with backpressuring logic which slave port read from and master write to.
- Full documentation and code provided in GitHub: [https://github.com/ycpoon/AXI4-Stream_Interconnect_FIFO](https://github.com/ycpoon/AXI4-Stream_Interconnect_FIFO)
- View Design on EDA Playground: [https://www.edaplayground.com/x/DkCF](https://www.edaplayground.com/x/DkCF)

&nbsp;

**Full-Duplex Ethernet MAC Core**
- A naive implementation of a configurable Ethernet Media Access Control (MAC) core, designed in SystemVerilog for FPGA/ASIC implementation.
- This MAC Core primarily handles the transmission of data between the host processor and the Ethernet network (including separate TX and RX FIFOs for backpressuring, CRC generation/checker, and RGMII interfacing to PHY).
- It supports full-duplex mode over three speed modes: 10/100/1000 Mbps
- Work In Progress: Configuration and Statistics Counter Registers for error tracking, MDIO management
- Full documentation and code provided in GitHub: [https://github.com/ycpoon/Ethernet_MAC_Core](https://github.com/ycpoon/Ethernet_MAC_Core)

&nbsp;

**Highly Efficient Parameterizable Priority Selector IP**
- An efficient multi-grant priority selector with parametrizable width and request grants
- Three different prioritization scheme: MSB-LSB alternating scheme, MSB prioritization, LSB prioritization
- Full documentation and code provided in GitHub: [https://github.com/ycpoon/Efficient_Priority_Selector](https://github.com/ycpoon/Efficient_Priority_Selector)
- View Design on EDA Playground: [https://www.edaplayground.com/x/RFmL](https://www.edaplayground.com/x/RFmL)

&nbsp;

**Integer Square Root & Multiplication IP**
- 64-bit integer square root (ISR) IP that uses the pipelined multpication IP 
- Comprehensive testing framework completed on ISR module and Pipelined Multiplication Module
- Full documentation and code provided in GitHub: [https://github.com/ycpoon/Integer_Square_Root_w_Pipelined_Mult](https://github.com/ycpoon/Integer_Square_Root_w_Pipelined_Mult)
- View Design on EDA Playground: [https://www.edaplayground.com/x/WVQt](https://www.edaplayground.com/x/WVQt)

&nbsp;

**Arithmetic Four Function Calculator**
- Sequential Four Function Calculator (Add, Sub, Multiply, Divde) that efficiently utilizes FSM, Ripple Carry Adder, Booth Multiplier Algorithm, Quotient Divider
- Full comprehensive testing framework implemented for the calculator
- Full documentation and code provided in GitHub: [https://github.com/ycpoon/Seq_Arithmetic_Calculator](https://github.com/ycpoon/Seq_Arithmetic_Calculator)
- View Design on EDA Playground: [https://www.edaplayground.com/x/EyBY](https://www.edaplayground.com/x/EyBY)

&nbsp;

**Reduced Latency Memory BIST Design**
- An efficient March C variant algorithm for MBIST testing, with full coverage in SAF, SOF, TF, AF, and inter-word CF
- View Design on EDA Playground: [https://www.edaplayground.com/x/Fr6S](https://www.edaplayground.com/x/Fr6S)

&nbsp;

**Improved BRAM Wrapper Design**
- Scalable Read and Write BRAM Wrapper with backpressuring logic
- View Design on EDA Playground: [https://www.edaplayground.com/x/YFYf](https://www.edaplayground.com/x/YFYf)

&nbsp;


