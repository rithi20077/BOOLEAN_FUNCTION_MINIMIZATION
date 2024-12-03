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
 ![ex op1](https://github.com/user-attachments/assets/bc2e07eb-18ad-43b4-a38f-8bd17dbf450e)





**RTL**
 ![op2](https://github.com/user-attachments/assets/b5bd83d1-c712-45fc-836b-94e626489a93)


**Timing Diagram**
 ![ex op1](https://github.com/user-attachments/assets/bc2e07eb-18ad-43b4-a38f-8bd17dbf450e)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

