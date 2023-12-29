# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory

## Procedure:
1.Create a New Project: Open Quartus and create a new project by selecting "File" > "New Project Wizard." Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).

2.Create a New Design File: *Once the project is created, right-click on the project name in the Project Navigator and select "Add New File." *Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.

3.Write the Combinational Logic Code: *Open the newly created Verilog or VHDL file and write the code for your combinational logic.

4.Compile the Project:

*To compile the project, click on "Processing" > "Start Compilation" in the menu. *Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.

5.Analyze and Fix Errors:

*If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window.

*Review and fix any issues in your code if necessary. *View the RTL diagram.

6.Verification:

*Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".

*Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All.

*Give the Input Combinations according to the Truth Table and then simulate the Output Waveform

## Program:

Developed by: K Vijay

RegisterNumber: 23004034

### Code:

![image](https://github.com/vijaygowdu/Experiment--02-Implementation-of-combinational-logic-/assets/147473788/5ef64b49-b34b-4938-b108-d5b7420fd6d7)

## Output:
## Truthtable:

![image](https://github.com/vijaygowdu/Experiment--02-Implementation-of-combinational-logic-/assets/147473788/bac55c27-0705-4df3-912e-9be605e3b704)

## RTL:

![image](https://github.com/vijaygowdu/Experiment--02-Implementation-of-combinational-logic-/assets/147473788/f00467d1-7a16-4a6b-a06e-a9051f753fd1)

## Timing Diagram:

![image](https://github.com/vijaygowdu/Experiment--02-Implementation-of-combinational-logic-/assets/147473788/545670a0-f8a8-4be0-894a-00ba0d60c321)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
