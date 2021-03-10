# Day 13
Nathan Quam

---

[Quam's List](https://github.com/NathanMQuam/Quams-List)

---
---

## Daily Journal

Read Advancing with JS > An Intro to Javascript Proxy Objects and answer the following questions

1. What are the two common operations that we will set in the handler?
`In a proxy object handler, we will usually define a Get and Set operation. These provide even more control over how code can access, utilize, and manipulate our objects and functions.`

2. What do you have to make sure you are doing with every Get to insure the value does not become undefined?
`To ensure a Get doesn't become undefined, you need to always return *something.* You can step through the control flow of the code to see when different values are returned, and you can make sure that there's __at least__ a fallback return statement if the code doesn't operate as expected.`

3. What are some of the benefits of the proxy object that we are using in our structure for applications?
`One benefit of the proxy objects in our application is that we can check for when a value is changed, and when it is call a different function. Another is that we can explicitly control how values are get and set, as well as define some more code than simply getting or setting values in that proxy function.`
