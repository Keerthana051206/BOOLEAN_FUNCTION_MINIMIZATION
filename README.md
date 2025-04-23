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

Developed by: RegisterNumber:*/ 212224220047
i) module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
ii) module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|( w &y )|(x & y));
endmodul



**RTL realization**
<img width="490" alt="image" src="https://github.com/user-attachments/assets/a38f0143-c999-41bd-9311-fe19fffa78d0" />
![Screenshot 2025-04-23 214914](https://github.com/user-attachments/assets/184f5d27-972f-40b1-a815-528e503d2850)

**Truth Table**
<img width="597" alt="image" src="https://github.com/user-attachments/assets/936f1c0f-0511-41e2-afd1-d7d9b1901788" />
<img width="546" alt="image" src="https://github.com/user-attachments/assets/32b5dec0-6af4-4a7a-af23-a3de4132d076" />


**Output:**
<img width="638" alt="image" src="https://github.com/user-attachments/assets/3d531d52-35ed-4bf7-b48e-92e00bd7a366" />
<img width="638" alt="image" src="https://github.com/user-attachments/assets/9e2ec01f-5a60-443f-846c-9e48325d4f8d" />


**RTL**

**Timing Diagram**
<img width="632" alt="image" src="https://github.com/user-attachments/assets/84542428-d354-4d61-bb2a-b261baf5f684" />
<img width="635" alt="image" src="https://github.com/user-attachments/assets/84006317-f5a7-4bb3-91c5-84bc570e083c" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

