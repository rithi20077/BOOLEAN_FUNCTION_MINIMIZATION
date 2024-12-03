# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
   
    module boolean1(a,b,c,d,f1);
    input a,b,c,d;
    output f1;
    assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
    endmodule



Developed by: RITHIKA M

RegisterNumber: 24900286


**RTL realization**
V![op2](https://github.com/user-attachments/assets/f648460c-7cbe-4494-8527-b869ac29f162)


**Output:**
![ex op1](https://github.com/user-attachments/assets/f99e2655-a401-4ff9-aa98-2dc3bd82c007)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

