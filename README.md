# Middleware
In this a basic Middleware function is created. Middleware functions are used to add the functionalities to the EXPRESS Application. 

IMPORTANT POINTS TO NOTE:

1. Whenever a request arrives to the server, first of all it goes to the middleware functions and then to the handlers.
2. Order of middleware does matter.
3. Using next() after each middleware is also important so that your server can go to the next function.
