# MongoDB $inc operator type error
This example demonstrates an uncommon error when using the `$inc` operator in MongoDB update operations.  The error arises from providing a string value instead of a numeric value to the `$inc` operator.

The incorrect code attempts to increment the `count` field by '1' (a string), which results in unexpected behavior rather than incrementing the numeric value of the field. The solution demonstrates the correct usage.