# Unhandled Exception in Node.js HTTP Server
This repository demonstrates an unhandled exception in a Node.js HTTP server and its solution.  The server throws an error if the request URL is '/error', but the error is not properly caught, causing the server to crash.  The solution shows how to correctly handle the error using the 'error' event listener.