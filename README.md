# Backend-Router-Level-Middleware

Node and Express: Router middleware
This lesson should take you about 25 minutes. If you spend longer than that on this lesson, reach out for help!

Instructions
Your goal for this lesson is to get the tests to pass. To do so, you will be building a middleware function and placing it in the right place in the pipeline.

File structure and setup
In the utils/ folder, there is a file called validateNameLength.js that includes a function of the same name.

Create middleware
The validateNameLength() function should assess the length of the name route parameter. Then:

If the name is three characters or longer, move on to the next step of the middleware pipeline.

If the name is less than three characters long, trigger the error-handling middleware function with the following message:

"Name length is too short."
