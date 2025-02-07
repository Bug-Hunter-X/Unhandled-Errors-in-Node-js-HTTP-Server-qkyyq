# Unhandled Errors in Node.js HTTP Server

This repository demonstrates a common error in Node.js where unhandled exceptions in an HTTP server can lead to crashes or unexpected behavior.  The `bug.js` file showcases the problematic code. The solution is shown in `bugSolution.js`.

## Problem
The provided server lacks robust error handling.  If an error occurs during request processing, the server will likely crash without providing informative error messages.