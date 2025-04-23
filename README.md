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


![WhatsApp Image 2025-04-23 at 21 31 14_56ee0b79](https://github.com/user-attachments/assets/0f953223-8e36-4e0c-af84-4eb51ad46a1f)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
Exp 2:
module logic_function(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module logic_function(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule	
 ```

Developed by: RegisterNumber:212224050027


**RTL realization**

![WhatsApp Image 2025-04-23 at 21 11 34_620a2658](https://github.com/user-attachments/assets/060c70f7-2c23-4839-a856-b12e5bd15a12)


![WhatsApp Image 2025-04-23 at 21 11 40_7858b34d](https://github.com/user-attachments/assets/ef61e6f8-8bed-4f2b-968e-6b22c7c3f089)



**RTL**

![WhatsApp Image 2025-04-23 at 21 11 24_7d53d6b9](https://github.com/user-attachments/assets/0b268a14-6231-4e3a-86d3-5228351b40e5)

![WhatsApp Image 2025-04-23 at 21 11 30_e9fe7bce](https://github.com/user-attachments/assets/5cf7b3c3-10b1-4009-a244-6d1116b4d5a1)



**Result:**

Thus the given logic functions are implemented using Quartus and their operations are verified using Verilog programming.

