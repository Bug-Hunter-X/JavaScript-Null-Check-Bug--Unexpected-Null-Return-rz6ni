# JavaScript Null Check Bug

This repository demonstrates a common JavaScript bug related to null checks and its solution. The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version.

## Bug Description
The function `foo` aims to add two numbers.  However, if either input is `null`, it should return `null`. The buggy code incorrectly returns `null` even if only one of the inputs is `null`.

## Solution
The corrected code in `bugSolution.js` uses a more robust null check, ensuring the function behaves as intended.