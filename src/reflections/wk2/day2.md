# Functions, Objects & Loops (W2-D2)

## What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?

You can write them the following ways:

```
function fnName(params){
}

let name = function(params){}

let name = (params) => {}
```

The important thing to know is that in the third case, the function object is nameless and can't be referenced directly elsewhere in your code.

## What is the difference between Parameters and Arguments?

Parameters are placeholders that expect to receive data. Arguments are the data being passed into those parameters.

## What are higher order functions? Can you provide an example?

A higher order function is a function that takes a function as an argument or returns a function. A good example might be the .find() method, which requires a callback function to perform an operation over an array.

### Daily Project:
 https://github.com/CyberTomB/more-js-challenges