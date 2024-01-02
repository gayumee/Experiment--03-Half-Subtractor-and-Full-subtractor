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
Developed by: T. Gayathri
RegisterNumber:  212223100007
*/
## Half Subtractor 
![Exp4 hs code](https://github.com/gayumee/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037327/8f3f3aca-7433-4041-b1b7-b49f05ab85b1)
## Full Subtractor 
![Exp4 fs code](https://github.com/gayumee/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037327/697c6b9e-f903-4296-8d48-2035e0f3613d)


## Truthtable
## Half subtractor
![Exp4 truthtable hs](https://github.com/gayumee/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037327/059f427e-e826-48d5-9f9e-469a8d7be1fb)
## Full subtractor
![Exp4 truthtable fs](https://github.com/gayumee/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037327/57875e62-9902-43ea-95c5-5ca971a95b23)



##  RTL realization
## Half subtractor 
![Exp4 hs RTL diagram](https://github.com/gayumee/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037327/97584449-920d-46cb-986f-08d9184f67df)

## Full subtractor 
![Exp4 fs RTL diagram](https://github.com/gayumee/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037327/df830a05-a6c5-47bb-8b73-491158eed5cf)

## Timing diagram 
## Half subtractor
![hs wave](https://github.com/gayumee/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037327/b6023ecb-f470-424c-94bc-a439d2469ffd)

## Full subtractor 
![fs wave](https://github.com/gayumee/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149037327/f7e14b07-62d3-42a4-983c-aae687539fbe)
## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
