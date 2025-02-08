# JavaScript Loose Comparison and Null/Undefined Handling

This repository demonstrates a common error in JavaScript related to loose comparison (==) and the handling of null and undefined values.  The `bug.js` file shows a function that attempts to add two numbers but fails to correctly handle cases where one or both inputs are null or undefined. This can lead to unexpected results, such as NaN (Not a Number).

The `bugSolution.js` file provides a corrected version that uses strict equality (===) to handle null and undefined values explicitly and gracefully.

## How to Reproduce

1. Clone this repository.
2. Navigate to the repository directory in your terminal.
3. Run `node bug.js` to observe the unexpected behavior.
4. Run `node bugSolution.js` to see the corrected output.

## Lesson Learned

This example underscores the importance of using strict equality (===) in JavaScript when comparing values, especially when dealing with null, undefined, 0, and empty strings which may cause unexpected results with loose comparison. Always explicitly handle edge cases to prevent unexpected behavior and improve code robustness.