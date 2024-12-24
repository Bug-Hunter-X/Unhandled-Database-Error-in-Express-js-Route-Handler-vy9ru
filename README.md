# Unhandled Database Error in Express.js Route Handler

This repository demonstrates a common error in Express.js applications:  missing error handling for database queries within route handlers.

The `bug.js` file shows a route that fetches user data.  It correctly handles the case where a user is not found, but it lacks error handling for database errors (e.g., connection failures, query execution failures).

The `bugSolution.js` file provides a corrected version with robust error handling, including the use of `try...catch` blocks and appropriate HTTP status codes.