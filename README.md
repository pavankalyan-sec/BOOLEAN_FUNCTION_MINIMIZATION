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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
~~~
module logic_function(
input a,b,c,d,
input w,x,y,z,
output f1,f2);
assign f1=(~b&~d)|(a&b&~c)|(~a&b&d);
assign f2=(~y&z)|(x&y)|(w&y);
endmodule 

~~~
~~~
Developed by: Pavan Kalyan P
RegisterNumber: 25010044
~~~


**RTL realization**
<img width="536" height="450" alt="image" src="https://github.com/user-attachments/assets/955e3929-f9a8-493d-9701-4f15b521fba5" />

**Output:**

**RTL**
<img width="1920" height="1080" alt="exp2" src="https://github.com/user-attachments/assets/77b8965a-0832-4df1-a4fa-beb6e383be90" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

