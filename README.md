# Assembly Memory Access Bug

This repository demonstrates a common error in assembly programming: accessing memory without bounds checking.  The `bug.asm` file contains code that causes a segmentation fault due to accessing an invalid memory address. The `bugSolution.asm` file provides a corrected version with appropriate bounds checks.

## Setup

To reproduce the error, assemble and run `bug.asm` using your preferred assembler and linker. You will likely encounter a segmentation fault or similar error.

## Solution

The solution involves adding explicit checks to ensure that the memory address calculated is within the valid bounds of the allocated memory.  This is crucial to prevent program crashes and security vulnerabilities.  See `bugSolution.asm` for implementation details.

## Contributing

Feel free to contribute by improving the solution or adding other common assembly errors and their solutions.