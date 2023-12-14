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

### Procedure

![Screenshot 2023-12-14 125624](https://github.com/PRAJAN-23013995/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150313345/df9cbe96-95db-4df0-9910-301c2da307a1)

###Program

###Half Subtractor

![Screenshot 2023-12-14 125707](https://github.com/PRAJAN-23013995/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150313345/6285c17f-cb04-487d-92a3-aea828b39af9)

###Full Subtractor

![Screenshot 2023-12-14 130010](https://github.com/PRAJAN-23013995/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150313345/0962bdd0-1e72-4775-a527-7209c493c02a)

Write the detailed procedure here 
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: PRAJAN-P
RegisterNumber:  23013995
*/

## Output:
### RTL realization

###Half Subtractor 

![Screenshot 2023-12-14 130243](https://github.com/PRAJAN-23013995/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150313345/71f85e47-34b2-4998-8c42-9a7bd2f6255e)

###Full Subtractor

![Screenshot 2023-12-14 130255](https://github.com/PRAJAN-23013995/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150313345/08cf7712-8191-437e-8fbf-c79337fa4972)


### Truthtable

###Half Subtractor 


![Screenshot 2023-12-14 130617](https://github.com/PRAJAN-23013995/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150313345/b736a5b2-555a-4a38-879f-07d908c33050)

###Full Subtractor

![Screenshot 2023-12-14 130636](https://github.com/PRAJAN-23013995/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150313345/7eec2430-2aa0-446f-a830-a31647fbff36)

###Timing diagram 

###Half Subtractor 

![Screenshot 2023-12-14 130833](https://github.com/PRAJAN-23013995/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150313345/2cb532f1-9767-4f27-b9ac-cf1b929a6e4f)

###Full Subtractor

![Screenshot 2023-12-14 130920](https://github.com/PRAJAN-23013995/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150313345/89f6a803-9d38-4623-88e4-83609e5da383)



## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
