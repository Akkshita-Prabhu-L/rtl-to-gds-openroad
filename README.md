# RTL to GDS Flow using OpenROAD

## 📌 Overview
This project explores the complete RTL-to-GDSII ASIC design flow using open-source tools. The objective was to understand how a high-level hardware description is transformed into a physically implementable chip design.

## ⚙️ Design Description
- Designed a simple **ALU module in Verilog**
- Used as input for synthesis and physical design flow

## 🔄 ASIC Design Flow Explored
1. RTL Design (Verilog)
2. Logic Synthesis (Yosys)
3. Floorplanning
4. Placement
5. Clock Tree Synthesis (CTS)
6. Routing
7. Static Timing Analysis

## 📊 Key Observations
- RTL is converted into a **gate-level netlist** during synthesis  
- Placement determines **cell locations** affecting timing and congestion  
- Routing connects components while optimizing delays  
- Timing reports highlight **critical paths and slack values**  
- Trade-offs between **Power, Performance, and Area (PPA)** are crucial  

## 🛠️ Tools Used
- Yosys (Synthesis)
- OpenROAD (Physical Design)
- GTKWave (Waveform Analysis)


## 🧠 Key Learnings
- Understanding of end-to-end ASIC design flow  
- Importance of timing closure in digital circuits  
- Exposure to physical design stages like placement and routing  
- Basics of analyzing timing reports and slack  

## ⚠️ Note
This project focuses on **exploration and understanding** of ASIC design flow using open-source tools, rather than full-scale chip implementation.
