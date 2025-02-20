# Incorrect Usage of $inc Operator in MongoDB Update Operation

This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update operation. The `$inc` operator is designed to increment or decrement a numerical value by a specified amount.  However, attempting to increment with a string value will lead to an error.

## Bug
The `bug.js` file contains code that incorrectly uses the `$inc` operator with a string value. This will result in an error when executed.

## Solution
The `bugSolution.js` file demonstrates the correct usage of the `$inc` operator. It increments the value of a numerical field by a numerical value.

This example highlights a common error when working with MongoDB update operations.  Always ensure that the values you provide to the `$inc` operator are numerical.