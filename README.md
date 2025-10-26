# BOOLEAN_FUNCTION_MINIMIZATION
AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D

F2=xy’z+x’y’z+w’xy+wx’y+wxy

Equipment Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

Theory

Logic Diagram

Procedure

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram.

Program:

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by:AHAMED JASEER SHA .E RegisterNumber:212224040015
module
sample2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~a)&(~b)&(~c)&(~d))|(a&
(~c)&(~d))|(~b)&c&(~d)|((~a)&b&c&d)|
(b&(~c)&d);
assign f2=(x&(~y)&z)|((~x)&(~y)&z)|
((~w)&x&y)|(w&x&(~y))|(w&x&y);
endmodule
RTL realization

<img width="1027" height="630" alt="image" src="https://github.com/user-attachments/assets/a343738a-50aa-4744-b200-aedf6f1664bf" />


Output:

<img width="1039" height="512" alt="image" src="https://github.com/user-attachments/assets/3a25e703-2bf5-4b7a-99be-c60dfac01fb4" />


Timing Diagram

<img width="1050" height="576" alt="image" src="https://github.com/user-attachments/assets/51ffb416-741c-4aa7-afba-9c404b147b9e" />


<img width="1049" height="549" alt="image" src="https://github.com/user-attachments/assets/8eb907ca-ee8c-48d9-a227-92396d3180c6" />


Result:

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
