# Forms and Templates (Week 3 Day 3)

## What are the two common operations that we will set in the handler?

The "get" and "set" operations.

## What do you have to make sure you are doing with every Get to insure the value does not become undefined?

We need to ensure the value being returned by the default implementation of the "get" function is readable. That is, when we override the default implemenation, we need to provide a return for the value attempting to be accessed with the given key.

## What are some of the benefits of the proxy object that we are using in our structure for applications?

We can privatize the properties of objects, and set strict limitations on what information can be set to an object. In addition, we can provide custom error responses.
