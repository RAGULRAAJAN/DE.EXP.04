# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
Write the detailed procedure here 
## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: RAGUL RAAJAN .T
RegisterNumber:23007752  
*/

## CODE:
 ### HALF SUBRACTOR:
 ![Screenshot 2023-12-23 054910](https://github.com/RAGULRAAJAN/DE.EXP.04/assets/147473144/43d01943-4ce6-47ea-a77b-aefff678752c)

 ### FULL SUBRACTOR:
![Screenshot 2023-12-23 054941](https://github.com/RAGULRAAJAN/DE.EXP.04/assets/147473144/71341b63-35ec-4fdc-82a2-ed1acf558cd2)

## Truthtable
 ### HALF SUBRACTOR:
![Screenshot 2023-12-23 055413](https://github.com/RAGULRAAJAN/DE.EXP.04/assets/147473144/fda740e3-bba2-4edf-a965-60489e0f6ddb)

 ### FULL SUBRACTOR:
 ![Screenshot 2023-12-23 055516](https://github.com/RAGULRAAJAN/DE.EXP.04/assets/147473144/9b5ae100-6881-4887-b24c-3f86e6594596)

##  RTL DIAGRAM:
### HALF SUBRACTOR:
![Screenshot 2023-12-23 055737](https://github.com/RAGULRAAJAN/DE.EXP.04/assets/147473144/7f3607ce-a920-4339-8aa2-f9b31f4bf83a)

 ### FULL SUBRACTOR:
 ![Screenshot 2023-12-23 055757](https://github.com/RAGULRAAJAN/DE.EXP.04/assets/147473144/c4acb5e2-f315-4194-9c16-cec54060af08)

## Timing diagram 
### HALF SUBRACTOR:
![Screenshot 2023-12-23 060037](https://github.com/RAGULRAAJAN/DE.EXP.04/assets/147473144/1b7025e9-4d8c-4882-9b6f-bf426aa9c72f)

 ### FULL SUBRACTOR:
 ![Screenshot 2023-12-23 060054](https://github.com/RAGULRAAJAN/DE.EXP.04/assets/147473144/d696eab5-7ecc-4ac5-91fb-ea2eaded6b3f)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
