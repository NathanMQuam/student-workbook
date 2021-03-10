# Day 8
Nathan Quam

---

[Rock - Paper - Scissors, Shoot!](https://github.com/NathanMQuam/Rock-Paper-Scissors)

---
---

## Daily Journal

Read Intro to JS > Chrome Developer Tools and answer the following questions
1. What are the main ways to write information to the console? Why/when should you use each style.
````console.log()``` and ```console.error()```. 'console.log()' will simply print it's arguments to the console. Meanwhile, 'console.error()' will print to the console in red error text and can provide a link to the probable cause of the error in a javascript file (which would include the file, and the specific line), or it will link you to the network tab if the error came from an API call.`

2. Which tab allows you to see the breakdown of HTML/CSS and how can this tab be useful when debugging HTML?
`The 'Elements' tab will let you see the HTML and CSS styles being applied to any selected element, including rules and styles that are being overridden. This can be useful when trying to find what rule is giving an element a style you don't want, or when you're trying to give an element a style and it's not applying because something is overriding it.`

3. Outside of writing everything to the console, what is a better way to debug your code?
`Outside of printing to the console, you can use the 'Debugger' in the dev tools, which will let you look at the files, the code, the call stack and break points. Printing to the console is useful if you need to see the specific value of a variable, or how many times an event has happened. The debugger will let you edit the code directly in the window/tab and add break points. When the code is run, if it reaches a break point, it will pause the execution and highlight where the computer is in the code, and will let the user dictate when to move to the next step of execution, and when to simply resume running like normal.`
