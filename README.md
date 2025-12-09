# BOOLEAN_FUNCTION_MINIMIZATION
**Date:09/12/2025**


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
module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule

```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Kishor B RegisterNumber: 25017562 */


**output**

<img width="953" height="508" alt="Screenshot 2025-12-09 203036" src="https://github.com/user-attachments/assets/6e762b2f-946f-4c0b-bd35-69a3ea624307" />


**RTL realization**
**RTL**

![ex=2 output](https://github.com/user-attachments/assets/55df8200-40f8-4499-9612-d9dc975e6fbb)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming..
.

.
.
.
.

.
.
.
.

.
.
.

.
.
.
.
.
.


.
.
.
.

..

.
.
.
.
.

..

.
.
.
.
.
.


.
.
.
.
.

.
.
.
.

.
.

.
.
.
.
.
.
.
.
.
.
.
.
.

..


.
.
.
.
.
.

.
.
.

.

.
.
.
.
.
.
.
.
.
.

..
.
.
.
.
.
.
.
.
.4

.

.

.

.
.
.


.
.
.


.

.
.
.



