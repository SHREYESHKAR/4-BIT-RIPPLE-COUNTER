# NAME : SHREYESHKAR SEKAR 
# REFERENCE NUMBER : 24900622


# EXP 12 : 4-BIT-RIPPLE-COUNTER

## AIM:

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

## SOFTWARE REQUIRED:

Quartus prime

## THEORY

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

## Procedure

/*

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.*/

## PROGRAM

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

*/



![WhatsApp Image 2024-12-21 at 7 50 52 PM (1)](https://github.com/user-attachments/assets/45ae7060-347a-4348-b963-08ca40c07817)


## RTL LOGIC FOR 4 Bit Ripple Counter


![WhatsApp Image 2024-12-21 at 7 51 00 PM](https://github.com/user-attachments/assets/d62c84dd-c4a2-46a1-958a-5d7e33c84869)



## TIMING DIGRAMS FOR 4 Bit Ripple Counter


![WhatsApp Image 2024-12-21 at 7 50 42 PM (3)](https://github.com/user-attachments/assets/208bf35d-1885-41f3-afd8-9a37e97f44bd)




## RESULTS

 4 Bit Ripple Counter implemented using verilog and validated their functionality using their functional tables successfully .

