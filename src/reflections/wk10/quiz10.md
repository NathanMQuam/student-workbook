# C# Fundamentals

**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
`
A namespace is an identifier that groups related classes together. Such as console.writeLine() and console.read() which are both in the system.console namespace.
`

**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
`
Classes and structs are both data structures that encapsulate a group of methods, properties, and events. A class is a reference type, meaning that it doesn't actually contain the data it stores, but instead stores a location in memory for that data. A struct is a value type, meaning that it actually stores all of the values within itself in memory.
`

**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
`
new
`

## Example 1

```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```

**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
`
The Start() method has the public access modifier, which makes the method public to anything that can access the Car class.
`

**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
`
On the method Start(), string is the return type of the method.
`

**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
`
Abstract in the example means that the class is a definition for child classes, but it itself will not ever be used to store data.
`

**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
`
In a parent class, only virtual methods can be overridden by child classes.
`

**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
`
Public, Private, Protected, and Internal
`

**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
`
When a class or method is private, only the parent that contains it can access it.
`
