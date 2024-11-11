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
module exp_2(f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor,a,b);
input a,b;
output f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor;
and(f_and,a,b);
or(f_or,a,b);
not(f_not,a);
nor(f_nor,a,b);
nand(f_nand,a,b);
xor(f_xor,a,b);
xnor(f_xnor,a,b);
endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24004887


**RTL realization**

**Output:**![WhatsApp Image 2024-11-11 at 14 37 31_f47a2212](https://github.com/user-attachments/assets/4c06844f-8078-477c-89b5-2578cdb90f25)



**RTL**

**Timing Diagram**
![WhatsApp Image 2024-11-11 at 14 38 52_cbbee5e9](https://github.com/user-attachments/assets/9d814cad-7f5c-49dc-aee5-8ce562403933)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

