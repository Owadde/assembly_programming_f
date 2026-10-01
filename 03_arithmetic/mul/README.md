MUL1.md

CF (0)- no carry occurred.
ZF (0) - line 21 - result of operation was zero. done by comparing through subtraction in ebx.
SF (1) - line 13, 15, 16, 17 - result is a negative number
OF (0) - no overflow of bits.
AF (0) - no carry in lower bits
PF (1) - line 13, 15, 16, 17 - result has even parity
IF (1) - line 11, 13, 15, 17- cpu is executing but can change to go execute other programs

MUL2.md

CF (1)- lines 13, 14, 16, 17 - carry occurred. too large for destination register, had to go to upper register.
ZF (0) - line 21 - result of operation was zero. done by comparing through subtraction in ebx.
SF (1) - line 13, 15, 16, 17 - result is a negative number
OF (1) - lines 13, 14, 16, 17 - result led to more bits that surpased sit limit of destination register.
AF (0) - no carry in lower bits
PF (1) - lines 13, 14, 16, 17 - result has even parity
IF (1) - lines 13, 14, 16, 17- cpu is executing but can change to go execute other programs