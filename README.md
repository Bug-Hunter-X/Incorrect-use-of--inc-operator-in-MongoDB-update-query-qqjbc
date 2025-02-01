# MongoDB $inc Operator Error
This repository demonstrates an error related to the incorrect usage of the `$inc` operator in MongoDB update queries. The `$inc` operator is designed to increment a numerical value, but in the provided code, a string value is passed, which causes an error. The solution shows the correct way to use the `$inc` operator.
## Bug
The original code demonstrates an incorrect usage of the `$inc` operator.  It attempts to increment the 'age' field by the string '1'. This results in a MongoDB error. 
## Solution
The solution shows the correct way to use the `$inc` operator, by passing a numerical value to increment the 'age' field.