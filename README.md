# Unexpected String Concatenation in JavaScript

This repository demonstrates a common error in JavaScript related to the unexpected behavior of the `+` operator when used with a mix of numbers and strings. The `bug.js` file shows the erroneous code, and the `bugSolution.js` provides the corrected version.

## Bug Description
In JavaScript, the `+` operator is overloaded.  It performs both numerical addition and string concatenation. When used with a mix of number and string operands, JavaScript will implicitly convert the number to a string and perform string concatenation rather than numerical addition. This often leads to unexpected behavior and incorrect results.

## Solution
The solution involves using the `parseInt()` function to ensure that both operands are numbers before performing addition.  This ensures the addition operation is performed as intended.

## How to Run
1. Clone this repository.
2. Navigate to the repository's directory.
3. Run `node bug.js` to see the erroneous behavior.
4. Run `node bugSolution.js` to see the corrected behavior.