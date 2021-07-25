# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Asynchronous means functions can operate without blocking the rest of your code from running.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is essentially a function that waits for an event from your DOM/Page to be trigger. It "listens" for page events from the browser.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open/Close Pinricple - classes should be open for extension but closed for modification.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
Higher order functions are functions that perform operations on other functions. Like taking functions as arguments: as an example.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is the return value of an asynchronous function which carries out operations without blocking further code. Use the "catch" method to capture error returns.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
POST, PUT, and DELETE
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The "service" objects are responsible (or in MVC terms, the "controller", rather than the model or viewer)
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Encapsulation helps us adhere to the "O" in solid - creating objects in our code that can be "extended" without the definition of those objects being modified.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
Internal Server Error - meaning the responding server was unable to complete the request within its own system.
```