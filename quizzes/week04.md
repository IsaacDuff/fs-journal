# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
asynchronous code is code that runs in the "background". Essentially synchronous code will run in order and is all required as the page loads. Asynchronous code will run in the background while the synchronous code runs. 
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
This is a function that watches a certain variable or object for changes. When a change occurs it will trigger and run whatever it was supplied. 
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
the O is the open-closed principle
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
a callback or higher order function is one that runs outside of the typical js run pattern. it will reach its destination and respond while the synchronous code is actively running. 
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
a promise is a method that will perform its given task and then respond with either a success or failure. We capture it using the catch method to see its success or failure response. 
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
get, put, delete
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
the service will make calls to the api. Only the service handles the moving and transforming of data. 
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Encapsulation allows us to limit the scope of access by our users. It splits the jobs of functions into ones that affect the app or the dom and ones that affect the data. This allows us to give access to the user on certain things but block other/more important things behind walls. 
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
the 200 response, means our stuff went through or was retrieved successfully. 
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
it is an internal server error
```