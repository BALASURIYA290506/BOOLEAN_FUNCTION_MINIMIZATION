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
```
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
Developed by: Balasuriya M
RegisterNumber: 212224240021
```
```
module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
```
```
module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
```
**RTL realization**

**Output:**

**F1:**

![image](https://github.com/user-attachments/assets/028ce4a4-bcf6-4b25-b8bb-d0a43e320049)

**F2:**

![image](https://github.com/user-attachments/assets/41b0c2bf-106a-406b-9f77-a675ea32040f)


**RTL**

**F1:**

![image](https://github.com/user-attachments/assets/a75e37fe-2378-44f3-a39e-3db363cb22ff)

**F2:**

![image](https://github.com/user-attachments/assets/e7c3c8af-8be2-4d23-84db-5f1cb0c06544)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

