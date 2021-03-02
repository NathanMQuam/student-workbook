# Day 19
Nathan Quam

---

[Music is fun](https://github.com/NathanMQuam/Music-is-Fun)

---
---

## Daily Journal

Read Asynchronous Code > What is REST and answer the following questions

1. What does REST stand for, and in simple terms what does it mean?
```
"REST is an architectural style, or design pattern, for APIs."
"REST stands for REpresentational State Transfer."
REST gives API's a set of standard conventions and rules to follow, making it easier to use a new API or even to create.

REST API's must follow these rules:
Uniform interface
Client --- server separation
Stateless
Layered system
Cacheable
Code-on-demand
```

2. What does Stateless mean?
```
Stateless means that an API must not save/remember anything about any users that access it. Everything the server might need in order to return the correct information is in the initial GET request.
```

3. What URL pattern is used when writing a RESTful API?
```
When making a request the URL must include an identifier for the information you want, and the operation you want the server to perform on that information. These operations usually include GET, POST, PUT, and DELETE
```