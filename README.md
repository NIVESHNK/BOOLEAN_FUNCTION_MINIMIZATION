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


![WhatsApp Image 2025-04-23 at 21 31 14_0c0c9349](https://github.com/user-attachments/assets/a57f97fc-67bb-44ca-ba4c-9785e01ebd90)

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

![WhatsApp Image 2025-04-23 at 21 11 34_e7b030bf](https://github.com/user-attachments/assets/47f2fed7-5e18-4309-b80a-6010ecf76fda)


![WhatsApp Image 2025-04-23 at 21 11 40_ae603491](https://github.com/user-attachments/assets/5531e04d-053e-4979-af10-5052ca0df838)


**RTL**

![WhatsApp Image 2025-04-23 at 21 11 24_a4836895](https://github.com/user-attachments/assets/f1b77a27-e344-4f78-8445-2880bbc06506)

![WhatsApp Image 2025-04-23 at 21 11 30_e1cc0a6c](https://github.com/user-attachments/assets/1ff10260-4c0f-4f32-aa47-a5a030d8280d)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

