# Javascript Promises (Week 4 Day 2)

## What are the three states of a Promise?
1. Pending
2. Resolved
3. Rejected

## How do promises seek to resolve the issues of "callback hell"?

Rather than trying to maintain a strict sequencing of callbacks, we can use Promises to chain functions together while still running our code on an asynchronous pattern.

## What is the difference between .then() and .catch()?

".then()" is called when the Promise successfully returns, whereas ".catch()" is triggered when the Promise fails.