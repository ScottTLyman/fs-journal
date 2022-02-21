# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
The Pillars of Object Oriented Programming are Abstraction, Encapsulation, Inheritance, and Polymorphism.
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
return property
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation refers to the bundling of data, along with the methods that operate on that data, into a single unit.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A Class is like a blueprint used to create objects.  An instance of a class is an object created using a specific Class.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A Proxy object allows creation of an object that can be used in place of the original object that may redefine fundamental object operations like getting, sending, and manipulating properties.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose of the MVC pattern is to separate application's concerns.  It controls the data flow to the dom and updates the view whenever it changes. 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is responsible for responding to user input and performing interactions with the dom.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service is responsible for handling the business logic of an application and returning data to the controller.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model gives the controller and service a template for data being manipulated and produced to the dom.
```
