# Uncommon C Pointer Arithmetic Bug
This repository demonstrates a subtle bug related to pointer arithmetic in C. The bug involves modifying a variable indirectly through a pointer, leading to unexpected behavior.

## Bug Description
The provided C code snippet demonstrates how modifying the value pointed to by a pointer affects the original variable. This seemingly straightforward example highlights a common pitfall in C programming that can lead to difficult-to-debug issues in more complex scenarios.

## How to Reproduce
Compile and run the `bug.c` file. The output will be different from what one might initially expect.