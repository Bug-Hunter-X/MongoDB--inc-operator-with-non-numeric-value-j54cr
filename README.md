# MongoDB $inc Operator with Non-Numeric Value

This repository demonstrates a common error in MongoDB when using the `$inc` operator with a non-numeric value. The `$inc` operator is designed to increment a numeric field by a specified value; attempting to increment with a string or other non-numeric type will result in an error or unexpected behavior.

## Bug
The `bug.js` file contains code that attempts to increment a field using `$inc` with a string value. This results in an error or incorrect modification.

## Solution
The `bugSolution.js` file shows the correct usage of the `$inc` operator, ensuring that the increment value is numeric.