# Day 12
Nathan Quam

---

(Vendr)[https://github.com/NathanMQuam/Vendr]

---
---

## Daily Journal

Read Advancing with JS > Encapsulation in JavaScript and answer the following questions

1. What is the purpose of Encapsulation?

2. What were some of the problems with closures and the underscore prefix?

3. How do we create private variables in an ES6 Class? Why would you do this?

### My Responses

1. Encapsulation gives much more control over the program and what it actually does. Encapsulation prevents external code from directly interacting with any of the internal code. For example, you could take a global variable and put it into an instance of a class, and only allow functions called on that class to change the variable, instead of any other function from anywhere under the global scope just making whatever changes it wants whenever it wants.

2. The underscore prefix does not explicitly define a function as private-only, it's only a shorthand for noting a function as privately accessible. The underscore prefix can cause a false sense of security, and the function may be exposed when it shouldn't be.

3. Variables and functions outside of a class file's export will be private, and only accessibly by the class. Or variables created inside of a non-constructor function inside of the exported class will be scope-limited to only inside of that function.