# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, const, and let
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a subprogram that performs a specific set of instructions within a larger program
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S - Single Responsibility
O - Open/Closed Principle
L - Liskov's Substitution Principle
I - Interface Segregation Principle
D - Dependency Inversion Principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
It's 2 -- the index starts at 0 from left to right
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if((2+2) == 5){
  console.log('It must be 1984!')
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model, the HTML file is accessed first.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
- undefined
- boolean
- number
- string
- null
- arrays
- objects
- functions
- NaN
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is used when defining the function, whereas arguments are passed in place of the parameters when invoking the function.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive value is stored in "the stack", directly in the location a variable accesses. Reference values are stored in "the heap", the variable location contains a pointer to a location in memory where the reference value is stored.
```