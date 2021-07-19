# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction, Encapsulation, Inheritance, and Polymorphism.
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
return staff[property] (this should give us "Tim")
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Wrapping data and method together into a single class object for security and privacy in the program.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is an object that defines the properties that object inherits. An instance of a class is a copy, or articulation of the class. That is, it's an object that actually embodies the properties defined by its class, but it does not define the class itself.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy is an object that takes a target and a handler. The handler intercepts and redefines the properties of the target, so that the original (proxied) object is not affected directly, but the proxy is used in its stead.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The MVC pattern obfuscates data from the user, and provides the developer tools to maintain the integrity of their program and limit the surface area through with the user can interact with the state. This provides cleaner, more efficient and readable code on the developer side and a more secure and streamlined functionality for the client side.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller vets user inputs being passed and then targets the appropriate services with the incoming data.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service provides the functional performance that ineracts with the state.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is the state in which data is stored and changed before being presented for view by the user.
```

