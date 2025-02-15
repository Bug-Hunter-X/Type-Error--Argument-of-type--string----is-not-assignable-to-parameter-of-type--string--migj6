# TypeScript Type Error: Argument of type 'string[]' is not assignable to parameter of type 'string'

This repository demonstrates a common TypeScript error: passing an array to a function expecting a string. The `bug.ts` file contains the erroneous code, while `bugSolution.ts` provides a corrected version.

The error arises because the `greeter` function is explicitly typed to accept a single string (`person: string`) and return a string.  Attempting to pass an array of strings results in a type mismatch.

The solution involves either modifying the `greeter` function to handle arrays or adjusting how the `user` variable is handled to pass only a single string.