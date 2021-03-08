# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
`
Create, Read, Update, and Delete
`

**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
`

Create: POST
Read: GET
Update: PUT
Delete: DELETE
`

**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
`
Object-Relational Mapping
`

**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
`
GET and PUT
`

**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
`
Synchronous, Asynchronous
`

**6.** Fill in the missing piece of this snippet of code.

```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```js
import mongoose from "mongoose"
let Schema = mongoose.Schema;
```

**7.** What is middleware?
<!-- enter you answer in the space below -->
`
Middleware is a communication bus between two endpoints, which handles and manages all information going in and out of it. An example of this is an API, where a client requests a specific set of information from the API, the API goes to and gathers that information from a database/server and returns the requested information back to the client.
`

**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks.
<!-- enter you answer in the space below -->
`
Request
Response
`

**9.**
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
`
https://endpoint/tag/:winter
`
