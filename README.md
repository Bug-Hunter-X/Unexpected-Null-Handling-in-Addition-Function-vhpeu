# Unexpected Null Handling in JavaScript Addition Function

This repository demonstrates a subtle bug related to null value handling in a simple JavaScript addition function.

The `foo` function adds two numbers.  However, it returns 0 if either input is null. This behavior might be unexpected or incorrect depending on the desired functionality. The solution demonstrates a more robust approach to handling null values, preventing unexpected results.

## Bug
The original `bug.js` file contains the flawed function, which returns 0 if a null value is passed in.

## Solution
The `bugSolution.js` file demonstrates how to improve the function to handle null values in a more appropriate manner (treating null as 0).