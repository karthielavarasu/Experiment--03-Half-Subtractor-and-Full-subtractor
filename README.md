## Name:R.Elavarasu
## Reg:23013515

## Experiment--03-Half-Subtractor-and-Full-subtractor
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

## Full Subtractor:
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure:



Write the detailed procedure here 


## Program:

## Half Subtractor:

![Screenshot 2023-12-21 214733](https://github.com/karthielavarasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980473/bf0865ad-16a0-4af5-ae24-dd0700e1c669)


## Full Subtractor:
![exfull](https://github.com/karthielavarasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980473/8fd92959-667b-451d-bf44-de97b26e0bd2)


Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 

## Truthtable:

## Half Subtractor:
![Screenshot 2023-12-21 215055](https://github.com/karthielavarasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980473/5fa5a858-3ef2-41cb-8aac-f4c2a108bc67)


## Full Subtractor:
![Screenshot 2023-12-21 215151](https://github.com/karthielavarasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980473/987d0aba-452b-49bc-8698-38640b5cb4e2)


##  RTL realization:

## Half Subtractor:
![Screenshot 2023-12-21 215248](https://github.com/karthielavarasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980473/d8db481f-e3e6-4c81-a5e7-8b11681b03cf)


## Full Subtractor:

![Screenshot 2023-12-21 215352](https://github.com/karthielavarasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980473/1ffbf9eb-b167-47b5-bf1c-1eb328d67efa)

## Timing diagram:

## Half Subtractor:
![Screenshot 2023-12-21 215500](https://github.com/karthielavarasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980473/870fdff4-fc6e-4a8a-b80d-1d3856cf5a87)


## Full Subtractor:
![Screenshot 2023-12-21 215551](https://github.com/karthielavarasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980473/8cb8d868-9c50-4fc7-89c1-bdc631542192)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
