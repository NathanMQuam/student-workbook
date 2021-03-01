# Day 18
Nathan Quam

---

(Pokedex API)[https://github.com/NathanMQuam/pokedex-api]

---
---

## Daily Journal

Read Asynchronous Code > Async and Await and answer the following questions

1. What is the purpose of Async/Await?
```
Async/Await make the code read as though it's synchronous, even though it isn't. It also mitigates callback hell by allowing asynchronous functions to chain, instead of being nested inside of each other.
```

2. What must you do in order to await a promise inside of a function?
```
In order to await a promise inside a function, the function keyword must be prepended with the async keyword, to indicate the function as asynchronous. While not required, any and all awaited promises should either be placed inside a try().catch() block, or be appended with the .then().catch() block to better handle rejected responses.
```

3. What are some of the primary benefits of Async/Await?
```
Async/Await make the code much more readable, making it easier to write and to debug. They also make the control flow of the code more readable and obvious.
```