# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

    module funct1(a,b,c,d,f1);
    input a,b,c,d;
    output f1;
    assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
    endmodule


Developed by: RITHIKA M

RegisterNumber: 24900286



**Output:**
  ![ex op1](https://github.com/user-attachments/assets/050bfc89-92cd-40c0-a257-ea537f0f4526)


**RTL**
 ![op2](https://github.com/user-attachments/assets/03a456b9-47de-4b88-93af-97948c271582)

**Timing Diagram**
 ![ex op1](https://github.com/user-attachments/assets/072096b2-f8df-44cf-97e4-faeddc90ad44)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

