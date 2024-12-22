# Improper Null Handling in JavaScript

This repository demonstrates a common error in JavaScript: improper handling of null values in function arguments.  The `bug.js` file contains the faulty code, while `bugSolution.js` provides a corrected version.

## Problem

The original function `foo` attempts to add two numbers. However, it fails to explicitly handle cases where one or both of the inputs (`a` and `b`) are `null`.  This can lead to unexpected results, crashes, or runtime errors.

## Solution

The corrected function in `bugSolution.js` addresses this by adding a check for `null` values at the beginning.  If either `a` or `b` is `null`, the function returns 0.  Otherwise, it performs the addition as intended.

This demonstrates the importance of robust null handling in JavaScript to prevent unexpected errors and ensure the reliability of your code.