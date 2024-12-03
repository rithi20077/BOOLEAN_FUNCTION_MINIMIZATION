# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**


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


Developed by: M RITHIKA
RegisterNumber:24900286


**RTL realization**
![op2](https://github.com/user-attachments/assets/666648d7-46e8-48d0-bc48-483681ee55c6)

**Output:**
![ex op1](https://github.com/user-attachments/assets/9644879b-caea-4adc-aa94-bc26e1dbb0d2)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

