# High-speed Hardware Integer Multiplier Implementations

### Design high-speed hardware integer multipliers and implement them in Verilog. 

### Design of 6 different multipliers as follows:

1. 8-bit signed (2’s complement) multiplier using radix-4 modified booth algorithm and two 4-bit Carry-Lookahead-Adders.
2. 8-bit unsigned multiplier using radix-4 modified booth algorithm and three 4-bit Carry-Lookahead-Adders.
3. 8-bit unsigned multiplier using four 8-bit unsigned multiplier modules and a 1 level CSA-based Wallace tree and a 
16-bit 2-level CLA. 
4. 16-bit (2’s complement) multiplier using four 8-bit multiplier modules and a 1 level CSA-based Wallace tree and a 
16-bit 2-level CLA. The 8-bit multiplier modules used are unsigned, signed, signed-unsigned multipliers.
5. 16-bit booth algorithm array multiplier for 2’s complement numbers
6. 16-bit array multiplier for unsigned numbers.

### Reference
‘Computer Arithmetic Algorithms’ by Israel Koren.
