# Closure

- Before ES6 provided the block scope, people used to utilize the concept of closure to create the block scope.
- ### Creating a closure requires 
  - A parent function
  - A child function
  - And Two return statements.

- Parent Function provide function scope, the variables that we want to protect are declared in parent function.
- Child Function helps us to access those protected variables, from the global scope.
- In the return statement of the inner function we only return the name of the inner function not the invocation of inner function.