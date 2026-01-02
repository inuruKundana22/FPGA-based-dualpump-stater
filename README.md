

## Problem Statement

In critical facilities, running multiple pumps at the same time may cause:

* Power overload
* Equipment damage
* Reduced system reliability

Hence, a robust control logic was required to manage pump operations safely.

## Project Objectives

* Prevent simultaneous operation of multiple pumps
* Implement first-start logic for safe pump activation
* Ensure reliable and deterministic control behavior
* Improve system safety and operational efficiency

## System Description

The system includes:

* Input signals from control switches and sensors
* FPGA-based control logic
* Output control signals to water pumps
* Status indication for pump operation

## Technologies & Tools Used

* **HDL:** Verilog
* **FPGA Tool:** Xilinx Vivado
* **Simulation:** Functional simulation using testbenches
* **Version Control:** Git & GitHub

## Implementation Details

* Designed interlock logic to allow only one pump to operate at a time
* Implemented first-start gating logic for safe system initialization
* Verified system behavior under normal and fault conditions using simulation
* Ensured reliable pump sequencing and balanced usage

## Results

* Successfully eliminated simultaneous pump operation
* Improved safety and reliability of pump control system
* Achieved correct pump sequencing and fault prevention

## Learning Outcomes

* Practical experience in **FPGA-based control system design**
* Strong understanding of **interlock and safety logic**
* Hands-on exposure to real-time industrial systems
* Experience working in a **mission-critical ISRO environment**

