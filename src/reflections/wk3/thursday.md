# Day 14
Nathan Quam

---

[Partner Project, Shopping Page](https://github.com/JordanWilker/Week-3-Day-4)

---
---

## Daily Journal

Read Advancing with JS > The Observer Pattern and answer the following questions

1. What problems does the Observer Pattern seek to solve?
`The observer pattern seeks to solve "one-to-many, one-way, and event-driven data binding. It is a problem that comes up often when you have many elements that must be in sync." Such as for example, when we have many different objects on a page which can change independently from each other.`

2. What are the three mechanisms of the observer pattern?
`Subscribe, Unsubscribe, and Broadcast. These let you subscribe or unsubscribe functions from being run when an event occurs, and broadcasting an event to invoke the subscribed methods.`

3. Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
`The ProxyState/AppState is an observer in the observer pattern. It gives us the On and Off methods to subscribe or unsubscribe a function from being called when a value changes.`
