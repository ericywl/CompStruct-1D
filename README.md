# Mojo_1D
CompStruct 1D Project

8-bit ALU with the following functionalities:


ALUFN  | Operation | Type    | Description
------ | --------- | ------- | ------------------
000000 | ADD       | ARITH   | A + B
000001 | SUB       | ARITH   | A - B
000010 | MUL       | ARITH   | A * B
011000 | AND       | BOOL    | bitwise A and B
011110 | OR        | BOOL    | bitwise A or B
010110 | XOR       | BOOL    | bitwise A xor B
010111 | NAND      | BOOL    | bitwise A nand B
010001 | NOR       | BOOL    | bitiwse A nor B
011010 | "A"       | BOOL    | output A
011100 | "B"       | BOOL    | output B
011111 | XORCP     | BOOL    | output 1 if odd number of 1's in A
100000 | SHL       | SHIFT   | shift A leftwards by B bits
100001 | SHR       | SHIFT   | shift A rightwards by B bits
100011 | SRA       | SHIFT   | SHR with MSB padding
100100 | RL        | SHIFT   | rotate A leftward by B bits
100101 | RR        | SHIFT   | rotate A rightwards by B bits
110011 | CMPEQ     | CMP     | compare if A == B
110101 | CMPLT     | CMP     | compare if A < B
110111 | CMPLE     | CMP     | compare if A <= B

