# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER


**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.


##Half-Adder

![WhatsApp Image 2025-11-15 at 8 07 41 PM](https://github.com/user-attachments/assets/66436351-2bdc-47c7-8485-87b8085bd17f)


##Half-Subtractor


![WhatsApp Image 2025-11-15 at 8 07 42 PM](https://github.com/user-attachments/assets/d83b4c74-86a7-4cf0-b807-d0907f5a7d4d)





Developed by:NARENDRA KRISHNAN KS RegisterNumber:25008086

**RTL Schematic**
##Half-Adder
![WhatsApp Image 2025-11-15 at 8 06 28 PM](https://github.com/user-attachments/assets/0de28187-27bf-4ba1-ba43-6e19b65a65b3)
##Half=Subtractor
![WhatsApp Image 2025-11-15 at 8 13 53 PM](https://github.com/user-attachments/assets/67eb4ce7-2b0e-42d8-8033-688ecbc09f70)




**Output/TIMING Waveform**
##Half-Adder
![WhatsApp Image 2025-11-15 at 8 15 41 PM](https://github.com/user-attachments/assets/74277678-4230-49a2-b14f-efb3b04f7216)
##Half-Subtractor
![WhatsApp Image 2025-11-15 at 8 16 57 PM](https://github.com/user-attachments/assets/10283d02-8b47-4bd9-b3bb-e951acc7bbcc)




**Result:**
Thus the a half adder and half subtractor circuit is designed and its truth table is verified in Quartus using Verilog programming .
