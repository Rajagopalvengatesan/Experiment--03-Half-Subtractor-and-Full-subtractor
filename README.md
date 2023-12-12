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
Developed by: Rajagopal V
RegisterNumber:23002920  
*/
### code 
![image](https://github.com/Rajagopalvengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/144870784/7b874647-cd42-4212-8eab-b99b17d1302b)

## Truth Table 
## Half Subtractor
![image](https://github.com/Rajagopalvengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/144870784/fb23db42-5c45-4796-b6f7-397ee11f0523)
## Full Subtractor

![image](https://github.com/Rajagopalvengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/144870784/26176a39-24c4-4e2b-94ec-3dd5009ece00)

## RTL
## Half Subtractor
![image](https://github.com/Rajagopalvengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/144870784/c993668d-8e13-4bb3-9670-5eaf9ce6a4e8)

## Full Subtractor
![image](https://github.com/Rajagopalvengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/144870784/b058ca53-6e2b-4eb6-817b-1bb939564b11)





## Timing diagram 
## Half Subtractor 
![image](https://github.com/Rajagopalvengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/144870784/827f793e-6858-4ba6-bcff-b5a3f3da144e)
## Fulf Subtractor
![image](https://github.com/Rajagopalvengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/144870784/ccb6b3a6-0a06-443a-b492-a7d39ecbfeaa)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
