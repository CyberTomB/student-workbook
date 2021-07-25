# Async and Await (Wk 4 Day 3)

## What is the purpose of Async/Await?

Async defines the client function and "await" creates a Promise that the calling code will wait for a return value from. This enables the rest of our code outside of the async function to continue running.

## What must you do in order to await a promise inside of a function?

Use the "async" keyword when defining the function, then use the "await" keyword to define the part of the function that should wait on the return promise.

## What are some of the primary benefits of Async/Await?

Chained functions are more readable than "regular" callbacks, and debugging is more straightforward because the compiler will interpret the code as if it was synchronous.