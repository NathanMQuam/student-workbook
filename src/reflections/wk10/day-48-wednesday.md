# Day 48

Nathan Quam

---

[GregsList API with MySQL db](https://github.com/NathanMQuam/C-Sharp-MySQL-GregsList-Api)

---
---

## Daily Journal

Read Foundations of C# > C# Enum's and answer the following questions

1. What is an Enum, and what are some use cases for them?
"Enums are strongly typed constants."
"That means an enum of one type may not be implicitly assigned to an enum of another type, though the underlying value of their members is the same."
"All assignments between different enum types and integral types require an explicit cast."
"Enums are value types, which means they contain their own value, can't inherit or be inherited from, and assignment copies the value of one enum to another."
`Essentially, Enums allow a value to be assigned to a more semantic or meaningful name. They act like a custom defined data type, like volume.medium and volume.low, or meat.medium and meat.rare.`

2. How can you modify an Enum?
`
When assigning the values of an Enum, such as low in the volume enum, you can assign a value instead of just declaring the name and letting it's value be automatically assigned. But, an Enum can only be assigned values when it is declared, once the code moves on the Enum cannot be modified.
`

3. How have you used Enums in your afternoon lab projects this far?(if you have not yet, give an example of how you could)
`
So far, I have not used Enums in any of my projects. But going forward, I can use Enums for meaningful names. I have previously used plain numbers, which are vague, or strings, which leave room for error.
`
