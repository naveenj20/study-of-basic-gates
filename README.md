# DATE: 12/03/2025

### study-of-basic-gates

# NAME: NAVEEN JAISANKER
# REG. NO.: 212224110039

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

'''
module LOGIC_GATE(a, b, c1, c2, c3, c4, c5,c6 ,c7);
input a, b;
output c1, c2, c3, c4, c5, c6, c7;
assign c1 = ~a;
assign c2 = a & b;
assign c3 = a | b;
assign c4 = ~(a & b);
assign c5 = ~(a | b);
assign c6 = a ^ b;
assign c7 = ~(a ^ b);
endmodule
'''

 Developed by: Naveen Jaisanker RegisterNumber: 212224110039 
 
**Logic symbol & Truthtable**

**AND GATE**

![Screenshot 2025-03-19 091858](https://github.com/user-attachments/assets/b8c5f53d-dd3b-49e8-9584-622ec38d62b7)

**NAND GATE**

![Screenshot 2025-03-19 091906](https://github.com/user-attachments/assets/27d15015-29a4-43f8-8aab-e45c4918f77b)

**NOT GATE**

![Screenshot 2025-03-19 091958](https://github.com/user-attachments/assets/28792916-440b-49e1-9ab8-ac8c4ec5b07d)

**OR GATE**

![Screenshot 2025-03-19 092027](https://github.com/user-attachments/assets/1126fe5e-38ed-4489-8257-912114644a5e)

**NOR GATE**

![Screenshot 2025-03-19 092049](https://github.com/user-attachments/assets/addcb1da-abf8-44c6-8ac0-9a1164a3b870)

**XOR GATE**

![Screenshot 2025-03-19 092057](https://github.com/user-attachments/assets/8d494d42-590e-4c00-b806-e64f19b81252)

**XNOR GATE**

![Screenshot 2025-03-19 092103](https://github.com/user-attachments/assets/68729cfe-5205-4459-9179-86bac82b1220)



**RTL realization Output:** 

![Screenshot 2025-03-11 111043](https://github.com/user-attachments/assets/6fcb555a-97c3-4c9e-bb1a-58a3db662920)


**RTL**

![Screenshot 2025-03-11 113039](https://github.com/user-attachments/assets/709b2fa5-72cc-419b-816a-d3579d3bc95f)


**Result:**

Thus, the verification and truth tables of basic gates are verified.


