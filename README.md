# MongoDB $inc Operator Error: String Value Instead of Number

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numeric field by a specified value. However, if you provide a string value instead of a number, the update will fail to produce the expected result and might even result in an error in some cases.

**Bug:** The `bug.js` file shows an incorrect implementation that passes a string ("1") to `$inc`, resulting in an unintended behavior. 

**Solution:** The `bugSolution.js` file provides the correct usage of `$inc` which demonstrates passing an actual numeric value to `$inc` for increment operations.
