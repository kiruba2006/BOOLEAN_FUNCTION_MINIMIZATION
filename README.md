# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-10-22 at 10 20 18 AM](https://github.com/user-attachments/assets/2fa68466-a84e-4fd8-a007-cae84098c24d)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24900445


**RTL realization**
![Screenshot (1)](https://github.com/user-attachments/assets/7a0629cc-d6e2-466d-946b-91cba124c4ff)






**Timing Diagram**
![Screenshot 2024-10-29 112115](https://github.com/user-attachments/assets/c995db4d-734d-4067-9b08-016fdf3ad4e9)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

