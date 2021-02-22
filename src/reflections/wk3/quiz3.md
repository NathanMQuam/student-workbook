# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
  S - Single-Responsibility
  O - Open-closed Principle
  L - Liskov Substitution Principle
  I - Interface Segregation Principle
  D - Dependency Inversion Principle
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
According to Wikipedia: encapsulation refers to the bundling of data with the methods that operate on that data, or the restricting of direct access to some of an object's components. Encapsulation is used to hide the values or state of a structured data object inside a class, preventing direct access to them by clients in a way that could expose hidden implementation details or violate state invariance maintained by the methods.

What this means is that data which an object uses and is not not needed for any other code, should only be accessible to that object. The object instead provides public methods for other code to get or set it's private variables, but the manipulation of those variables are ultimately under it's control.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single-Responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is merely a definition of an object, while there can be any number of individual instances of that class.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy is the "middleware" which defines the Get and Set methods, among other things. The bcw-create template uses a proxy as an observer
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The MVC pattern defines an architecture framework for an application which consists of the UI, Controllers, Services, and Models. The MVC design pattern creates a pattern for encapsulation
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller should be the only thing that the user can interact with. It controls, manipulates, and draws the user interface, as well as control the user's inputs. The controller should never directly manipulate any data, only relay inputs and outputs.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service controls data, it should not ever interact with the DOM, and the user should never be able to interact with the service.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
Models are the class definitions, which are then instantiated by the services.
```
