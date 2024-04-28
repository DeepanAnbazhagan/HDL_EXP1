# HDL_EXP1
# Multiplexer4to1
# Aim
To simulate and synthesis Multiplexer 4 to 1 using Vivado software.
# Apparatus required
Vivado 2023.1 software.
# Procedure
STEP:1 Start the Xilinx navigator, Select and Name the New project. STEP:2 Select the device family, device, package and speed. STEP:3 Select new source in the New Project and select Verilog Module as the Source type. STEP:4 Type the File Name and Click Next and then finish button. Type the code and save it. STEP:5 Select the Behavioral Simulation in the Source Window and click the check syntax. STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table. STEP:7 Select the Implementation in the Sources Window and select the required file in the Processes Window. STEP:8 Select Check Syntax from the Synthesize XST Process. Double Click in the Floorplan Area/IO/Logic-Post Synthesis process in the User Constraints process group. UCF(User constraint File) is obtained. STEP:9 In the Design Object List Window, enter the pin location for each pin in the Loc column Select save from the File menu. STEP:10 Double click on the Implement Design and double click on the Generate Programming File to create a bitstream of the design.(.v) file is converted into .bit file here. STEP:12 Load the Bit file into the SPARTAN 6 FPGA STEP:11 On the board, by giving required input, the LEDs starts to glow light, indicating the output.
# Program
module mux(a,b,c,d,s0,s1,y);
input a,b,c,d,s0,s1;
output y;
assign y=s1 ?(s0?d:c):(s0?b:a);
endmodule
# Truth Table
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f1dac9e1-e938-4072-bfa9-c17a0a54b7c7)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f8ea8610-f6fc-4de3-a68a-5a9a4cfcd673)
# Output
![image](https://github.com/Akila56/Multiplexer4to1/assets/164776026/e05d66c6-0d21-48f2-8245-040d504bc66d)
# Result 
hence the simulation  and synthesis of Multiplexer 4 to 1 using Vivado software are verified.

# DEMULTIPLEXER1TO4
# Aim:
To simulate and synthesis DEMULTIPLEXER 1 TO 4 using Vivado software.
# Software Required:
Vivado 2023.1 software.
# Procedure 
STEP:1 Start the Xilinx navigator, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 Select the Implementation in the Sources Window and select the required file in the Processes Window.

STEP:8 Select Check Syntax from the Synthesize XST Process. Double Click in the Floorplan Area/IO/Logic-Post Synthesis process in the User Constraints process group. UCF(User constraint File) is obtained.

STEP:9 In the Design Object List Window, enter the pin location for each pin in the Loc column Select save from the File menu.

STEP:10 Double click on the Implement Design and double click on the Generate Programming File to create a bitstream of the design.(.v) file is converted into .bit file here.

STEP:11 Load the Bit file into the SPARTAN 6 FPGA

STEP:12 On the board, by giving required input, the LEDs starts to glow light, indicating the output.

![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/b6d81e6c-81ec-4f91-ae42-832a68f8facc)
# Truth Table
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/bb0a83c7-b4f3-463b-b422-f2ff65b1a0ee)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/dcd56444-97dd-454b-bddf-c7472c4af1de)
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/03fbbbdf-8ae3-4653-8047-7d4cbf555ccb)
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/f48cc07d-c76f-4d1c-8907-11e99711b751)
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/a3075cf9-55ba-4478-b20c-c7128badef04)
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/e07386db-69b3-4a5f-945f-b38929b801ea)
# Program
 
Developed by: Trisha S
Register number: 212222060280


module demux(y0,y1,y2,y3,s1,s0,I);
 input I,s0,s1;
 output y0,y1,y2,y3;
     assign s1n = ~ s1;
     assign s0n = ~ s0;
     assign y0 = I & s0n & s1n;
     assign y1 = I & s0 & s1n;
     assign y2 = I & s0n & s1;
     assign y3 = I & s0 & s1;
 endmodule

# Output
<img width="768" alt="318172064-5ae7b88b-d5e1-4a3c-93fe-dd64e73574cd" src="https://github.com/trishasailendran/DEMULTIPLEXER1TO4/assets/87655678/b85cee91-2655-4673-aa17-e3dbb0da80c4">

# Result
Thus the simulate and synthesis of DEMULTIPLEXER 1 TO 4 is verified successfully by using Vivado software.

# RIPPLE_CARRY_ADDER
# AIM
To simulate and synthesis of ripplecarryadder using vivado 2023.
# APPARATUS REQUIRED
vivado 2023
# PROCEDURE
STEP:1 Start the vivado software, Select and Name the New project.
STEP:2 Select the device family, device, package and speed.
STEP:3 Select new source in the New Project and select Verilog Module as the Source type.
STEP:4 Type the File Name and module name and Click Next and then finish button.
Type the code and save it.
STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.
STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.
STEP:7 compare the output with truth table.
# RIPPLECARRYADDER
![image](https://github.com/RESMIRNAIR/RIPPLECARRYADDER/assets/154305926/62459000-90cb-4c43-a221-7b8cf1d419b0)
![image](https://github.com/RESMIRNAIR/RIPPLECARRYADDER/assets/154305926/24ea1940-0b55-4f8a-be6a-a7ac5daf2919)
# Full Adder
![image](https://github.com/RESMIRNAIR/RIPPLECARRYADDER/assets/154305926/3208d46f-2fd4-4d6a-987f-63102c173ca0)
# PROGRAM
module fa(a,b,c,sum,carry);
input a,b,c;
output sum,carry;
assign sum = a^b^c;
assign carry=(a&b)|(b&c)|(c&a);
endmodule
module rca(a,b,cin,sum,cout);
input [3:0]a,b;
input cin;
output [3:0]sum;
output cout;
wire c1,c2,c3;
fa fa1(a[0],b[0],cin,sum[0],c1);
fa fa2(a[1],b[1],c1,sum[1],c2);
fa fa3(a[2],b[2],c2,sum[2],c3);
fa fa4(a[3],b[3],c3,sum[3],cout);
endmodule
# OUTPUT
![image](https://github.com/Akila56/RIPPLECARRYADDER/assets/164776026/8165e38a-e5c5-468f-a915-de2c6d67d13e)
# RESULT
Thus the simulation and synthesis of Ripplecarryadder using vivado 2023.2 is successfully executed and verified.

# JK_FLIPFLOP
## Aim
To simulate and synthesis JK flipflop using vivado.

## Software Required
Vivado 2023.2 software

## Procedure:
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table. 

![image](https://github.com/Douglas0207/JK_FLIPFLOP/assets/166375742/cb5787c3-1c5c-48e5-a831-e382071f9d21)


## Circuit Diagram
![image](https://github.com/Douglas0207/JK_FLIPFLOP/assets/166375742/0cdcb7d7-36c6-4b10-951b-85c791cbc86f)


## Truth Table
![image](https://github.com/Douglas0207/JK_FLIPFLOP/assets/166375742/3116d125-d7a7-45c2-bd1e-357917af4c0c)


## Program

module jkff(clk,j,k,rst,q );
input j,k,clk,rst;
output reg q;
always@(posedge clk)
begin
if(rst==1)
q=1'b0;
else
begin
case({j,k})
2'b00: q=q;
2'b01:q=1'b0;
2'b10:q=1'b1;
2'b11:q=~q;
endcase
end
end
endmodule

## Output
![image](https://github.com/Douglas0207/JK_FLIPFLOP/assets/166375742/08876632-317d-4f89-9cdd-e3c15c326da7)


## Result
Thus the verilog program for JK flipflop has been simulated and verified successfully.

# SR_FLIPFLOP
# AIM
To simulate and synthesis of SR_flipflop using vivado 2023.2
# APPARATUS REQUIRED
To simulate and synthesis of SR_flipflop using vivado 2023.2
# PROCEDURE
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button.

Type the code and save it.
STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.
# PROGRAM
module SR(clk,s,r,rst,q );

input s,r,clk,rst;

output reg q;

always@(posedge clk)
begin

if(rst==1)

q=1'b0;

else

begin
case({s,r})

2'b00: q=q;

2'b01:q=1'b0;

2'b10:q=1'b1;

2'b11:q=1'bx;

endcase

end

end

![image](https://github.com/RESMIRNAIR/SR_FLIPFLOP/assets/154305926/c17acfa3-84d9-4ef6-99ab-d36655169f63)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/SR_FLIPFLOP/assets/154305926/51cb1738-6112-466e-a1b0-f9dd9f2e9d25)
# Truth Table
![image](https://github.com/RESMIRNAIR/SR_FLIPFLOP/assets/154305926/0946849a-bd0a-445b-b27e-0833dee20e51)
# OUTPUT
![image](https://github.com/SIVANANDHI-N/SR_FLIPFLOP/assets/162731951/60df4ee4-afd0-4d81-9bb6-df156a995f71)

# RESULT
Thus the simulation and synthesis of SR_flipflop using vivado 2023.2 is successfully executed and verified

# T_FLIPFLOP
# AIM
To simulate and synthesis of T_flipflop using vivado 2023.2
# APPARTUS REQUIRED
vivado 2023
# PROCEDURE
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button.

Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.
# PROGRAM
module tff(t,clk,rst,Q);

input t,clk,rst;

output reg Q;

always @(posedge clk)

begin

if(rst==1)

Q=1'b0;

else if(t==0)

Q=Q;

else

Q=~Q;

end

endmodule
# BLOCK DIAGRAM
![image](https://github.com/RESMIRNAIR/T_FLIPFLOP/assets/154305926/74140ea2-0b93-4ffc-b38b-527fb2ece133)
# Truth Table
![image](https://github.com/RESMIRNAIR/T_FLIPFLOP/assets/154305926/1d4afa40-166a-4690-ab1a-179948b9b550)
# OUTPUT
![image](https://github.com/Akila56/T_FLIPFLOP/assets/164776026/8116560b-3986-495b-9916-eef5835f2a7d)

# RESULT
Thus the simulation and synthesis of T_flipflop using vivado 2023.2 is successfully executed and verified.

# D_FLIPFLOP
# AIM
To simulate and synthesis of D_flipflop using vivado 2023.2
# APPARATUS REQUIRED
vivado 2023.1 software
# PROCEDURE
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button.

Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.
# PROGRAM
module dff(d,clk,rst,Q);

input d,clk,rst;

output reg Q;

always @(posedge clk)

begin

if(rst==1)

Q=1'b0;

else

Q=d;

end

endmodule

# D_FLIPFLOP
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/4f3e1d9d-e0c3-464e-b0e4-e47946c813bd)
# Truth Table
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/42d38f79-9cc3-4b09-a46f-e0c1241dee57)
# OUTPUT
![image](https://github.com/Akila56/D_FLIPFLOP/assets/164776026/71b2aff0-8ef4-46aa-acba-a4f6b125b655)

# RESULT
Thus the simulation and synthesis of D_flipflop using vivado 2023.2 is successfully executed and verified.
