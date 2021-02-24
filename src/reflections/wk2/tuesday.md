# Day 7
Nathan Quam

---

(JavaScript challenges 2, electric boogaloo)[https://github.com/NathanMQuam/js-challenges-2]

---
---

## Daily Journal

Read Intro to JS > JavaScript Functions and answer the following questions

1. What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?
2. What is the difference between Parameters and Arguments?
3. What are higher order functions? Can you provide an example?

### My Response
1. A 'Function Declaration', a 'Function Expression', and an 'Arrow Function.' A function declaration creates a named function, while a function expression defines a named or anonymous function, and an arrow function is a shorthand way to create an anonymous function, and also does not create it's own 'this' value.

2. 'Parameters' are the names inside of the () created during the function declaration. An 'Argument' is the value that the function receives from each parameter when the function is executed (or invoked).

3. When a function accepts another function as a parameter, or returns a function, it is called a higher-order function. An example of this could be:
   ```let person = objArray.find(name => name == "Steve")```
   This line of code looks through an array of objects named 'objArray' using the array method 'find().' Find() runs the code inside it's parameter, which takes a function as an argument, once for every object in the array. It passes into find() an arrow function, which returns true if the current object's.name value is equal to '==' "Steve". When the find() method receives true from the function it called, it stops looping and returns that object from the array. Finally, we are capturing this object and assigning it to the variable 'person'.
