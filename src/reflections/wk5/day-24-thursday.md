# Day 24
Nathan Quam

---

[Afternoon Challenge](link.com)

---
---

## Daily Journal

Read Servers with Node/Express > Virtuals in Mongoose and answer the following questions

1. What is a virtual property?
`
A virtual property is an additional value/parameter/field for an item/instance in the database. A virtual property is not actually a stored value, but is instead a generated/logical value, like fullname being a concatenation of first and last name.
`

2. When might you use a virtual property?
`
You might use a virtual property for getting a full name from the stored first and last name. You might also use it for any logical information, like a combination of two other properties, or anything that can be logically extracted from the stored information.
`

3. How do you search by a virtual properties value?
`
"Virtuals are NOT available for document queries or field selection. Only non-virtual properties work for queries and field selections."
`