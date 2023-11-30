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

## HALF Subtractor

![Screenshot 2023-11-26 143921](https://github.com/Pradeepkumar-2005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474038/2db9866a-b48c-4b36-8b9c-de8d80889674)


## Full Subtractor

![Screenshot 2023-11-26 144911](https://github.com/Pradeepkumar-2005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474038/eb2ba6f2-0ac3-4ef2-b463-e6e9f9822641)

/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: Pradeep kumar R
RegisterNumber:  23006358
*/

## Output:

## Truthtable

## HALF Subtractor

![WhatsApp Image 2023-11-30 at 10 47 29 PM](https://github.com/Pradeepkumar-2005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474038/5ca1e424-5428-4b6c-9a8a-27dc80b5791b)

## Full Subtractor

![Exp4 truthtable fs](https://github.com/Pradeepkumar-2005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474038/2218e123-9b96-442c-8572-67c90bc8f589)



##  RTL realization

## HALF Subtractor

![Screenshot 2023-11-26 143850](https://github.com/Pradeepkumar-2005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474038/0d4410c8-d45e-4ae2-9c8c-f455a1a8bc69)


## Full Subtractor

![Screenshot 2023-11-26 151305](https://github.com/Pradeepkumar-2005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474038/0c2af869-f498-4cbf-a0b8-482d3c942120)




## Timing diagram 

## HALF Subtractor

![Screenshot 2023-11-26 150729](https://github.com/Pradeepkumar-2005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474038/71701176-8190-478a-8764-23fa2f0df2b7)

## Full Subtractor

![Screenshot 2023-11-26 151237](https://github.com/Pradeepkumar-2005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474038/0e141dcb-3be5-4e11-8353-f5434f586aaa)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
