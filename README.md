# Haskell Undefined Value Bug
This repository demonstrates a common, yet subtle, error in Haskell programming involving the use of the `undefined` value.  The code attempts to perform a calculation with an undefined value, leading to a runtime error.  The solution shows how to avoid this by using appropriate type handling and default values.

## Bug
The `bug.hs` file contains Haskell code that uses the `undefined` value in a calculation. This results in a runtime error when the program is executed.

## Solution
The `bugSolution.hs` file provides a corrected version of the code. The solution addresses the issue by introducing a default value to replace `undefined` ensuring the program runs without errors.
