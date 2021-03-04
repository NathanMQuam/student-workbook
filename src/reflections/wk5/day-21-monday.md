# Day 21
Nathan Quam

---

[Borger Shaq](https://github.com/NathanMQuam/burger-shack-node-api)

---
---

## Daily Journal

Read Servers with Node/Express > Using Query Parameters and answer the following questions

1. What is the purpose of a Query String?
`
A query string allows the client to give the server some information in order to get other information back. The server can receive and interpret the query string to process it and return the correct data.
`

2. What is the format of a query parameter? How does it start? How do you distinguish between one parameter and the next?
`
?paramter=value
?key=value&key=value2
`

3. When do you think Query parameters would be helpful when writing your server?
`
Query parameters are helpful when the client needs to access specific information from a sever, such as page 2 in a category. When writing my server, query parameters would be helpful for retrieving a specific burger from the available burger shack burgers. They're also helpful for sending non-sensitive information.
`