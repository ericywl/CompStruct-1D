# Mojo_1D
CompStruct 1D Pojek

8-bit ALU with the following functionalities
ARITH
======
000000 - ADD, outputs A plus B
000001 - SUB, outputs A minus B
000010 - MUL, outputs A * B

BOOL (bitwise)
===============
011000 - AND, outputs A & B 
011110 - OR, outputs A | B 
010110 - XOR, outputs A ^ B 
010111 - NAND, outputs !(A & B)
010001 - NOR, outputs !(A | B)
011010 - "A", outputs A
011100 - "B", outputs B
011111 - XORCP, outputs 1 if odd number of 1's in A

SHIFT
======
100000 - SHL, shift all A bits leftwards by B amount with 0 padding
100001 - SHR, shift all A bits rightwards by B amount with 0 padding
100011 - SRA, shift all A bits rightwards by B amount with MSB padding
100100 - RL, rotate all A bits leftwards by B amount ie. left circular shift
100101 - RR, rotate all A bits rightwards by B amount ie. right circular shift

CMP
====
110011 - CMPEQ, outputs 1 if A == B
110101 - CMPLT, outputs 1 if A < B
110111 - CMPLE, outputs 1 if A <= B
