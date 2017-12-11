
1. Middleware - function you can plug which ties two parts of the application. body-parser is a middleware function. We can specifically tell the route handler to use middleware using the third parameter using some function.
  e.g server.get('/route', somefunction, (req, res));
2. Decomposition - using middleware code to allow functions used multiple times without having to repeat the code multiple times but instead simply call the function. 
