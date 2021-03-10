# Day 16
##### Lucky 16
Nathan Quam

---

[Open Trivia Game](https://github.com/NathanMQuam/open-trivia-game)

---
---

## Daily Journal

Read Asynchronous Code > Callback Hell and answer the following questions

1. What are some of the signs and causes of Callback Hell?
`
When there are several code blocks nested within code blocks, within code blocks... It often occurs when the coder tries to write the code in a way that executes from top to bottom like JS regularly would, despite the code being asynchronous.
`

2. What does the asynchronous mean and how are callbacks involved?
`
Asynchronous means that the function may take some time to run, and will return a value when it is done, instead of right now. Callbacks is a convention used to describe asynchronous code, specifically when a function is stored as a variable and is then invoked when an async function returns a value, instead of immediately. This prevents the code from getting held up waiting for a response.
`

3. Summarize the 3 ways to avoid / fix Callback Hell
`
1. Keep your code shallow, give functions descriptive names and store them for later use instead of putting them inline.

2. Modularize, write small modules that each do one thing, and assemble them into bigger modules that do a bigger thing. Splitting complex code into smaller single-purpose modules makes the code cleaner and easier to read, as well as better adhering to the SOLID principles.

3. Handle every single error, you can never know when errors will happen, so plan on them always happening. The most common method is to use the Node.js style, where the first argument of the callback is reserved for an error.
`
