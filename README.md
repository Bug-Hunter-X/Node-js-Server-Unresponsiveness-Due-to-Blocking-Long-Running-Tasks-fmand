# Node.js Server Unresponsiveness Due to Blocking Long-Running Tasks

This repository demonstrates a common issue in Node.js where long-running operations in request handlers can block the event loop, causing the server to become unresponsive to new requests. The `bug.js` file contains code that simulates this problem.  The solution demonstrates the importance of asynchronous operations using promises or async/await to prevent blocking.