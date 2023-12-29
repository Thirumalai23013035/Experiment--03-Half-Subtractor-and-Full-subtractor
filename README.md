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

![7481a955-4e38-4f41-874e-af36a2891640](https://github.com/Thirumalai23013035/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153185249/9accd4c9-527c-4a21-972a-f0c6fb99bb4b)

 

Write the detailed procedure here 


## Program:

![ae9eaee0-e5a4-48b5-ba43-9b19ce3ac396](https://github.com/Thirumalai23013035/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153185249/814d078e-793e-4114-9d86-df07ee91915b)


![6488c31a-e214-4b82-bd9b-9135f74901e4](https://github.com/Thirumalai23013035/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153185249/e7943d3b-9079-4212-bdf7-ef8a6914a1f6)

/*
 
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/

## Output:

## Truthtable
![OIP](https://github.com/Thirumalai23013035/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153185249/81367658-e54f-4790-97a3-f61cd104f468)
![full-subtractor-truth-table](https://github.com/Thirumalai23013035/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153185249/10d66147-2606-4983-9c17-421c33316373)



##  RTL realization
![Screenshot 2023-11-26 150550](https://github.com/Thirumalai23013035/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153185249/58468641-78b8-46cb-bef6-b73185f1a372)
![Screenshot 2023-11-26 164129](https://github.com/Thirumalai23013035/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153185249/c6312fff-2767-4e93-be9d-3b81b20c3bbb)


## Timing diagram 
![Screenshot 2023-11-26 150532](https://github.com/Thirumalai23013035/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153185249/ee59b871-8b28-4aa0-a27b-a36846bf96f3)
![Screenshot 2023-11-26 164108](https://github.com/Thirumalai23013035/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153185249/7c5ee097-39a7-443f-b2d5-7cc4cbf73d7b)

## Result:

Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
