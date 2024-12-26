# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

1. Full Adder

   ![image](https://github.com/user-attachments/assets/deff94df-e5dd-42ee-b4ef-3af099aaf323)

2. Full Subtractor

   ![image](https://github.com/user-attachments/assets/d5246c51-a25b-4409-904a-7893418f37fa)


**Procedure**

Write the detailed procedure here

**Program:**

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 

Developed by: MERIL GOLDLINA A RegisterNumber: 24007299

![image](https://github.com/user-attachments/assets/94ca5155-dcac-47b3-ae34-64127f16c131)


**RTL Schematic**

1. FULL ADDER

![image](https://github.com/user-attachments/assets/96c0575d-eeb5-4f7d-8ae3-8b2148600e93)

2. FULL SUBTRACTOR

![image](https://github.com/user-attachments/assets/a8ac8728-12ba-4797-81d4-dbe78da1cd50)


**Output Timing Waveform**

1. FULL ADDER
   
![image](https://github.com/user-attachments/assets/27f28e87-2f27-445e-a068-ad879f7a3ae7)

2. FULL SUBTRACTOR

![image](https://github.com/user-attachments/assets/c0f2cca7-7de6-4ed1-9da6-8b44e67b8e45)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.




