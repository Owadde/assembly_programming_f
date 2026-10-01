flags raised:
1. Interrupt flag in line 17 and throughout the program - indicating the program is being executed but cpu is open to execute a different program when triggered.

2. Parity flag, Auxilliary Carry Flag, Sign Flag, Interrupt Flag, Overflow Fag - line 22, 23. 
PF - indicates result is an even parity
AF - there was a carried bit in the lower bits
SF - the number is a negative number
IF - program is running but cpu can be diverted
OF - resulting number is negative meaning the two numbers were large numbers causing the left most bits to be spilled.

3. Parity flag, Zero flag, Interrupt flag - line 24
PF - indicates result is an even parity
ZF - register is cleared
IF - program is running but cpu can be diverted