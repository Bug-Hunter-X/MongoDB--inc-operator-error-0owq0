# MongoDB $inc operator error
This repository demonstrates an uncommon error related to the usage of the `$inc` operator in MongoDB update queries.

## Bug Description
The original code uses the `$inc` operator with a string value instead of a number. This leads to an unexpected behavior or error.

## Solution
The correct usage of the `$inc` operator requires a numerical value to increment the field.