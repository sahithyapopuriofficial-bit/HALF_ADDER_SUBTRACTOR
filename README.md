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


**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)


**Truthtable**

## HALF ADDER

<img width="752" height="390" alt="{EB432CC3-E799-43AF-914F-1E5C2142B523}" src="https://github.com/user-attachments/assets/38536d05-909f-408c-aaa1-000d7e94bd63" />

## HALF SUBTRACTOR

<img width="418" height="217" alt="{ABBA83E3-75D2-434F-B73F-5D031967B5CF}" src="https://github.com/user-attachments/assets/55a3e96f-51f7-4983-9719-562b3e112893" />

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

 Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: POPURI SAHITHYA RegisterNumber: 25004681

## HALF ADDER

<img width="397" height="173" alt="{549F18F1-8231-4927-BC4A-F6D71D1B4B54}" src="https://github.com/user-attachments/assets/6d162f77-130e-4ee8-807d-fdda8a15f934" />

## HALF SUBTRACTOR

<img width="428" height="137" alt="{9A3796FF-42C8-403F-9D88-3B1B677D7386}" src="https://github.com/user-attachments/assets/d1b5e4d1-87fe-4085-8c55-d62e63870d34" />


**RTL Schematic**

## HALF ADDER

<img width="986" height="435" alt="{337911B4-C810-416E-9B65-AAAB3463072A}" src="https://github.com/user-attachments/assets/87d5a0ec-fec3-418d-abe0-4d6da0376927" />

## HALF SUBTRACTOR

<img width="989" height="396" alt="{DAD24B4B-8F70-4727-B4E8-EA7E4E56BA61}" src="https://github.com/user-attachments/assets/35bb46b8-1e58-420e-9cb5-e0d41a437fcd" />

**Output/TIMING Waveform:**

## HALF ADDER

<img width="1004" height="118" alt="{8F81400D-D432-4A7A-91A5-AB338566EBDF}" src="https://github.com/user-attachments/assets/33dafcc9-a55f-418f-a3e4-806ab8776a18" />

## HALF SUBTRACTOR

<img width="1002" height="121" alt="{CB0B6972-D3A0-4966-8CDA-C68CD16FACD9}" src="https://github.com/user-attachments/assets/6ed7908d-f523-4578-824c-0d47e072546c" />

**Result:**
Thus the half adder and half subtractor circuits are designed and the truth tables is verified using quartus software.
