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

module ex2 (a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1 = ~a&~b&~c&~d | a&~c&~d | ~b&c&~d | ~a&b&c&d | b&~c&d;
assign f2 = x&~y&z | ~x&~y&z | ~w&x&y | w&~x&y | w&x&y;
endmodule


Developed by:MUHAMMAD ASJAD E 
RegisterNumber:25013957
*/


**RTL realization**

<img width="807" height="650" alt="Screenshot 2025-11-16 154626" src="https://github.com/user-attachments/assets/3b436368-09bd-44ff-903d-b0d3676cff48" />


**Output:**

**RTL**
F1:

<img width="550" height="414" alt="Screenshot 2025-11-16 154720" src="https://github.com/user-attachments/assets/8a522733-0272-4c71-b5ee-ac6e2f8186ba" />

F2:

<img width="586" height="370" alt="Screenshot 2025-11-16 154728" src="https://github.com/user-attachments/assets/0a8e887e-ab5f-4132-b255-6f066fd5b10b" />

**Timing Diagram**

<img width="1695" height="334" alt="Screenshot 2025-11-16 155405" src="https://github.com/user-attachments/assets/c9680576-4bd5-4539-abe8-a9b9f6f8edc3" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

