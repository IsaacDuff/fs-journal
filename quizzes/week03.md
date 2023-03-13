# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
They are Abstraction, Encapsulation, Inheritance and polymorphism
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
console.log(property) would give me the name tim within my console log.
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is the ordering and bundling of data in a private group that cannot be directly accessed or changed by the user but instead by methods and functions calling upon it. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is an object that can that can have different functions and logic inside of it. An instance of a class is an object that is created from a class. 
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is one that allows basic objects operations like get and set to have additional logic set on them. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The MVC is used to make a proper flow for our code. It allows us to separate code into different parts that all have a purpose on what their job is. In addition it allows us to make certain parts of our code private from the user and identify others as usable by them. 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is the holder for all things that change the DOM. Functions tend to start here and anything they do that will change the DOM will be applied here while the rest goes into the service. 
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service is when we apply the parts of our functions that will be accessing and changing data and models. By separating this from the controller function we are able to keep it private and sorted.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model in the mvc is the place where out outlines for our data will be held. Such as the breakdown of an object inside of an array so data can be passed inside to be properly sorted before being applied to that array. It also gives us a place to create models of html we will be creating again and again but changing the data within. 
```
