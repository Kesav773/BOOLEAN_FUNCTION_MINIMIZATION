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
module EXP2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(w&y)|(x&y));
endmodule
```

Developed by:Kesav K.M RegisterNumber:*/ 24004978


**RTL realization**
![Screenshot 2024-11-23 204933](https://github.com/user-attachments/assets/15a87786-0b83-4f3f-a7da-9228ed6defa3)


**Output:**

**RTL**

**Timing Diagram**
![Screenshot 2024-11-23 205341](https://github.com/user-attachments/assets/a4c328c4-e24c-458c-afa1-592116aa8095)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

