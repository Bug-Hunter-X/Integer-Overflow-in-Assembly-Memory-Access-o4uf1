# Integer Overflow Bug in Assembly

This repository demonstrates a simple integer overflow bug in an assembly code snippet. The bug occurs due to the lack of bounds checking before incrementing a value stored in memory.

The `bug.asm` file contains the buggy code.  The `bugSolution.asm` file provides a corrected version that addresses the potential overflow issue.  The solution involves adding a check to prevent the increment from causing an overflow.