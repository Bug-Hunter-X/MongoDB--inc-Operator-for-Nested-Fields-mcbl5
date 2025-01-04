# MongoDB $inc Operator for Nested Fields
This repository demonstrates an uncommon bug related to using the `$inc` operator in MongoDB to update nested fields. Incorrect usage can lead to unexpected behavior and data inconsistencies.

## Bug Description
The provided code snippet shows how incorrect usage of `$inc` when working with nested objects may fail to update the intended field.  The problem occurs because the dot notation doesn't correctly interpret the nested field when used with the `$inc` operator within a single update operation. 

## Solution
The solution involves a different approach to increment the nested field, utilizing the `$inc` operator correctly within an update operation or using other update approaches that work directly with the nested fields.
