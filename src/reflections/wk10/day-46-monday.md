# Day 46

Nathan Quam

---

[Afternoon Challenge](link.com)

---
---

## Daily Journal

Read Foundations of C# > C# Data Types and answer the following questions

1. What are the three categories of data types? How are they different?

* Value Type
   `Value types are variables which directly store a data value. These are usually numbers, or a boolean. Passing a value type from one method into another creates a new copy of that value, which is separate from the original value.`
* Reference Type
  `A reference type variable does not directly store a data value, instead it stores a memory address to a value. These are usually a string, array, class or delegate. Reference types default to null, which means they are not currently storing a reference. When passing a reference type variable to a method passes it's memory location reference, meaning that any changes made to the variable also occurs anywhere that variable in memory is referenced.`
* Pointer Type

1. What are the Value-type data types? What differences do you notice from JavaScript?

* bool
* byte
* char
* decimal
* double
* enum
* float
* int
* long
* sbyte
* short
* struct
* uint
* ulong
* ushort

`These data types only store a literal data value, and as opposed to JavaScript, the exact type of number must be specified, instead of a general "number" data type.`

2. In your own words how do Reference types get stored in memory? How does this differ from Value types?
`
A reference type variable does not directly store a data value, instead it stores a memory address to a value. While value types only store a literal data value in memory.
`
