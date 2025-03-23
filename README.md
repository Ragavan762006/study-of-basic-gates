### RAGAVAN E
### 212223040160
### EXP1 STUDY OF LOGIC GATES

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
![WhatsApp Image 2025-03-17 at 10 13 20_14efb063](https://github.com/user-attachments/assets/a7ccf971-50cc-4dd9-904f-2d299cc8754f)

 
**Logic symbol & Truthtable:**

![image](https://github.com/user-attachments/assets/3d587784-cff7-48f7-a426-a7d0bbe62ae6)


**RTL realization Output:** 

![WhatsApp Image 2025-03-17 at 10 13 50_2c94c965](https://github.com/user-attachments/assets/5746ea73-55bc-4b73-8124-f13f5f25bc72)



**RTL:**

![WhatsApp Image 2025-03-17 at 10 29 19_6172f6f3](https://github.com/user-attachments/assets/10e69196-b902-49c1-b69f-6a3160682fb1)


**Result:**

Thus the truth table of logic gates (AND,OR,NOT,NAND,NOR,XOR,XNOR) is successfully implemented and verified using verilog programmming in Quartus II.

