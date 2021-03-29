# Day 39

Nathan Quam

---

[Capstones](https://github.com/JordanWilker/Prompetition)

---

---

## Daily Journal

Read Working In a Professional Environment > Testing in Vue and answer the following questions

1. What are the three main types of testing we can accomplish in Vue? What does each method provide?
`
Unit Testing, Component Testing, and End-to-End (E2E) Testing. Unit tests are for individual pieces of code in isolation. Vue components need to mounted to a real or virtual DOM to be tested, bringing in component testing. End-to-End testing is for the bigger picture, the overall actions and reactions of things like user inputs and the app's outputs.
`

2. What testing method do you think is the most useful? Why?

`
None of the methods are truly better or worse than the others, but Unit Testing provides the most granular and exact tests which are usually very clearly passing or failing. A large portion of components and End-to-End functionality are more humanly-testable as it's easy to see when something isn't working the way it should be.
`

3. What testing method do you think is the least useful? Why?
`
Component Testing seems the least useful to me, as it's code can be tested with Unit tests. Plus, the actual DOM-mounted-component is usually very clearly working or broken.
`
