# Unresponsive Node.js Server Due to Synchronous Long Operation

This repository demonstrates a common issue in Node.js where a long-running synchronous operation in the request handler can make the server unresponsive.  The `bug.js` file contains the problematic code. The solution involves refactoring the code to use asynchronous operations or offloading the long task to a worker thread. The solution is provided in `bugSolution.js`.