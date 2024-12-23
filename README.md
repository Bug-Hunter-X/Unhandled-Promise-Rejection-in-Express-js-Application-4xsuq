# Unhandled Promise Rejection in Express.js

This repository demonstrates a common, yet subtle, error in Express.js applications: unhandled promise rejections.  Asynchronous operations often involve promises, and if an error occurs within a promise but isn't properly caught and handled, the application might fail silently, making debugging difficult.

The `bug.js` file shows an example of this issue.  The `bugSolution.js` file provides a corrected version with robust error handling.