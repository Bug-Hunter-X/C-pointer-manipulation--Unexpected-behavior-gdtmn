# C Pointer Manipulation: Unexpected Behavior

This repository demonstrates a common error in C related to pointer manipulation and variable modification.

## Bug Description
The provided C code snippet aims to modify a variable's value using a pointer. While the intent is simple, a subtle issue can arise if the pointer is not handled correctly.

## Bug Solution
The solution addresses the potential error in pointer manipulation by providing a corrected approach. It ensures that the pointer accurately targets the intended memory location and the modification occurs as expected.

## How to Run
1. Clone the repository.
2. Compile the C code using a suitable compiler (e.g., GCC):
   `gcc bug.c -o bug`
   `gcc bugSolution.c -o bugSolution`
3. Run the compiled executable: