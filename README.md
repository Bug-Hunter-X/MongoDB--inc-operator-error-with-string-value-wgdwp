# MongoDB $inc Operator Error with String Value
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The error arises from providing a string value instead of a numerical value to the `$inc` operator.

## Bug Description
The `$inc` operator is used to increment a numerical field in a MongoDB document.  However, if a string value is used instead of a number, MongoDB will throw an error.

## Solution
Ensure that the value provided to the `$inc` operator is a number.