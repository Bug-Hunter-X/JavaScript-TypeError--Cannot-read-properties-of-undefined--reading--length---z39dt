# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error: a `TypeError` thrown when trying to access the `length` property of an undefined value.

The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version.

## Bug
The original code doesn't explicitly check for `undefined`, leading to an error when an undefined value is passed to the function.

## Solution
The solution adds a check for `undefined` before accessing the `length` property, handling this case gracefully.