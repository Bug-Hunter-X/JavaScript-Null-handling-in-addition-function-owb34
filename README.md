# JavaScript Null Handling Bug

This repository demonstrates a subtle bug in a JavaScript function that handles null values unexpectedly during addition. The `foo` function aims to add two numbers, but its handling of null inputs leads to incorrect results.

## Bug Description
The function `foo` returns 0 if either input `a` or `b` is null. While this might seem correct for some use cases, it's not a robust approach for all scenarios. A more robust approach would be to explicitly handle null values, perhaps by throwing an error, treating null as 0, or returning a default value with appropriate logging to indicate the input was null. 

## Solution
The solution provides an improved version of the `foo` function that addresses the null handling issue more explicitly and robustly.