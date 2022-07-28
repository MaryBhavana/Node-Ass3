Middleware

Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application's request-response cycle. These functions are used to modify req and res objects for tasks like parsing request bodies, adding response headers, etc.

Express.js is a routing and Middleware framework for handling the different routing of the webpage and it works between the request and response cycle. Middleware gets executed after the server receives the request and before the controller actions send the response. Middleware has the access to the request object, responses object, and next, it can process the request before the server send a response. An Express-based application is a series of middleware function calls.



Middleware Syntax: The basic syntax for the middleware functions are as follows –

                         app.get(path, (req, res, next) => {}, (req, res) => {})
                         



Advantages of using middleware:

   =>Middleware can process request objects multiple times before the server works for that request.
   
   =>Middleware can be used to add logging and authentication functionality.
   
   =>Middleware improves client-side rendering performance.
   
   =>Middleware is used for setting some specific HTTP headers.
   
   =>Middleware helps for Optimization and better performance.
