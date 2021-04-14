# Day 53

Nathan Quam

---

[Auth Taskmaster](https://github.com/NathanMQuam/Auth-Taskmaster)

---
---

## Daily Journal

Read Dotnet WebAPI's > SQL Injection, and answer the following questions

1. What is SQL injection?
`
SQL injection is the execution of arbitrary SQL code or queries by a likely malicious third party. It usually occurs in the form of some user input being parsed by the server and being accidentally run, potentially causing harm/damage.
`

2. What are 3 methods SQL injection can be done by?
`
There's user input, poisoned cookies, and HTTP headers. There are also second-order injections, but these are the sneakiest.
`

3. How can we detect and sanitize SQL injection attacks?
`
One of the simplest methods of sanitization is the removal/denial of characters that are likely to modify any SQL execution, such as a single quote, or semicolons. You can also control user permissions/privileges, and prevent a user input from dropping all tables for example.
`
