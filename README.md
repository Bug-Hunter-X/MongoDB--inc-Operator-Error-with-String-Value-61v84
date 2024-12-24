# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The `$inc` operator is used to increment a numerical field by a specified value. However, if a non-numerical value is provided, it will result in an error.

## Bug
The `bug.js` file contains the incorrect usage of the `$inc` operator, where a string value '1' is used instead of a number. This will result in a MongoDB error.

## Solution
The `bugSolution.js` file demonstrates the correct way to use the `$inc` operator, by using a numerical value.

## How to Reproduce
1. Clone this repository.
2. Install Node.js and the MongoDB Node.js driver.
3. Run `bug.js` and observe the error.
4. Run `bugSolution.js` to see the correct implementation.