# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value.  However, providing a string value instead of a number results in an unexpected behavior or error.

The `bug.js` file shows the erroneous code, and the `bugSolution.js` file provides the correct implementation.

## How to Reproduce

1.  Ensure you have MongoDB installed and running.
2.  Create a collection named 'myCollection' with a document containing a numeric field, e.g., `counter`.
3.  Run the code in `bug.js`.
4.  Observe the error or unexpected result.
5.  Run the code in `bugSolution.js` to see the correct behavior.

## Bug Description

The `$inc` operator expects a numeric value. Using a string value causes unexpected behavior or a MongoDB error.  This typically happens due to a type mismatch or incorrect data handling.