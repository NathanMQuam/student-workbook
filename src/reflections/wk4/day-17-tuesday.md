# Day 17
Nathan Quam

---

[Extending Greg'sList](link.com)

---
---

## Daily Journal

Read Asynchronous Code > JavaScript Promises and answer the following questions

1. What are the three states of a Promise?
`
Pending, Resolved, and Rejected. When making an http request with a promise it starts in the pending state, until there's been a response from the server, and it will then store a function to run when we get a response. The response will resolve the promise to either "Resolved" or "Rejected." If no issues occured and it returned data, it goes into the resolved state. If something went wrong, such as a timeout, 404, or any other error, it will be "Rejected"
`

2. How do promises seek to resolve the issues of "callback hell"?
`
Promises allow api requests to be saved for later while awaiting a response to continue executing code, or to pause execution until there's a response. This allows each api request to be put in sequential order on new lines, instead of nesting them inside of .then().catch() blocks. This makes the code much cleaner and much more readable.
`

1. What is the difference between .then() and .catch()?
`
The only difference is that then and catch each handle the "Resolved" and "Rejected" promise states respectively. One of the two methods will eventually be invoked, but neither is actually run yet, just stored to memory for later.
`