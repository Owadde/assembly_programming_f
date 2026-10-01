SUB1.asm

CF (1)- lines 13, 15, 16 - set because of the borrow. smaller number subtracting a larger number.
ZF (1) - line 17 - result of operation was 0. Comparison of ebx with ebx done through subtraction resulted in a 0.
SF (1) - line 13, 15, 16 - result is a negative number
OF (1) - lines 13, 14, 16, 17 
AF (0) - no carry in lower bits
PF (1) - lines 13, 15, 16 - result has even parity
IF (1) - lines 11, 12, 13, 15, 16, 17 - cpu is executing but can change to go execute other programs

SUB2.asm

CF (1)- lines 13, 17, 18 - set because of the borrow. smaller number subtracting a larger number.
ZF (1) - line 19 - result of operation was 0. Comparison of ebx with ebx done through subtraction resulted in a 0. 
SF (1) - line 13, 17, 18 - result of subtraction is a negative number
OF (1) - lines 13, 14, 16, 17 
AF (0) - no carry in lower bits
PF (1) - lines 19 - result has even parity
IF (1) - lines 11, 12, 13, 17, 18, 19 - cpu is executing but can change to go execute other programs