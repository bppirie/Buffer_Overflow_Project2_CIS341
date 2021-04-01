## Buffer_Overflow_Project2_CIS341
### Project 2 of CIS341, execute buffer overflow attacks using the Gets exploit in C

Phase 1:
Use the gdb debugger on C binary 'ctarget' to determine size of string needed to overflow the stack
Find address of function 'touch1' and write address into the stack to get the program to return to 'touch1' instead of main

Phase 2:
Same as phase 1 except return the function 'touch2' and pass cookie string in cookie.txt as an argument to the function

Phase 3:
Use gdb debugger on C binary 'rtarget' but this time the stack is no longer executable 
Use the farm.c library of functions to perform return oriented programming and accomplish the same goal as in Phase 2 but on 'rtarget'
