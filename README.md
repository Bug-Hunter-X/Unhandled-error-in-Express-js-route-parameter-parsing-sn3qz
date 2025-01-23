# Express.js Route Parameter Error Handling

This repository demonstrates a common error in Express.js route handlers:  failure to handle invalid input parameters.  The `bug.js` file shows the problematic code, which attempts to parse a user ID from a route parameter without checking for non-numeric values. This can cause an error if a user enters a non-numeric ID.

The `bugSolution.js` file provides a corrected version with proper error handling.