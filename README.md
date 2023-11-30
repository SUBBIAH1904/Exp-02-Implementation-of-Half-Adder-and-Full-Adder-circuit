# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 

#### Figure -01 HALF ADDER 

![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -02 FULL ADDER 

![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:

###Full Adder Code

![Exp3 1 fa code](https://github.com/SUBBIAH1904/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473604/ca2cec42-0ef0-4df9-8dde-90f1598eef63)


###Half Adder Code

![Exp3 ha code](https://github.com/SUBBIAH1904/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473604/4789ec7f-ae6a-45fa-9836-c39c51a8d77a)

/*

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: SUBBIAH S

RegisterNumber:  23005732

*/

###Full Adder Truthtable 

![Exp3 truthtable (fa)](https://github.com/SUBBIAH1904/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473604/39811e8b-9a49-4de5-9a51-3e563d37ba60)

###Full Adder RTL realization

![Exp3 fa RTL diagram](https://github.com/SUBBIAH1904/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473604/b4fac74f-0ba1-4d15-ac44-c3f1c455e2e3)


###Full Adder TIMING DIAGRAM

![Exp3 fa wave](https://github.com/SUBBIAH1904/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473604/76f1cd3f-8a02-4d86-8620-4b15e224153a)


### Output:

### Half Adder Truthtable

![Exp3 truthtable (ha)](https://github.com/SUBBIAH1904/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473604/6825c050-4c86-4351-aa57-ad0790358939)

### Half Adder RTL  realization

![Exp3 ha RTL diagram](https://github.com/SUBBIAH1904/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473604/2ac850fd-6f6f-455a-a5ee-d1722c3b26e8)

### Half Adder TIMING DIAGRAM

![Exp3 ha wave](https://github.com/SUBBIAH1904/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473604/991524a3-4fc8-4e4a-b0c4-4d102e62dd8a)


### Result:
