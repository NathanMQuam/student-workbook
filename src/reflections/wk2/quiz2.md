# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter your answer in the space below -->
`
  Let, Var, and Const
`
**2.** What is the definition of a function?
<!-- enter your answer in the space below -->
`
  A function is a block of code held within an object, the function has a set of inputs and returns an output.
`

**3.** What are the `SOLID` principles?
<!-- enter your answer in the space below -->
`
  ***S***
    * Single-Responsibility
  ***O***
    * Open-Closed
  ***L***
    * Liskov Substitution
  ***I***
    * Interface Segregation
  ***D***
    * Dependency Inversion
`
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter your answer in the space below -->
`
  [2], because arrays are index 0 based, 'apple' is 0, 'banana' is 1, and 'pineapple' is 2
`
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter your answer in the space below -->
`
  you.friends.push(them)
`

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter your answer in the space below -->
`
  (num1 >= num2) || (str1 == "comparison string")
`
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter your answer in the space below -->
`
This is the 'Increment Expression,' which is a line of code that is always run after every time the below block of code is run. It is usually used to increment or decrement the 'i' variable.
`
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter your answer in the space below -->
`
  "Document Object Model"
`

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter your answer in the space below -->
`
  There are 6 'Primitives':
  * Undefined
  * Boolean
  * Number
  * String
  * BigInt
  * Symbol

  2 'Structural Types':
  * Object
  * Function

  and 1 'Structural Root' primitive:
  * Null
`

**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter your answer in the space below -->
`
A 'parameter' is the name of a variable in the function parenthesis() that the function uses. An 'argument' is the actual variable that is passed into a function when it is called/invoked.
`

**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter your answer in the space below -->
`
a 'primitive' value is a simple value assigned to a variable. A 'reference' value is a reference to the complex object, instead of the entire object being the value.
`