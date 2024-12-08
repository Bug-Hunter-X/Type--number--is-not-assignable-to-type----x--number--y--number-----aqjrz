# TypeScript Type Assertion Bug

This repository demonstrates a common TypeScript error related to type assertions and function arguments.  The `bug.ts` file contains code that attempts to pass a number to a function expecting an object with x and y properties.  The `bugSolution.ts` file provides a corrected version.

## How to Reproduce

1. Clone this repository.
2. Compile `bug.ts` using the TypeScript compiler (tsc).
3. Observe the compilation error.

## Solution

The solution involves ensuring the correct object type is passed to the function. The `bugSolution.ts` file shows the corrected implementation.