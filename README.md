# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling for invalid input.  Specifically, the route `/users/:id` attempts to parse the `id` parameter as an integer without checking for potential errors, such as non-numeric values.  This can lead to unexpected behavior, including crashes or incorrect responses.

The `bug.js` file contains the erroneous code. The `bugSolution.js` demonstrates how to fix the issue by adding robust error handling.