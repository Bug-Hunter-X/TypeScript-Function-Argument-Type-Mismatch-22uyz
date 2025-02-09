# TypeScript Function Argument Type Mismatch Bug

This repository demonstrates a common error in TypeScript: passing an argument of the wrong type to a function. The `greeter` function expects a single string, but an array is provided. The TypeScript compiler will catch this type error, preventing runtime failures.

## Bug

The `bug.ts` file contains the erroneous code.  The `greeter` function is defined to accept a string, but an array of strings is passed. This results in a compilation error.

## Solution

The `bugSolution.ts` file shows two ways to fix the bug:  1) modifying the `greeter` function to accept an array of strings and iterate through them, or 2) passing the appropriate single string.

This example highlights the importance of careful type checking in TypeScript for preventing common runtime errors.