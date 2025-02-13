# Dereferencing NULL Pointer in C

This repository demonstrates a common error in C programming: dereferencing a NULL pointer.  The `bug.c` file contains the erroneous code, while `bugSolution.c` provides a corrected version.

**Problem:**
The original code attempts to write a value to a memory location pointed to by a NULL pointer. This leads to undefined behavior, often resulting in a segmentation fault and program crash.

**Solution:**
The corrected code checks if the pointer is NULL before dereferencing.  If it's NULL, an appropriate action is taken (e.g., printing an error message or returning an error code).