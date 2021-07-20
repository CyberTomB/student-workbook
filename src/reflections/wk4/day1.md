# Asynchronous Code (Week 4 Day 1)

## What are some of the signs and causes of Callback Hell?

A sign of callback hell would be large series of conditional statements (typically nested one after another) creating messy "pyramid" shapes in the code editor. This is caused by a developer trying to write Javascript functionality in a way where they expect the code to run "top to bottom" sequentially.

## What does the asynchronous mean and how are callbacks involved?

Asynchronous means code blocks can execute in a non-linear order. You use callbacks in order for your code to register "when" a given block's execution has completed, allowing dependent processes to wait, while non-dependent processes can continue unabated.

## Summarize the 3 ways to avoid / fix Callback Hell

1. Keep your code shallow.
2. Modularize
3. Handle every single error.



Project Link: https://github.com/CyberTomB/trivia-game