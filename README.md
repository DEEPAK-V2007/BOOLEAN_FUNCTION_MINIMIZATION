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

## Developed by: DEEPAK.V
## RegisterNumber: 212225230044
*/
```
module EXP2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1 = ~b&~d | a&b&~c | ~a&b&d;
assign f2 = ~y&z | x&y | w&y;
endmodule
```
**RTL realization**

![WhatsApp Image 2026-03-09 at 11 16 14 AM](https://github.com/user-attachments/assets/f754cbba-3f98-46ef-a873-1bb6788f230c)

**RTL**

![WhatsApp Image 2026-03-09 at 11 20 52 AM](https://github.com/user-attachments/assets/ef81a6ee-b472-48ac-902d-484f36990f7c)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

