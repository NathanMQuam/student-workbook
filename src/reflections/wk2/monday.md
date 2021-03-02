# Day 6
Nathan Quam

---

[JavaScript Challenges](https://github.com/NathanMQuam/Javascript-Challenges)

---
---

## Daily Journal

Read Intro to JS > Var, let and const and answer the following questions

1. What is Scope ?
2. What is Hoisting 
3. In what cases might you use let vs const vs var?


### My Response
1. "Scope" is the different levels of hierarchy in code, with each block of code being a deeper level. A variable declared outside of any functions is at the "global" scope level, and anything within the current window can access it. While a variable declared within a function is only accessible from inside of that function. Scope is a very important part of encapsulation.

2. Hoisting is when a variable is declared, but hasn't yet been assigned a value. When the computer enters into a block of code, any variables declared in the current block will be hoisted before the code starts to actually run. Until they are assigned a value, 'Var's will have the value "Undefined" and 'Let's will not be initialized and will not have a value, or be unassigned. 'Const's must be initialized at the time of declaration, as once they are initialized they cannot be changed. 'Const's are also hoisted to the top, but are not initialized.

3. If you have a variable that you want any block of code within the variable's scope to be able to change, you can use a Var. Or you can use a Let if you want a variable to *only* be accessible within it's current scope, and not any deeper blocks of code. A Const is useful for a variable that you know is not ever going to change, but you need to read multiple times.