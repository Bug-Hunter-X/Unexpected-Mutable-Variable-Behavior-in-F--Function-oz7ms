# Unexpected Mutable Variable Behavior in F#

This repository demonstrates a subtle but common error involving mutable variables in F#. The `add` function unexpectedly modifies its input parameters, leading to an incorrect result.  This example highlights the importance of carefully managing mutability in F# to avoid unexpected side effects and ensure code correctness.

## Bug Description
The `bug.fs` file contains an F# function that intends to add two numbers. However, due to the misuse of mutable variables, the function modifies its inputs and produces an incorrect result. The solution demonstrates a more functional approach avoiding this problem.