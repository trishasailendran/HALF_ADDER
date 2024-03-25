# HALF_ADDER
# Aim
To simulate and synthesis Half adder using Xilinx ISE.

# Software required
Xilinx 14.7 Spartan6 FPGA

# Procedure
STEP:1
Start the Xilinx navigator, Select and Name the New project.

STEP:2
Select the device family, device, package and speed.

STEP:3
Select new source in the New Project and select Verilog Module as the Source type.

STEP:4
Type the File Name and Click Next and then finish button. Type the code and save it.

STEP:5
Select the Behavioral Simulation in the Source Window and click the check syntax.

STEP:6
Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7
Select the Implementation in the Sources Window and select the required file in the Processes Window.

STEP:8
Select Check Syntax from the Synthesize XST Process. Double Click in the Floorplan Area/IO/Logic-Post Synthesis process in the User Constraints process group. UCF(User constraint File) is obtained.

STEP:9
In the Design Object List Window, enter the pin location for each pin in the Loc column Select save from the File menu.

STEP:10
Double click on the Implement Design and double click on the Generate Programming File to create a bitstream of the design.(.v) file is converted into .bit file here.

STEP:11
Load the Bit file into the SPARTAN 6 FPGA

STEP:12
On the board, by giving required input, the LEDs starts to glow light, indicating the output.
# Program
```
Developed By :TRISHA S
Register Number:212222060280
```
```
module half_adder(a,b,sum,carry);
       input a,b;
       output sum,carry;
       xor g1(sum,a,b);
       and g2(carry,a,b);
endmodule
```
# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/fe672c28-5c6a-4355-b70f-b40bce63880d)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/5f1a79a7-73c2-4b99-a40d-afa2a20c74ac)
# Sum = A XOR B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/020e1531-1c11-42e5-9f27-f09ba459984d)
# Carry = A AND B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/988ae131-0822-4d23-941b-eaafad349a72)
# Output
![image](https://github.com/trishasailendran/HALF_ADDER/assets/87655678/4b6935a9-5d93-495e-b8a6-bdb247ee8626)
# Result
Hence, the stimulation and synthesis of a half adder was run successfully by using Xilinx ISE.


