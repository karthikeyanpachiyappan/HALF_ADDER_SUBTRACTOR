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

# Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

# Developed by: karthikeyan P
# RegisterNumber:212223230102
# HALF ADDER
![image](https://github.com/karthikeyanpachiyappan/HALF_ADDER_SUBTRACTOR/assets/155143878/c196885d-6ec4-418b-ac12-c4f743fa576b)

# RTL Schematic
![image](https://github.com/karthikeyanpachiyappan/HALF_ADDER_SUBTRACTOR/assets/155143878/228a7577-ae5e-461c-a9c9-3e31c59d5396)

# Truth table
![image](https://github.com/karthikeyanpachiyappan/HALF_ADDER_SUBTRACTOR/assets/155143878/d3931159-5031-4e6d-8cf6-f09135df42f5)


# output/TIMING Waveform
![image](https://github.com/karthikeyanpachiyappan/HALF_ADDER_SUBTRACTOR/assets/155143878/3939eef1-70e8-4746-b60c-6aa0d6fd802a)

## HALF SUBTRACTOR
# Program
![image](https://github.com/karthikeyanpachiyappan/HALF_ADDER_SUBTRACTOR/assets/155143878/df967c55-e319-40a5-8861-1c9854084499)

# RTL Schematic
![image](https://github.com/karthikeyanpachiyappan/HALF_ADDER_SUBTRACTOR/assets/155143878/2dbd959a-28f1-4538-9ba6-ec98a00af99c)

# Truth table
![image](https://github.com/karthikeyanpachiyappan/HALF_ADDER_SUBTRACTOR/assets/155143878/7345c9a5-5b3a-482c-9183-c7eb407e34f9)

# Output/TIMING Waveform
![image](https://github.com/karthikeyanpachiyappan/HALF_ADDER_SUBTRACTOR/assets/155143878/109dc8cb-9849-46f4-a36a-f0edd933929a)

# Result:
Thus the program has successfully verified.
